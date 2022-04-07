---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Burst Image Restoration and Enhancement
subtitle: ''
# Summary. An optional shortened abstract.
summary: <span style="font-size:120%;color:#117A65">**CVPR 2022**</span>, <span style="font-size:120%;color:#D35400">**Oral**</span> <br> we develop a novel approach by solely focusing on the effective information exchange between burst frames, such that the degradations get filtered out while the actual scene details are preserved and enhanced.
authors:
- Akshay Dudhane
- admin
- Salman Khan
- Fahad Khan
- Ming-Hsuan Yang
tags: []
categories: []
date: '2022-01-01'
lastmod: 2022-04-07T13:06:37+04:00
featured: true
draft: false

# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://arxiv.org/abs/2110.03680
#- name: Supplementary
#  url: https://drive.google.com/file/d/1oKGON8vG4uDWMmZKqHeTMnFowhOubifK/view?usp=sharing
#- name: Colab Demo
#  url: https://colab.research.google.com/drive/1C2818h7KnjNv4R1sabe14_AYL7lWhmu6?usp=sharing
#- name: Web Demo
#  url: https://huggingface.co/spaces/swzamir/Restormer


url_pdf: ''
url_code: ''
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
publishDate: '2022-04-07T09:06:36.893512Z'
publication_types:
- '1'


abstract: 'Modern handheld devices can acquire burst image sequence in a quick succession. However, the individual acquired frames suffer from multiple degradations and are misaligned due to camera shake and object motions. The goal of Burst Image Restoration is to effectively combine complimentary cues across multiple burst frames to generate high-quality outputs. Towards this goal, we develop a novel approach by solely focusing on the effective information exchange between burst frames, such that the degradations get filtered out while the actual scene details are preserved and enhanced. Our central idea is to create a set of \emph{pseudo-burst} features that combine complimentary information from all the input burst frames to seamlessly exchange information. The pseudo-burst representations encode channel-wise features from the original burst images, thus making it easier for the model to learn distinctive information offered by multiple burst frames. However, the pseudo-burst cannot be successfully created unless the individual burst frames are properly aligned to discount inter-frame movements. Therefore, our approach initially extracts preprocessed features from each burst frame and matches them using an edge-boosting burst alignment module. The pseudo-burst features are then created and enriched using multi-scale contextual information. Our final step is to adaptively aggregate information from the pseudo-burst features to progressively increase resolution in multiple stages while merging the pseudo-burst features. In comparison to existing works that usually follow a late fusion scheme with single-stage upsampling, our approach performs favorably, delivering state of the art performance on burst super-resolution and low-light image enhancement tasks. Our codes and models will be released publicly.'

publication: '*IEEE/CVF Computer Vision and Pattern Recognition (CVPR)*'
---
