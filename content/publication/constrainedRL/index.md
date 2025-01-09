---
title: 'Sample Efficient Constrained Reinforcement Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - nikki


# Author notes (optional)
# author_notes:
#   - 'Equal contribution'

date: "2020-06-18T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['thesis']

# Publication name and optional abbreviated publication name.
publication: "Master thesis"
publication_short: "Master thesis"

abstract: The general assumption in reinforcement learning(RL) that agents are free to explore for searching optimal policies limits its applicability in real-world domains where safe exploration is desired. In this paper, we study the problem of constrained RL in episodic MDPs to investigate efficient exploration in safe RL. We formally describe two different constraint schemes frequently considered in empirical studies --- namely, soft constrained RL that focuses on the overall safety satisfaction, and hard constrained RL that aims to provide guarantees throughout learning. While violations may occur in the former scheme, the latter enforces safety by extending the challenging knapsack problem in multi-armed bandits. Accordingly, we propose two novel sample efficient constrained Q-learning algorithms. By balancing exploration and exploitation based on UCB, our methods reduce the notoriously high sample complexity in constrained model-free settings while achieving asymptotically optimal solutions. Our theoretical analyses establish promising regret bounds for both algorithms.

# Summary. An optional shortened abstract.
summary: We propose sample efficient algorithms for constrained RL frameworks.

tags:
- Constrained RL, Reinforcement Learning

featured: true

# links:
# - name: Custom Link
#   url: http://example.org


url_pdf: 'https://escholarship.org/content/qt528236n5/qt528236n5.pdf'
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
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

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
