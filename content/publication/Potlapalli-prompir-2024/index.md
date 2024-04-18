---
# Documentation: https://wowchemy.com/docs/managing-content/

title: PromptIR: Prompting for All-in-One Image Restoration
subtitle: ''
# Summary. An optional shortened abstract.
summary: <span style="font-size:120%;color:#117A65">**NeurIPS 2023**</span> <br> PromptIR utilizes prompt-based learning to restore images across various degradation types and levels, achieving state-of-the-art results in denoising, deraining, and dehazing, providing an efficient plugin module for image restoration without prior knowledge of corruptions.
authors:
- Vaishnav Potlapalli
- admin
- Salman Khan
- Fahad Khan
tags: []
categories: []
date: '2024-02-13'
lastmod: 2024-01-23T13:06:37+04:00
featured: true
draft: false

# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://arxiv.org/abs/2306.13090


url_pdf: ''
url_code: 'https://github.com/va1shn9v/PromptIR'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''



# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2024-02-23T09:06:38.873390Z'
publication_types:
- '1'


abstract: 'Image restoration involves recovering a high-quality clean image from its degraded version. Deep learning-based methods have significantly improved image restoration performance, however, they have limited generalization ability to different degradation types and levels. This restricts their real-world application since it requires training individual models for each specific degradation and knowing the input degradation type to apply the relevant model. We present a prompt-based learning approach, PromptIR, for All-In-One image restoration that can effectively restore images from various types and levels of degradation. In particular, our method uses prompts to encode degradation-specific information, which is then used to dynamically guide the restoration network. This allows our method to generalize to different degradation types and levels, while still achieving state-of-the-art results on image denoising, deraining, and dehazing. Overall, PromptIR offers a generic and efficient plugin module with few lightweight prompts that can be used to restore images of various types and levels of degradation with no prior information on the corruptions present in the image.'
publication: '*Advances in Neural Information Processing Systems 36 (NeurIPS 2023)*'
---
