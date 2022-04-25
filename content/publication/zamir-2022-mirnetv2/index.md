---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Learning Enriched Features for Fast Image Restoration and Enhancement
# Summary. An optional shortened abstract.
summary: <span style="font-size:120%;color:#117A65">**TPAMI 2022**</span> <br>  A novel feature extraction model that obtains a complementary set of features across multiple spatial scales, while maintaining the original high-resolution features to preserve precise spatial details.
authors:
- admin
- Aditya Arora
- Salman Khan
- Munawar Hayat
- Fahad Shahbaz Khan
- Ming-Hsuan Yang
- Ling Shao
tags: []
categories: []
date: '2022-04-25'
lastmod: 2022-04-25T13:06:37+04:00
featured: true
draft: false

# Custom links (uncomment lines below)


url_pdf: ''
url_code: 'https://github.com/swz30/MIRNetv2'
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
publishDate: '2022-04-25T09:06:37.554268Z'
publication_types:
- '2'
abstract: 'Given a degraded input image, image restoration aims to recover the missing high-quality image content. Numerous
applications demand effective image restoration, e.g., computational photography, surveillance, autonomous vehicles, and remote
sensing. Significant advances in image restoration have been made in recent years, dominated by convolutional neural networks
(CNNs). The widely-used CNN-based methods typically operate either on full-resolution or on progressively low-resolution
representations. In the former case, spatial details are preserved but the contextual information cannot be precisely encoded. In the
latter case, generated outputs are semantically reliable but spatially less accurate. This paper presents a new architecture with a
holistic goal of maintaining spatially-precise high-resolution representations through the entire network, and receiving complementary
contextual information from the low-resolution representations. The core of our approach is a multi-scale residual block containing the
following key elements: (a) parallel multi-resolution convolution streams for extracting multi-scale features, (b) information exchange
across the multi-resolution streams, (c) non-local attention mechanism for capturing contextual information, and (d) attention based
multi-scale feature aggregation. Our approach learns an enriched set of features that combines contextual information from multiple
scales, while simultaneously preserving the high-resolution spatial details. Extensive experiments on six real image benchmark
datasets demonstrate that our method, named as MIRNet-v2 , achieves state-of-the-art results for a variety of image processing tasks,
including defocus deblurring, image denoising, super-resolution, and image enhancement.'
publication: '*IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)*'
---
