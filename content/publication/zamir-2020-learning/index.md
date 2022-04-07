---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Learning Enriched Features for Real Image Restoration and Enhancement
subtitle: ''
summary: <span style="font-size:120%;color:#117A65">**ECCV 2020**</span> <br> A novel feature extraction model that obtains a complementary set of features across multiple spatial scales, while maintaining the original high-resolution features to preserve precise spatial details.

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
date: '2020-02-02'
lastmod: 2022-04-07T13:06:38+04:00
featured: true
draft: false


# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://arxiv.org/abs/2003.06792
- name: Supplementary
  url: https://drive.google.com/file/d/1QIKp7h7Rd85odaS6bDoeDGXb0VLKo8I9/view?usp=sharing
- name: Video
  url: https://www.youtube.com/watch?v=6xSzRjAodv4
- name: Slides
  url: https://drive.google.com/file/d/1hnhqSrjqQQiYn7XPAGpFgMBTfBlb1QAy/view?usp=sharing
- name: Web Demo
  url: https://huggingface.co/spaces/keras-io/Enhance_Low_Light_Image



url_pdf: ''
url_code: 'https://github.com/swz30/MIRNet'
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
publishDate: '2022-04-07T09:06:37.886292Z'
publication_types:
- '1'
abstract: 'With the goal of recovering high-quality image content from its degraded version, image restoration enjoys numerous applications, such as in surveillance, computational photography, medical imaging, and remote sensing. Recently, convolutional neural networks (CNNs) have achieved dramatic improvements over conventional approaches for image restoration task. Existing CNN-based methods typically operate either on full-resolution or on progressively low-resolution representations. In the former case, spatially precise but contextually less robust results are achieved, while in the latter case, semantically reliable but spatially less accurate outputs are generated. In this paper, we present a novel architecture with the collective goals of maintaining spatially-precise high-resolution representations through the entire network, and receiving strong contextual information from the low-resolution representations. The core of our approach is a multi-scale residual block containing several key elements: (a) parallel multi-resolution convolution streams for extracting multi-scale features, (b) information exchange across the multi-resolution streams, (c) spatial and channel attention mechanisms for capturing contextual information, and (d) attention based multi-scale feature aggregation. In the nutshell, our approach learns an enriched set of features that combines contextual information from multiple scales, while simultaneously preserving the high-resolution spatial details. Extensive experiments on five real image benchmark datasets demonstrate that our method, named as MIRNet, achieves state-of-the-art results for a variety of image processing tasks, including image denoising, super-resolution and image enhancement.'

publication: '*IEEE/CVF European Conference on Computer Vision (ECCV)*'
---
