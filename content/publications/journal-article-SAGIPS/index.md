---
title: 'SAGIPS: a physics-inspired scalable asynchronous generative inverse-problem solver'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Lersch, D.
  - Schram, M.
  - Dai, Z.
  - Rajput, K.
  - Sato, N.
  - Wu, X.
  - Childers, J. T.
  - Goldenberg, S.

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-04-16T00:00:00Z'
doi: 'https://doi.org/10.1088/2632-2153/adc8fb'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-journal']

# Publication name and optional abbreviated publication name.
publication: In Machine Learning Science and Technology
publication_short: In MLST

abstract: Solving large-scale inverse problems using deep-learning algorithms have become an essential part of modern research and industrial applications. The complexity of the underlying inverse problem may require the utilization of high performance computing systems which poses a challenge on the algorithmic design of the inverse problem solver. Most deep learning algorithms require, due to their design, custom parallelization techniques in order to be resource efficient while showing a reasonable convergence. In this paper we introduce a Scalable Asynchronous Generative Inverse Problem Solver (SAGIPS) on high-performance computing systems. We present a workflow that utilizes an asynchronous ring-allreduce algorithm to transfer the gradients of the generator network across multiple GPUs. Experiments with a scientific proxy application demonstrate that SAGIPS shows near linear weak scaling, together with a convergence quality that is comparable to traditional methods. The approach presented here allows leveraging Generative Adverserial Network across multiple GPUs, promising advancements in solving complex inverse problems at scale.

# Summary. An optional shortened abstract.
summary: A Scalable Asynchronous Generative Inverse Problem Solver (SAGIPS) on high-performance computing systems. We present a workflow that utilizes an asynchronous ring-allreduce algorithm to transfer the gradients of the generator network across multiple GPUs. Experiments with a scientific proxy application demonstrate that SAGIPS shows near linear weak scaling, together with a convergence quality that is comparable to traditional methods. The approach presented here allows leveraging Generative Adverserial Network across multiple GPUs, promising advancements in solving complex inverse problems at scale.

tags:
  - High Performance Computing
  - HPC
  - Generative Models
  - GAN
  - Machine Learning

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://iopscience.iop.org/article/10.1088/2632-2153/adc8fb/pdf'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
url_source: 'https://iopscience.iop.org/article/10.1088/2632-2153/adc8fb/meta'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://iopscience.iop.org/article/10.1088/2632-2153/adc8fb/meta)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
