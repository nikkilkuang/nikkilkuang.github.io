---
title: 'Towards Robust Estimation of Intention Hierarchy in Robot Teleoperation'

subtitle: NeurIPS 2024 Workshop on Open-World Agents

# categories: NeurIPS

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - nikki
  - Soshi Iba
  - Songpo Li

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'
  - ''
  - ''
  - ''


date: '2024-03-30T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-30T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "NeurIPS 2024 Workshop on Open-World Agents"
publication_short: "NeurIPS"

abstract: The last few decades have witnessed the widespread adoption of robot teleoperation across a myriad of real-world domains, including manufacturing, healthcare, military, and beyond. It has been recognized as an effective approach to assist humans in remotely tackling tasks that pose significant challenges and risks when undertaken alone. To improve the efficiency of collaboration between human and robot in teleoperated systems, it is essential to facilitate the robot to precisely infer human intentions. In this work, we introduce RoHIE, a novel architecture designed to reason about the intentions of the human partner at different levels of granularity. In particular, it leverages non-verbal observations that capture the motion and gaze information in shared autonomy, and learns a flexible intention hierarchy to categorize the relationship between low-level action primitives and higher-level task goals, thereby enabling robust inference. Moreover, by learning a compact representation in the embedding space, our framework captures the latent structural information of human behaviors from human partners' demonstrations, empowering the robot to robustly and accurately estimate the intention of new human companions. We further collect a teleoperation dataset featuring different human participants engaged in a variety of building block assembly tasks, and rigorously validate the efficacy of our approach against baseline methods with various evaluation metrics.

# Summary. An optional shortened abstract.
summary: (NeurIPS 2024 Workshop) We propose a novel architecture to reason about the intentions of the human partner in assistive robot teleoperation through non-verbal observations.

tags: 
- Intention estimation
- Robot Teleoperation

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=keDB5bPY5Z'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://openreview.net/forum?id=keDB5bPY5Z'
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