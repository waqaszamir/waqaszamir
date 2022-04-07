---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Synthesizing the Unseen for Zero-shot Object Detection'
subtitle: ''
summary: ''
authors:
- Nasir Hayat
- Munawar Hayat
- Shafin Rahman
- Salman Khan
- admin
- Fahad Shahbaz Khan
tags: []
categories: []
date: '2020-01-01'
lastmod: 2022-04-07T13:06:39+04:00
featured: false
draft: false

# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://arxiv.org/abs/2010.09425

url_pdf: ''
url_code: 'https://github.com/nasir6/zero_shot_detection'
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
publishDate: '2022-04-07T09:06:39.543070Z'
publication_types:
- '1'
abstract: 'The existing zero-shot detection approaches project visual features to the semantic domain for seen objects, hoping to map unseen objects to their corresponding semantics during inference. However, since the unseen objects are never visualized during training, the detection model is skewed towards seen content, thereby labeling unseen as background or a seen class. In this work, we propose to synthesize visual features for unseen classes, so that the model learns both seen and unseen objects in the visual domain. Consequently, the major challenge becomes, how to accurately synthesize unseen objects merely using their class semantics? Towards this ambitious goal, we propose a novel generative model that uses class-semantics to not only generate the features but also to discriminatively separate them. Further, using a unified model, we ensure the synthesized features have high diversity that represents the intra-class differences and variable localization precision in the detected bounding boxes. We test our approach on three object detection benchmarks, PASCAL VOC, MSCOCO, and ILSVRC detection, under both conventional and generalized settings, showing impressive gains over the state-of-the-art methods.'
publication: '*Asian Conference on Computer Vision (ACCV)*'
---
