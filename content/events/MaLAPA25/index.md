---
title: Harnessing the Power of Gradient Based Simulations for Multi-Objective Optimization in Particle Accelerators
talk_type: Invited Talk

event: 5th Beam Dynamics Workshop on Applications of Machine Learning in Particle Accelerators
event_url: https://indico.cern.ch/event/1382428/

location: European Organization for Nuclear Research (CERN), Geneva, Switzerland
address:
  street: 80/1-001 - Globe of Science and Innovation - 1st Floor (CERN)
  city: Geneva, Switzerland
  country: Switzerland

summary: Talk on applying fast optimization and control with differential reinforcement learning leveraging differential simulations.
abstract: "Particle accelerator operation requires simultaneous optimization of multiple objectives. Multi-Objective Optimization (MOO) is particularly challenging due to trade-offs between the objectives. Evolutionary algorithms, such as genetic algorithm (GA), have been leveraged for many optimization problems, however, they do not apply to complex control problems by design. This paper demonstrates the power of differentiability for solving MOO problems using a Deep Differentiable Reinforcement Learning (DDRL) algorithm in particle accelerators. We compare DDRL algorithm with Model Free Reinforcement Learning (MFRL), GA and Bayesian Optimization (BO) for simultaneous optimization of heat load and trip rates in the Continuous Electron Beam Accelerator Facility (CEBAF). The underlying problem enforces strict constraints on both individual states and actions as well as cumulative (global) constraint for energy requirements of the beam. A physics-based surrogate model based on real data is developed. This surrogate model is differentiable and allows back-propagation of gradients. The results are evaluated in the form of a Pareto-front for two objectives. We show that the DDRL outperforms MFRL, BO, and GA on high dimensional problems."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-04-09T11:00:00Z'
date_end: '2025-04-09T11:15:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags:
  - Multi-objective optimization
  - Controls
  - Reinforcement Learning
  - Multi-objective RL
  - Particle Accelerator
  - CEBAF
  - Differential Programming


# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Kishan**]()'
  focal_point: Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
# url_code: 'https://github.com'
# url_pdf: ''
url_slides: 'https://indico.cern.ch/event/1382428/contributions/6283318/attachments/3048032/5386212/GradRL_talk.pptx'
# url_video: 'https://youtube.com'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - example
---

<!-- {{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page. -->
