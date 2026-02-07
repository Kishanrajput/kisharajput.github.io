---
title: 'Geometric GNNs for Charged Particle Tracking at GlueX'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Mohammed, A. H.
  - Rajput, K.
  - Taylor, S.
  - Furletov, D.
  - Furletov, S.
  - Schram, M.

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-09-03T00:00:00Z'
doi: 'https://doi.org/10.1088/2632-2153/ae02df'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-journal']

# Publication name and optional abbreviated publication name.
publication: Machine Learning Science and Technology
publication_short: In MLST

abstract: Nuclear physics experiments are aimed at uncovering the fundamental building blocks of matter. The experiments involve high-energy collisions that produce complex events with many particle trajectories. Tracking charged particles resulting from collisions in the presence of a strong magnetic field is critical to enable the reconstruction of particle trajectories and precise determination of interactions. It is traditionally achieved through combinatorial approaches that scale worse than linearly as the number of hits grows. Since particle hit data naturally form a 3-dimensional point cloud and can be structured as graphs, Graph Neural Networks (GNNs) emerge as an intuitive and effective choice for this task. In this study, we evaluate the GNN model for track finding on the data from the GlueX experiment at Jefferson Lab. We use simulation data to train the model and test on both simulation and real GlueX measurements. We demonstrate that GNN-based track finding outperforms the currently used traditional method at GlueX in terms of segment-based efficiency at a fixed purity while providing faster inferences. We show that the GNN model can achieve significant speedup by processing multiple events in batches, which exploits the parallel computation capability of Graphical Processing Units (GPUs). Finally, we compare the GNN implementation on GPU and FPGA and describe the trade-off. 

# Summary. An optional shortened abstract.
summary: Graph Neural Networks (GNN) applied to track charged particle tracking at GlueX experiment at Jefferson Lab. GNN shows better performance compared to traditional method while being faster due to highly parallel nature of GPU machines. The study also presents feasibility of deployment on FPGA and compares with GPU based deployment. 

tags:
  - Graph Neural Networks
  - Machine Learning
  - Physics
  - Tracking
  - FPGA
  - Nuclear Physics

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
# url_slides: ''
url_source: 'https://iopscience.iop.org/article/10.1088/2632-2153/ae02df/meta'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Credit**](https://arxiv.org/abs/2507.15768)'
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
