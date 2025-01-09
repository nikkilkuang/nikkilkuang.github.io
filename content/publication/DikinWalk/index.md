---
title: "Towards Personalized Language Models via Inference-time Human Preference Optimization"

subtitle: NeurIPS 2024

# categories: NeurIPS

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - (Alphabetical) Yuzhou Gu
  - nikki
  - Yi-An Ma
  - Zhao Song
  - Lichen Zhang

# Author notes (optional)
# author_notes:
#   # - 'Equal contribution'
#   # - 'Equal contribution'
#   - ''
#   - ''
#   - ''
#   - ''
#   - ''

date: "2024-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-05-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "NeurIPS 2024 Workshop on Adaptive Foundation Models"
publication_short: "NeurIPS"

abstract: We consider the problem of sampling from a $d$-dimensional log-concave distribution $\pi(\theta) \propto \exp(-f(\theta))$ for $L$-Lipschitz $f$, constrained to a convex body (described by $n$ hyperplanes) equipped with a barrier function, contained in a ball of radius $R$ with a $w$-warm start. We propose a robust sampling framework that computes spectral approximations to the Hessian of the barrier functions in each iteration. We prove that for the polytope constraints, sampling with the Lee-Sidford barrier function mixes within $\widetilde O((d^2+dL^2R^2)\log(w/\delta))$ steps with a per step cost of $\widetilde O(nd^{\omega-1})$, where $\omega\approx 2.37$ is the fast matrix multiplication exponent. Compared to the prior work of Mangoubi and Vishnoi, our approach gives faster mixing time as we are able to design a generalized soft-threshold Dikin walk beyond log-barrier. 

# Summary. An optional shortened abstract.
summary: (NeurIPS 2024) We design a Dikin walk for log-concave sampling over polytopes and spectrahedra with optimal mixing time and efficient per-iteration cost.

tags:
- Log-concave sampling, Dikin walk

featured: true

# links:
# - name: Custom Link
#   url: http://example.org


url_pdf: 'https://openreview.net/pdf?id=XKrSB5a79F'
url_code: ''
url_dataset: ''
url_poster: 'https://neurips.cc/media/PosterPDFs/NeurIPS%202024/94777.png?t=1732321697.4782073'
url_project: 'https://neurips.cc/virtual/2024/poster/94777'
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
