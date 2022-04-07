---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Low Light Image Enhancement via Global and Local Context Modeling'
subtitle: ''
summary: ''
authors:
- Aditya Arora
- Muhammad Haris
- admin 
- Munawar Hayat
- Fahad Shahbaz Khan
- Ling Shao
- Ming-Hsuan Yang
tags: []
categories: []
date: '2021-01-01'
lastmod: 2022-04-07T13:06:40+04:00
featured: false
draft: false


# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://arxiv.org/abs/2101.00850


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
publishDate: '2022-04-07T09:06:39.869731Z'
publication_types:
- '2'
abstract: 'Images captured under low-light conditions manifest poor visibility, lack contrast and color vividness. Compared to conventional approaches, deep convolutional neural networks (CNNs) perform well in enhancing images. However, being solely reliant on confined fixed primitives to model dependencies, existing data-driven deep models do not exploit the contexts at various spatial scales to address low-light image enhancement. These contexts can be crucial towards inferring several image enhancement tasks, e.g., local and global contrast, brightness and color corrections; which requires cues from both local and global spatial extent. To this end, we introduce a context-aware deep network for low-light image enhancement. First, it features a global context module that models spatial correlations to find complementary cues over full spatial domain. Second, it introduces a dense residual block that captures local context with a relatively large receptive field. We evaluate the proposed approach using three challenging datasets: MIT-Adobe FiveK, LoL, and SID. On all these datasets, our method performs favorably against the state-of-the-arts in terms of standard image fidelity metrics. In particular, compared to the best performing method on the MIT-Adobe FiveK dataset, our algorithm improves PSNR from 23.04 dB to 24.45 dB.'
publication: '*arXiv:2101.00850*'
---
