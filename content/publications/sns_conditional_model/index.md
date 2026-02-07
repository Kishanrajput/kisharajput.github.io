---
title: "Robust errant beam prognostics with conditional modeling for particle accelerators"
authors:
- Rajput, K.
- Schram, M.
- Blokland, W.
- Alanazi, Y.
- Ramuhalli, P.
- Zhukov, A.
- Peters, C.
- Vilalta, R.
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2024-03-08T00:00:00Z"
doi: "https://doi.org/10.1088/2632-2153/ad2e18"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Machine Learning: Science and Technology, Volume 5, Number 1, Article 015044"
publication_short: "MLST"

abstract: Particle accelerators are complex and comprise thousands of components, with many pieces of equipment running at their peak power. Consequently, they can fault and abort operations for numerous reasons, lowering efficiency and science output. To avoid these faults, we apply anomaly detection techniques to predict unusual behavior and perform preemptive actions to improve the total availability. Supervised machine learning (ML) techniques such as siamese neural network models can outperform the often-used unsupervised or semi-supervised approaches for anomaly detection by leveraging the label information. One of the challenges specific to anomaly detection for particle accelerators is the data’s variability due to accelerator configuration changes within a production run of several months. ML models fail at providing accurate predictions when data changes due to changes in the configuration. To address this challenge, we include the configuration settings into our models and training to improve the results. Beam configurations are used as a conditional input for the model to learn any cross-correlation between the data from different conditions and retain its performance. We employ conditional siamese neural network (CSNN) models and conditional variational auto encoder (CVAE) models to predict errant beam pulses at the spallation neutron source under different system configurations and compare their performance. We demonstrate that CSNNs outperform CVAEs in our application.

# Summary. An optional shortened abstract.
summary: Conditional Models to handle data drifts due to changes in beam configuration changes at SNS accelerator.

tags:
- Machine Learning
- Data Drift
- Auto Encoder
- Conditional Model
- Fault Prediction
- Anomly Detection
- Particle Accelerator

featured: false

url_pdf: 'https://iopscience.iop.org/article/10.1088/2632-2153/ad2e18/pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://iopscience.iop.org/article/10.1088/2632-2153/ad2e18'
url_video: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**MLST**](https://iopscience.iop.org/article/10.1088/2632-2153/ad2e18)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
