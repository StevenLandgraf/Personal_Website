---
title: "Efficient Multi-task Uncertainties for Joint Semantic Segmentation and Monocular Depth Estimation"
authors:
- admin
- Markus Hillemann
- Theodor Kapler
- Markus Ulrich
date: "2024"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "DAGM German Conference on Pattern Recognition"
publication_short: "GCPR"

abstract: Quantifying the predictive uncertainty emerged as a possible solution to common challenges like overconfidence, lack of explainability, and robustness of deep neural networks, albeit one that is often computationally expensive. Many real-world applications are multi-modal in nature and hence benefit from multi-task learning. In autonomous driving or robotics, for example, the joint solution of semantic segmentation and monocular depth estimation has proven to be valuable. To this end, we introduce EMUFormer, a novel student-teacher distillation approach for efficient multi-task uncertainties in the context of joint semantic segmentation and monocular depth estimation. By leveraging the predictive uncertainties of the teacher, EMUFormer achieves new state-of-the-art results on Cityscapes and NYUv2 and additionally estimates high-quality predictive uncertainties for both tasks that are comparable or superior to a Deep Ensemble despite being an order of magnitude more efficient.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Deep Learning, Semantic Segmentation, Monocular Depth Estimation, Uncertainty Quantification, Vision Transformer

featured: true

links:
# - name: arXiv
#   url: 
url_pdf: https://link.springer.com/chapter/10.1007/978-3-031-85187-2_22
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
url_project: 'https://stevenlandgraf.github.io/EMUFormer_Website/'
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: Dr. Steven Landgraf'
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
# slides: example
---
<!-- 
This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
