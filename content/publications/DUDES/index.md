---
title: 'Deep Uncertainty Distillation using Ensembles for Semantic Segmentation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Kira Wursthorn
  - Markus Hillemann
  - Markus Ulrich

date: '2024-03-25T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2025-04-24T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In PFG - Journal of Photogrammetry, Remote Sensing and Geoinformation Science
publication_short: In PFG

abstract: The intersection of deep learning and photogrammetry unveils a critical need for balancing the power of deep neural networks with interpretability and trustworthiness, especially for safety-critical application like autonomous driving, medical imaging, or machine vision tasks with high demands on reliability. Quantifying the predictive uncertainty is a promising endeavour to open up the use of deep neural networks for such applications. Unfortunately, most current available methods are computationally expensive. In this work, we present a novel approach for efficient and reliable uncertainty estimation for semantic segmentation, which we call Deep Uncertainty Distillation using Ensembles for Segmentation (DUDES). DUDES applies student-teacher distillation with a Deep Ensemble to accurately approximate predictive uncertainties with a single forward pass while maintaining simplicity and adaptability. Experimentally, DUDES accurately captures predictive uncertainties without sacrificing performance on the segmentation task and indicates impressive capabilities of highlighting wrongly classified pixels and out-of-domain samples through high uncertainties on the Cityscapes and Pascal VOC 2012 dataset. With DUDES, we manage to simultaneously simplify and outperform previous work on Deep-Ensemble-based Uncertainty Distillation.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Deep Learning
  - Semantic Segmentation
  - Uncertainty Quantification
  - Vision Transformer

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Project Website
  url: https://stevenlandgraf.github.io/DUDES_Website/
url_pdf: https://link.springer.com/article/10.1007/s41064-024-00280-4
url_code: https://github.com/StevenLandgraf/DUDES
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
