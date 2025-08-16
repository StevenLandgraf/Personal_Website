---
title: 'A Comparative Study on Multi-task Uncertainty Quantification in Semantic Segmentation and Monocular Depth Estimation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Markus Hillemann
  - Theodor Kapler
  - Markus Ulrich

date: '2025-04-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2025-04-24T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In De Gruyter Journal, tm - Technisches Messen
publication_short: In TM

abstract: Deep neural networks excel in perception tasks such as semantic segmentation and monocular depth estimation, making them indispensable in safety-critical applications like autonomous driving and industrial inspection. However, they often suffer from overconfidence and poor explainability, especially for out-of-domain data. While uncertainty quantification has emerged as a promising solution to these challenges, multi-task settings have yet to be explored. In an effort to shed light on this, we evaluate Monte Carlo Dropout, Deep Sub-Ensembles, and Deep Ensembles for joint semantic segmentation and monocular depth estimation. Thereby, we reveal that Deep Ensembles stand out as the preferred choice, particularly in out-of-domain scenarios, and show the potential benefit of multi-task learning with regard to the uncertainty quality in comparison to solving both tasks separately. Additionally, we highlight the impact of employing different uncertainty thresholds to classify pixels as certain or uncertain, with the median uncertainty emerging as a robust default.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Deep Learning
  - Semantic Segmentation
  - Monocular Depth Estimation
  - Uncertainty Quantification
  - Vision Transformer

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Project Website
  url: https://stevenlandgraf.github.io/Multi-task_Uncertainties_Website/
url_pdf: https://www.degruyterbrill.com/document/doi/10.1515/teme-2025-0004/html
# url_code: https://github.com/StevenLandgraf/DUDES
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: Dr. Steven Landgraf'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - []

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
