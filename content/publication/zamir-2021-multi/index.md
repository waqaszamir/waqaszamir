---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Multi-Stage Progressive Image Restoration
# Summary. An optional shortened abstract.
summary: <span style="font-size:120%;color:#117A65">**CVPR 2021**</span> <br>  A multi-stage architecture that progressively learns restoration functions for the degraded inputs, thereby breaking down the overall recovery process into more manageable steps.
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
date: '2021-01-01'
lastmod: 2022-04-07T13:06:37+04:00
featured: true
draft: false

# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://arxiv.org/abs/2102.02808
- name: Supplementary
  url: https://drive.google.com/file/d/1mbfljawUuFUQN9V5g0Rmw1UdauJdckCu/view?usp=sharing
- name: Video
  url: https://www.youtube.com/watch?v=0SMTPiLw5Vw
- name: Slides
  url: https://drive.google.com/file/d/1-L43wj-VTppkrR9AL6cPBJI2RJi3Hc_z/view?usp=sharing


url_pdf: ''
url_code: 'https://github.com/swz30/MPRNet'
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
publishDate: '2022-04-07T09:06:37.554268Z'
publication_types:
- '1'
abstract: 'Image restoration tasks demand a complex balance between spatial details and high-level contextualized information while recovering images. In this paper, we propose a novel synergistic design that can optimally balance these competing goals. Our main proposal is a multi-stage architecture, that progressively learns restoration functions for the degraded inputs, thereby breaking down the overall recovery process into more manageable steps. Specifically, our model first learns the contextualized features using encoder-decoder architectures and later combines them with a high-resolution branch that retains local information. At each stage, we introduce a novel per-pixel adaptive design that leverages in-situ supervised attention to reweight the local features. A key ingredient in such a multi-stage architecture is the information exchange between different stages. To this end, we propose a two-faceted approach where the information is not only exchanged sequentially from early to late stages, but lateral connections between feature processing blocks also exist to avoid any loss of information. The resulting tightly interlinked multi-stage architecture, named as MPRNet, delivers strong performance gains on ten datasets across a range of tasks including image deraining, deblurring, and denoising. For example, on the Rain100L, GoPro and DND datasets, we obtain PSNR gains of 4 dB, 0.81 dB and 0.21 dB, respectively, compared to the state-of-the-art.'
publication: '*IEEE/CVF Computer Vision and Pattern Recognition (CVPR)*'
---
