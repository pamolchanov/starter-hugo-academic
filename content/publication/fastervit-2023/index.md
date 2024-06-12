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
summary: Vision transformer architecture with new hierarchical attention optimized for throughput and high-resolution images.

tags: 
  - Arxiv
  - Machine Learning

# Display this page in the Featured widget?
featured: true

abstract:  '![Teaser](graph.png) We design a new family of hybrid CNN-ViT neural networks, named FasterViT, with a focus on high image throughput for computer vision (CV) applications. FasterViT combines the benefits of fast local representation learning in CNNs and global modeling properties in ViT. Our newly introduced Hierarchical Attention (HAT) approach decomposes global self-attention with quadratic complexity into a multi-level attention with reduced computational costs. We benefit from efficient window-based self-attention. Each window has access to dedicated carrier tokens that participate in local and global representation learning. At a high level, global self-attentions enable efficient cross-window communication at lower costs. FasterViT achieves a SOTA Pareto-front in terms of accuracy vs. image throughput. We have extensively validated its effectiveness on various CV tasks including classification, object detection, and segmentation. We also show that HAT can be used as a plug-and-play module for existing networks and enhance them. We further demonstrate significantly faster and more accurate performance than competitive counterparts for high-resolution images. Code is available at https://github.com/NVlabs/FasterViT.

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

links:
 - name: ICLR2024
   url: https://iclr.cc

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
