---
title: 'Uncertainty-aware Cross-Entropy for Semantic Segmentation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Markus Hillemann
  - Kira Wursthorn
  - Markus Ulrich

date: '2024-06-10T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2025-04-24T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: in ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences

abstract: Deep neural networks have shown exceptional performance in various tasks, but their lack of robustness, reliability, and tendency to be overconfident pose challenges for their deployment in safety-critical applications like autonomous driving. In this regard, quantifying the uncertainty inherent to a model's prediction is a promising endeavour to address these shortcomings. In this work, we present a novel Uncertainty-aware Cross-Entropy loss (U-CE) that incorporates dynamic predictive uncertainties into the training process by pixel-wise weighting of the well-known cross-entropy loss (CE). Through extensive experimentation, we demonstrate the superiority of U-CE over regular CE training on two benchmark datasets, Cityscapes and ACDC, using two common backbone architectures, ResNet-18 and ResNet-101. With U-CE, we manage to train models that not only improve their segmentation performance but also provide meaningful uncertainties after training. Consequently, we contribute to the development of more robust and reliable segmentation models, ultimately advancing the state-of-the-art in safety-critical applications and beyond.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Deep Learning
  - Semantic Segmentation
  - Uncertainty Quantification

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Project Website
  url: https://stevenlandgraf.github.io/U-CE_Website/
url_pdf: https://isprs-annals.copernicus.org/articles/X-2-2024/129/2024/
url_code: https://github.com/StevenLandgraf/U-CE
# url_dataset: '#'
# url_poster: '#'
# url_project: https://stevenlandgraf.github.io/EMUFormer_Website/
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
