---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Gated Multi-Resolution Transfer Network for Burst Restoration and Enhancement
subtitle: ''
# Summary. An optional shortened abstract.
summary: <span style="font-size:120%;color:#117A65">**CVPR 2023**</span> <br> A new architecture to reconstruct a spatially-precise high-quality image from a burst of low-quality raw images.
authors:
- Nancy Mehta
- Akshay Dudhane
- Subrahmanyam Murala
- admin
- Salman Khan
- Fahad Khan
tags: []
categories: []
date: '2023-04-23'
lastmod: 2023-04-23T13:06:37+04:00
featured: true
draft: false

# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://arxiv.org/abs/2304.06703


url_pdf: ''
url_code: 'https://github.com/nanmehta/GMTNet'
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
publishDate: '2023-04-23T09:06:38.873390Z'
publication_types:
- '1'


abstract: 'Burst image processing is becoming increasingly popular in recent years. However, it is a challenging task since individual burst images undergo multiple degradations and often have mutual misalignments resulting in ghosting and zipper artifacts. Existing burst restoration methods usually do not consider the mutual correlation and non-local contextual information among burst frames, which tends to limit these approaches in challenging cases. Another key challenge lies in the robust up-sampling of burst frames. The existing up-sampling methods cannot effectively utilize the advantages of single-stage and progressive up-sampling strategies with conventional and/or recent up-samplers at the same time. To address these challenges, we propose a novel Gated Multi-Resolution Transfer Network (GMTNet) to reconstruct a spatially precise high-quality image from a burst of low-quality raw images. GMTNet consists of three modules optimized for burst processing tasks: Multi-scale Burst Feature Alignment (MBFA) for feature denoising and alignment, Transposed-Attention Feature Merging (TAFM) for multi-frame feature aggregation, and Resolution Transfer Feature Up-sampler (RTFU) to up-scale merged features and construct a high- quality output image. Detailed experimental analysis on five datasets validates our approach and sets a state-of-the-art for burst super-resolution, burst denoising, and low-light burst enhancement.'
publication: '*IEEE/CVF Computer Vision and Pattern Recognition (CVPR)*'
---
