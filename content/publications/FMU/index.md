---
title: 'A Critical Synthesis of Uncertainty Quantification and Foundation Models in Monocular Depth Estimation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Rongjun Qin
  - Markus Ulrich

date: '2025-01-14T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2025-04-24T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: arXiv

abstract: While recent foundation models have enabled significant breakthroughs in monocular depth estimation, a clear path towards safe and reliable deployment in the real-world remains elusive. Metric depth estimation, which involves predicting absolute distances, poses particular challenges, as even the most advanced foundation models remain prone to critical errors. Since quantifying the uncertainty has emerged as a promising endeavor to address these limitations and enable trustworthy deployment, we fuse five different uncertainty quantification methods with the current state-of-the-art DepthAnythingV2 foundation model. To cover a wide range of metric depth domains, we evaluate their performance on four diverse datasets. Our findings identify fine-tuning with the Gaussian Negative Log-Likelihood Loss (GNLL) as a particularly promising approach, offering reliable uncertainty estimates while maintaining predictive performance and computational efficiency on par with the baseline, encompassing both training and inference time. By fusing uncertainty quantification and foundation models within the context of monocular depth estimation, this paper lays a critical foundation for future research aimed at improving not only model performance but also its explainability. Extending this critical synthesis of uncertainty quantification and foundation models into other crucial tasks, such as semantic segmentation and pose estimation, presents exciting opportunities for safer and more reliable machine vision systems.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Deep Learning
  - Monocular Depth Estimation
  - Uncertainty Quantification
  - Vision Transformer

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Project Website
  url: https://stevenlandgraf.github.io/FoundationDepthUQ_Website/
url_pdf: https://arxiv.org/abs/2501.08188
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
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
