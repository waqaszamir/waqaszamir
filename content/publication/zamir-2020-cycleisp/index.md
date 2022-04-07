---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'CycleISP: Real Image Restoration via Improved Data Synthesis'
subtitle: ''
summary: <span style="font-size:120%;color:#117A65">**CVPR 2020**</span>, <span style="font-size:120%;color:#D35400">**Oral**</span> <br>  It is a framework that models camera imaging pipeline in forward and reverse directions and allows us to produce any number of realistic image pairs for denoising both in RAW and sRGB spaces.

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
date: '2020-01-01'
lastmod: 2022-04-07T13:06:38+04:00
featured: true
draft: false


# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://arxiv.org/abs/2003.07761
- name: Supplementary
  url: https://drive.google.com/file/d/1FHOPCrmgYcez2ZTI0-roKEbyeXJIulSJ/view?usp=sharing
- name: Video
  url: https://www.youtube.com/watch?v=41XKXY--7_E
- name: Slides
  url: https://drive.google.com/file/d/1KnmF0_yYrj4FzsMimLNfea84xgR7czlh/view?usp=sharing


url_pdf: ''
url_code: 'https://github.com/swz30/CycleISP'
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
publishDate: '2022-04-07T09:06:38.218582Z'
publication_types:
- '1'
abstract: 'The availability of large-scale datasets has helped unleash the true potential of deep convolutional neural networks (CNNs). However, for the single-image denoising problem, capturing a real dataset is an unacceptably expensive and cumbersome procedure. Consequently, image denoising algorithms are mostly developed and evaluated on synthetic data that is usually generated with a widespread assumption of additive white Gaussian noise (AWGN). While the CNNs achieve impressive results on these synthetic datasets, they do not perform well when applied on real camera images, as reported in recent benchmark datasets. This is mainly because the AWGN is not adequate for modeling the real camera noise which is signal-dependent and heavily transformed by the camera imaging pipeline. In this paper, we present a framework that models camera imaging pipeline in forward and reverse directions. It allows us to produce any number of realistic image pairs for denoising both in RAW and sRGB spaces. By training a new image denoising network on realistic synthetic data, we achieve the state-of-the-art performance on real camera benchmark datasets. The parameters in our model are ~5 times lesser than the previous best method for RAW denoising. Furthermore, we demonstrate that the proposed framework generalizes beyond image denoising problem e.g., for color matching in stereoscopic cinema.'
publication: '*IEEE/CVF Computer Vision and Pattern Recognition (CVPR)*'
---
