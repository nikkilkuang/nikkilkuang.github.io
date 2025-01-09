---
title: 'Statistical and computational trade-offs in variational inference: A case study in inferential model selection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Nikki Lijing Kuang*
  - Kush Bhatia*
  - Yian Ma*
  - Yixin Wang*

# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - ''
  # - 'Equal contribution'
  # - 'Equal contribution'
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2022-07-01T00:00:00Z'
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ["article-journal"]
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: "Preprint"
publication_short: " "

abstract: Variational inference has recently emerged as a popular alternative to the classical Markov chain Monte Carlo (MCMC) in large-scale Bayesian inference. The core idea is to trade statistical accuracy for computational efficiency. In this work, we study these statistical and computational trade-offs in variational inference via a case study in inferential model selection. Focusing on Gaussian inferential models (or variational approximating families) with diagonal plus low-rank precision matrices, we initiate a theoretical study of the trade-offs in two aspects, Bayesian posterior inference error and frequentist uncertainty quantification error. From the Bayesian posterior inference perspective, we characterize the error of the variational posterior relative to the exact posterior. We prove that, given a fixed computation budget, a lower-rank inferential model produces variational posteriors with a higher statistical approximation error, but a lower computational error; it reduces variance in stochastic optimization and, in turn, accelerates convergence. From the frequentist uncertainty quantification perspective, we consider the precision matrix of the variational posterior as an uncertainty estimate, which involves an additional statistical error originating from the sampling uncertainty of the data. As a consequence, for small datasets, the inferential model need not be full-rank to achieve optimal estimation error (even with unlimited computation budget).


# Summary. An optional shortened abstract.
summary: (Preprint) We provide a rigorous study of the statistical and computational trade-offs for variational inference (VI).

tags:
- Variational inference
# - Statistical and computational trade-offs
# - Non-asymptotic analysis

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2207.11208'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
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
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
