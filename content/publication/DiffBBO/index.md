---
title: "Diff-BBO: Diffusion-Based Inverse Modeling for Black-Box Optimization"

subtitle: NeurIPS 2024 Workshop on Bayesian Decision-making and Uncertainty

# categories: NeurIPS

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Dongxia Wu*
  - Nikki Lijing Kuang*
  - Ruijia Niu
  - Yi-An Ma
  - Rose Yu

# Author notes (optional)
# author_notes:
#   # - 'Equal contribution'
#   # - 'Equal contribution'
#   - ''
#   - ''
#   - ''
#   - ''
#   - ''

date: "2024-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-10-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "NeurIPS 2024 Workshop on Bayesian Decision-making and Uncertainty"
publication_short: "NeurIPS"

abstract: Black-box optimization (BBO) aims to optimize an objective function by iteratively querying a black-box oracle in a sample-efficient way. While prior studies focus on forward approaches to learn surrogates for the unknown objective function, they struggle with steering clear of out-of-distribution and invalid inputs. Recently, inverse modeling approaches that map objective space to the design space with conditional diffusion models have demonstrated impressive capability in learning the data manifold. They have shown promising performance in offline BBO tasks. However, these approaches require a pre-collected dataset. How to design the acquisition function for inverse modeling to actively query new data remains an open question. In this work, we propose diffusion-based inverse modeling for black-box optimization (Diff-BBO), an inverse approach leveraging diffusion models for online BBO problem. Instead of proposing candidates in the design space, Diff-BBO employs a novel acquisition function Uncertainty-aware Exploration (UaE) to propose objective function values. Subsequently, we employ a conditional diffusion model to generate samples based on these proposed values within the design space. We demonstrate that using UaE results in optimal optimization outcomes, supported by both theoretical and empirical evidence.

# Summary. An optional shortened abstract.
summary: (NeurIPS 2024 Workshop) We propose an inverse modeling approach with a novel acquisition function named Uncertainty-aware Exploration (UaE) for efficient online black-box optimization using classifier-free conditional diffusion models.

tags:
- Diffusion models, Black-box Optimization, Uncertainty Quantification

featured: true

# links:
# - name: Custom Link
#   url: http://example.org


url_pdf: 'https://arxiv.org/abs/2407.00610'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://openreview.net/forum?id=KizOx8SheQ'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
