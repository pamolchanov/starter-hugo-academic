---
title: 'FasterViT: Fast Vision Transformers with Hierarchical Attention'
#https://ezgif.com/apng-maker 

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
   - A. Hatamizadeh
   - G. Heinrich
   - H. Yin
   - A. Tao
   - J. Alvarez
   - J. Kautz
   - "**P. Molchanov**"


date: '2023-07-07'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-07-07T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In arxiv
publication_short: In *Arxiv*

abstract:  ''

# Summary. An optional shortened abstract.
summary: Vision transformer architecture with new hierarchical attention optimezed for throughput and high resolution images.

tags: 
  - Arxiv
  - machine learning

# Display this page in the Featured widget?
featured: true


abstract:  '![Teaser](graph.png) We design a new family of hybrid CNN-ViT neural net- works, named FasterViT, with a focus on high image through- put for computer vision (CV) applications. FasterViT com- bines the benefits of fast local representation learning in CNNs and global modeling properties in ViT. Our newly introduced Hierarchical Attention (HAT) approach decom- poses global self-attention with quadratic complexity into a multi-level attention with reduced computational costs. We benefit from efficient window-based self-attention. Each window has access to dedicated carrier tokens that par- ticipate in local and global representation learning. At a high level, global self-attentions enable the efficient cross- window communication at lower costs. FasterViT achieves a SOTA Pareto-front in terms of accuracy vs. image through- put. We have extensively validated its effectiveness on various CV tasks including classification, object detection and segmentation. We also show that HAT can be used as a plug-and-play module for existing networks and en- hance them. We further demonstrate significantly faster and more accurate performance than competitive counter- parts for images with high resolution. Code is available at https://github.com/NVlabs/FasterViT.

New hierarchical attention that facilitates local and global information exchange in a computationally efficient manner. The proposed hierarchical attention is shown in the following figure:
![HAT](hierarchial_attn.png)
'


# Custom links (uncomment lines below)
# links:
#  - name: CVPR2023 Highlight
#    url: https://cvpr2023.thecvf.com

url_pdf: 'https://arxiv.org/pdf/2306.06189'
url_code: 'https://github.com/NVlabs/FasterViT'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'FasterViT'
  focal_point: ''
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
