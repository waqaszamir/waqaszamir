---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Striking the Right Balance with Uncertainty
subtitle: ''
summary: <span style="font-size:120%;color:#117A65">**CVPR 2019**</span>, <span style="font-size:120%;color:#D35400">**Oral**</span> <br>  A new framework for uncertainty based class imbalance learning.
authors:
- Salman Khan
- Munawar Hayat
- admin
- Jianbing Shen
- Ling Shao
tags: []
categories: []
date: '2019-02-02'
lastmod: 2022-04-07T13:06:38+04:00
featured: true
draft: false



# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://arxiv.org/abs/1901.07590


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
publishDate: '2022-04-07T09:06:38.547956Z'
publication_types:
- '1'
abstract: 'Learning unbiased models on imbalanced datasets is a significant challenge. Rare classes tend to get a concentrated representation in the classification space which hampers the generalization of learned boundaries to new test examples. In this paper, we demonstrate that the Bayesian uncertainty estimates directly correlate with the rarity of classes and the difficulty level of individual samples. Subsequently, we present a novel framework for uncertainty based class imbalance learning that follows two key insights. First, classification boundaries should be extended further away from a more uncertain (rare) class to avoid overfitting and enhance its generalization. Second, each sample should be modeled as a multi-variate Gaussian distribution with a mean vector and a covariance matrix defined by the samples uncertainty. The learned boundaries should respect not only the individual samples but also their distribution in the feature space. Our proposed approach efficiently utilizes sample and class uncertainty information to learn robust features and more generalizable classifiers. We systematically study the class imbalance problem and derive a novel loss formulation for max-margin learning based on Bayesian uncertainty measure. The proposed method shows significant performance improvements on six benchmark datasets for face verification, attribute prediction, digit/object classification and skin lesion detection.'
publication: '*IEEE/CVF Computer Vision and Pattern Recognition (CVPR)*'
---
