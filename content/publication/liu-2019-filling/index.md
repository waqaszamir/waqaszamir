---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Filling the gaps in atrous convolution: semantic segmentation with a better context'
subtitle: ''
summary: ''
authors:
- Liyuan Liu
- Yanwei Pang
- admin
- Salman Khan
- Fahad Shahbaz Khan
- Ling Shao
tags: []
categories: []
date: '2019-01-01'
lastmod: 2022-04-07T13:06:40+04:00
featured: false
draft: false

# Custom links (uncomment lines below)
links:
- name: Paper
  url: https://ieeexplore.ieee.org/document/8861330


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
publishDate: '2022-04-07T09:06:40.538371Z'
publication_types:
- '2'
abstract: 'The main challenge for scene parsing arises when complex scenes with highly diverse objects are encountered. The objects not only differ in scale and appearance but also in semantics. Previous works focus on encoding the multi-scale contextual information (via pooling or atrous convolutions) generally on top of compact high-level features (i.e., at a single stage). In this work, we argue that a rich set of cues exist at multiple stages of the network, encapsulating low, mid and high-level scene details. Therefore, an optimal scene parsing model must aggregate multi-scale context at all three levels of the feature hierarchy; a capability that lacks in state-of-the-art scene parsing models. To address this limitation, we introduce a novel architecture with three new blocks that systematically aggregate low, mid and high tier features. The heart of our approach is a high-level feature aggregation module that augments sparsely connected atrous convolution with dense local and layer-wise connections to avoid gridding artifacts. Besides, we employ a novel feature pyramid augmentation and semantic refinement unit to generate low- and mid-level features that are mixed with high-level features at the decoder. We extensively evaluate our proposed approach on the large-scale Cityscapes and ADE2K benchmarks. Our approach surpasses many latest models on both datasets, achieving mean intersection-over-union (mIoU) scores of 80.5% and 44.0% on Cityscapes and ADE20K, respectively.'
publication: '*IEEE Access*'
---
