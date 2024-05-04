---
title: "Posterior sampling with delayed feedback for reinforcement learning with linear function approximation"

subtitle: NeurIPS 2023

# categories: NeurIPS

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Nikki Lijing Kuang*
  - Ming Yin*
  - Mengdi Wang
  - Yu-Xiang Wang 
  - Yi-An Ma

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'
  - ''
  - ''
  - ''
  - ''
  - ''

date: "2024-02-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "Advances in Neural Information Processing Systems (NeurIPS)"
publication_short: "NeurIPS"

abstract: Recent studies in reinforcement learning (RL) have made significant progress by leveraging function approximation to alleviate the sample complexity hurdle for better performance. Despite the success, existing provably efficient algorithms typically rely on the accessibility of immediate feedback upon taking actions. The failure to account for the impact of delay in observations can significantly degrade the performance of real-world systems due to the regret blow-up. In this work, we tackle the challenge of delayed feedback in RL with linear function approximation by employing posterior sampling, which has been shown to empirically outperform the popular UCB algorithms in a wide range of regimes. We first introduce \textit{Delayed-PSVI}, an optimistic value-based algorithm that effectively explores the value function space via noise perturbation with posterior sampling. We provide the first analysis for posterior sampling algorithms with delayed feedback in RL and show our algorithm achieves worst-case regret in the presence of unknown stochastic delays. Here is the expected delay. To further improve its computational efficiency and to expand its applicability in high-dimensional RL problems, we incorporate a gradient-based approximate sampling scheme via Langevin dynamics for \textit{Delayed-LPSVI}, which maintains the same order-optimal regret guarantee with computational cost. Empirical evaluations are performed to demonstrate the statistical and computational efficacy of our algorithms.

# Summary. An optional shortened abstract.
summary: (NeurIPS 2023) We provide the first theoretical analysis for the class of posterior sampling algorithms to handle delayed feedback in RL frameworks.

tags:
- PSRL

featured: true

# links:
# - name: Custom Link
#   url: http://example.org


url_pdf: https://openreview.net/pdf?id=RiyH3z7oIF
url_code: ''
url_dataset: ''
url_poster: 'https://neurips.cc/media/PosterPDFs/NeurIPS%202023/71646.png?t=1702362883.9005537'
url_project: 'https://neurips.cc/virtual/2023/poster/71646'
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
