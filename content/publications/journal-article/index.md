---
title: "Harnessing the power of gradient-based simulations for multi-objective optimization in particle accelerators"
authors:
- Rajput, K.
- Schram, M.
- Edelen, A.
- Colen, J.
- Kasparian, A.
- Roussel, R.
- Carpenter, A.
- Zhang, H.
- Benesch, J.
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2025-04-16T00:00:00Z"
doi: "https://doi.org/10.1088/2632-2153/adc221"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Harnessing the power of gradient-based simulations for multi-objective optimization in particle accelerators"
publication_short: "Differential Reinforcement Learning"

abstract: Particle accelerator operation requires simultaneous optimization of multiple objectives. Multi-objective optimization (MOO) is particularly challenging due to trade-offs between the objectives. Evolutionary algorithms, such as genetic algorithms (GAs), have been leveraged for many optimization problems, however, they do not apply to complex control problems by design. This paper demonstrates the power of differentiability for solving MOO problems in particle accelerators using a deep differentiable reinforcement learning (DDRL) algorithm. We compare the DDRL algorithm with model-free reinforcement learning (MFRL), GA, and Bayesian optimization (BO) for simultaneous optimization of heat load and trip rates in the continuous electron beam accelerator facility. The underlying problem enforces strict constraints on both individual states and actions as well as cumulative (global) constraints on energy requirements of the beam. Using historical accelerator data, we develop a physics-based surrogate model which is differentiable and allows for back-propagation of gradients. The results are evaluated in the form of a Pareto-front with two objectives. We show that the DDRL outperforms MFRL, BO, and GA on high dimensional problems.

# Summary. An optional shortened abstract.
summary: Differential Reinforcement Learning outperforms Multi-objective TD3, Multi-Objective Bayesian Optimization, Multi-objective Genetic Algorithms on highly complex constrained optimization problems.

tags:
- Reinforcement Learning
- Optimization
- Controls
- Differential Simulation
- Bayesian Optimization
- Multi-objective

featured: true

url_pdf: https://iopscience.iop.org/article/10.1088/2632-2153/adc221/pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: https://iopscience.iop.org/article/10.1088/2632-2153/adc221
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://iopscience.iop.org/article/10.1088/2632-2153/adc221)'
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
slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
