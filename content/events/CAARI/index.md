---
title: Errant Beam Prognostics with Machine Leaning at SNS Accelerator
talk_type: Invited Talk

event: 27th International Conference on the Application of Accelerators in Research and Industry (CAARI) and the 55th Symposium of Northeastern Accelerator Personnel (SNEAP)
event_url: https://caari-sneap.com/home

location: Fort Worth, TX, USA
address:
  street: Worthington Renaissance Hotel
  city: Fort Worth, TX, Switzerland
  country: USA

summary: '<span class="inline-block px-2 py-1 text-xs font-semibold rounded-full bg-yellow-100 text-yellow-800 dark:bg-yellow-900 dark:text-yellow-100 mr-2 mb-2">Invited Talk</span> Talk on application of conditional machine learning models to predict anomalies before they occur at SNS accelerator.'
abstract: "Particle Accelerators are complex machine with many pieces of equipment running in synchronization to deliver required beam. However, faults in particle accelerators reduce the availability of the beam for experiments affecting the overall science output. To avoid these faults, we apply anomaly detection techniques to predict any unusual behavior and perform preemptive actions to improve the total availability. Many researchers have adopted semi-supervised Machine Learning (ML) methods such as auto-encoders and variational auto-encoders for such tasks. However, supervised ML techniques designed for similarity learning such as Siamese Neural Network (SNN) can outperform semi-supervised or unsupervised methods for anomaly prediction. One of the challenges associated with application of ML models to particle accelerators is the variability in observed data over time due to system configuration changes. We employ conditional models such as Conditional Siamese Neural Networks (CSNN), and Conditional-VAE (CVAE) to learn the variability in the data by using beam configuration parameters as conditional input. We apply these models for errant beam prediction at Spallation Neutron Source accelerator under different system configurations and compare their performance. We demonstrate that CSNN outperforms CVAE in our application. This talk will present the data source, collection, analysis, data-preparation, model development, hyper-parameter studies and the results."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-07-22T11:00:00Z'
date_end: '2024-07-22T11:15:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags:
  - Invited Talk
  - Particle Accelerator
  - Spallation Neutron Source
  - SNS
  - Diagnostics
  - Machine Learning
  - Anomaly Prediction
  - Conditional Model


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
# url_slides: 'https://indico.cern.ch/event/1382428/contributions/6283318/attachments/3048032/5386212/GradRL_talk.pptx'
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
