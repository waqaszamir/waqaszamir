---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Burstormer: Burst Image Restoration and Enhancement Transformer
subtitle: ''
# Summary. An optional shortened abstract.
summary: <span style="font-size:120%;color:#117A65">**CVPR 2023**</span> <br> we develop a novel Transformer based design for burst-image restoration and enhancement that leverages multi-scale local and non-local features for improved alignment and feature fusion. Its flexible design allows processing bursts of variable sizes.
authors:
- Akshay Dudhane
- admin
- Salman Khan
- Fahad Khan
- Ming-Hsuan Yang
tags: []
categories: []
date: '2023-04-01'
lastmod: 2023-04-07T13:06:37+04:00
featured: true
draft: false

# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://arxiv.org/abs/2304.01194


url_pdf: ''
url_code: 'https://github.com/akshaydudhane16/Burstormer'
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
publishDate: '2023-04-07T13:06:37+04:00'
publication_types:
- '1'


abstract: 'On a shutter press, modern handheld cameras capture multiple images in rapid succession and merge them to generate a single image. However, individual frames in a burst
are misaligned due to inevitable motions and contain multiple degradations. The challenge is to properly align the successive image shots and merge their complimentary information to achieve high-quality outputs. Towards this direction, we propose Burstormer: a novel transformer-based architecture for burst image restoration and enhancement. In comparison to existing works, our approach exploits multi-scale local and non-local features to achieve improved alignment and feature fusion. Our key idea is to enable inter-frame communication in the burst neighborhoods for information aggregation and progressive fusion while modeling the burst-wide context. However, the input burst frames need to be properly aligned before fusing their information. Therefore, we propose an enhanced deformable alignment module for aligning burst features with regards to the reference frame. Unlike existing methods, the proposed alignment module not only aligns burst features but also exchanges feature information and maintains focused communication with the reference frame through the proposed reference-based feature enrichment mechanism, which facilitates handling complex motions. After multi-level alignment and enrichment, we re-emphasize on inter-frame communication within burst using a cyclic burst sampling module. Finally, the inter-frame information is aggregated using the proposed burst feature fusion module followed by progressive upsampling. Our Burstormer outperforms state-of-the-art methods on burst super-resolution, burst denoising and burst low-light enhancement.'
publication: '*IEEE/CVF Computer Vision and Pattern Recognition (CVPR)*'
---
