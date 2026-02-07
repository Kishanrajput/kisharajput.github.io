---
title: 'Explainable physics-based constraints on reinforcement learning for accelerator controls'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Colen, J.
  - Schram, M.
  - Rajput, K.
  - Kasparian, A.

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-02-27T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2502.20247'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-preprint']

# Publication name and optional abbreviated publication name.
publication: Preprint Arxiv
publication_short: Preprint

abstract: We present a reinforcement learning (RL) framework for controlling particle accelerator experiments that builds explainable physics-based constraints on agent behavior. The goal is to increase transparency and trust by letting users verify that the agent's decision-making process incorporates suitable physics. Our algorithm uses a learnable surrogate function for physical observables, such as energy, and uses them to fine-tune how actions are chosen. This surrogate can be represented by a neural network or by an interpretable sparse dictionary model. We test our algorithm on a range of particle accelerator controls environments designed to emulate the Continuous Electron Beam Accelerator Facility (CEBAF) at Jefferson Lab. By examining the mathematical form of the learned constraint function, we are able to confirm the agent has learned to use the established physics of each environment. In addition, we find that the introduction of a physics-based surrogate enables our reinforcement learning algorithms to reliably converge for difficult high-dimensional accelerator controls environments. 

# Summary. An optional shortened abstract.
summary:  By examining the mathematical form of the learned constraint function, we are able to confirm the agent has learned to use the established physics of each environment. In addition, we find that the introduction of a physics-based surrogate enables our reinforcement learning algorithms to reliably converge for difficult high-dimensional accelerator controls environments. 

tags:
  - Reinforcement Learning
  - Physics
  - Multi-objective
  - Optimization
  - Controls
  - Particle Accelerator

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
url_source: 'https://arxiv.org/abs/2502.20247'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Credit**](https://arxiv.org/abs/2502.20247)'
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
