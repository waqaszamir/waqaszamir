---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Restormer: Efficient Transformer for High-Resolution Image Restoration'
subtitle: ''
# Summary. An optional shortened abstract.
summary: <span style="font-size:120%;color:#117A65">**CVPR 2022**</span>, <span style="font-size:120%;color:#D35400">**Oral**</span> <br> An encoder-decoder Transformer for multi-scale local-global representation learning. Restormer is computationally efficient to handle high-resolution images.

authors:
- admin
- Aditya Arora
- Salman Khan
- Munawar Hayat
- Fahad Shahbaz Khan
- Ming-Hsuan Yang
tags: []
categories: []
date: '2022-02-02'
lastmod: 2022-04-07T13:06:36+04:00
featured: true
draft: false

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://arxiv.org/abs/2111.09881
- name: Supplementary
  url: https://drive.google.com/file/d/1oKGON8vG4uDWMmZKqHeTMnFowhOubifK/view?usp=sharing
- name: Colab Demo
  url: https://colab.research.google.com/drive/1C2818h7KnjNv4R1sabe14_AYL7lWhmu6?usp=sharing
- name: Web Demo
  url: https://huggingface.co/spaces/swzamir/Restormer


url_pdf: ''
url_code: 'https://github.com/swz30/Restormer'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://drive.google.com/file/d/19wKhnQtr3mcD6IsLj0ZFSwCgIRKUkDQJ/view?usp=sharing'
url_source: ''
url_video: 'https://www.youtube.com/watch?v=3mqu6N4_0pY&t'



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
publishDate: '2022-04-07T09:06:36.560036Z'


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]


abstract: 'Since convolutional neural networks (CNNs) perform well at learning generalizable image priors from large-scale data, these models have been extensively applied to image restoration and related tasks. Recently, another class of neural architectures, Transformers, have shown significant performance gains on natural language and high-level vision tasks. While the Transformer model mitigates the shortcomings of CNNs (i.e., limited receptive field and inadaptability to input content), its computational complexity grows quadratically with the spatial resolution, therefore making it infeasible to apply to most image restoration tasks involving high-resolution images. In this work, we propose an efficient Transformer model by making several key designs in the building blocks (multi-head attention and feed-forward network) such that it can capture long-range pixel interactions, while still remaining applicable to large images. Our model, named Restoration Transformer (Restormer), achieves state-of-the-art results on several image restoration tasks, including image deraining, single-image motion deblurring, defocus deblurring (single-image and dual-pixel data), and image denoising (Gaussian grayscale/color denoising, and real image denoising).'

publication: '*IEEE/CVF Computer Vision and Pattern Recognition (CVPR)*'


---
