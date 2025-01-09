---
title: 'Langevin Thompson sampling with logarithmic communication: bandits and reinforcement learning'

subtitle: ICML 2023

# categories: ICML

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Nikki Lijing Kuang*
  - Siddharth Mitra*
  - Amin Karbasi
  - Yi-An Ma

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'
  - ''
  - ''
  - ''
  - ''

date: '2023-06-22T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "International Conference on Machine Learning (ICML)"
publication_short: "ICML"

abstract: Thompson sampling (TS) is widely used in sequential decision making due to its ease of use and appealing empirical performance. However, many existing analytical and empirical results for TS rely on restrictive assumptions on reward distributions, such as belonging to conjugate families, which limits their applicability in realistic scenarios. Moreover, sequential decision making problems are often carried out in a batched manner, either due to the inherent nature of the problem or to serve the purpose of reducing communication and computation costs. In this work, we jointly study these problems in two popular settings, namely, stochastic multi-armed bandits (MABs) and infinite-horizon reinforcement learning (RL), where TS is used to learn the unknown reward distributions and transition dynamics, respectively. We propose batched Langevin Thompson Sampling algorithms that leverage MCMC methods to sample from approximate posteriors with only logarithmic communication costs in terms of batches. Our algorithms are computationally efficient and maintain the same order-optimal regret guarantees of for stochastic MABs, and for RL. We complement our theoretical findings with experimental results.

# Summary. An optional shortened abstract.
summary: (ICML 2023) We study approximate Thompson Sampling with Markov Chain Monte Carlo in bandit and reinforcement learning frameworks, providing algorithms that achieve optimal performance with low computation and communication cost.

tags: 
- Batched Langevin RL
- Reinforcement Learning
- Langevin Monte Carlo
- MCMC

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://proceedings.mlr.press/v202/karbasi23a/karbasi23a.pdf'
url_code: ''
url_dataset: ''
url_poster: 'https://icml.cc/media/PosterPDFs/ICML%202023/23638.png?t=1690654535.0261657'
url_project: 'https://icml.cc/virtual/2023/poster/23638'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  caption: ''
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
slides: ""
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->