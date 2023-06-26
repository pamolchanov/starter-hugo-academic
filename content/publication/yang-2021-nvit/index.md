---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Global Vision Transformer Pruning with Hessian-Aware Saliency'
subtitle: ''
summary: ''
authors:
- H. Yang
- H. Yin
- M. Shen
- P. Molchanov
- H. Li
- J. Kautz
tags: []
categories: []
date: '2021-01-01'
lastmod: 2022-06-06T16:13:55-07:00
draft: false

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
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE/CVF Conference on Computer Vision and Pattern Recognition*
publication_short: In *CVPR 2023*

abstract:  'Transformers yield state-of-the-art results across many tasks. However, their heuristically designed architecture impose huge computational costs during inference. This work aims on challenging the common design philosophy of the Vision Transformer (ViT) model with uniform dimension across all the stacked blocks in a model stage, where we redistribute the parameters both across transformer blocks and between different structures within the block via the first systematic attempt on global structural pruning. Dealing with diverse ViT structural components, we derive a novel Hessian-based structural pruning criteria comparable across all layers and structures, with latency-aware regularization for direct latency reduction. Performing iterative pruning on the DeiT-Base model leads to a new architecture family called NViT (Novel ViT), with a novel parameter redistribution that utilizes parameters more efficiently. On ImageNet-1K, NViT-Base achieves a 2.6x FLOPs reduction, 5.1x parameter reduction, and 1.9x run-time speedup over the DeiT-Base model in a near lossless manner. Smaller NViT variants achieve more than 1% accuracy gain at the same throughput of the DeiT Small/Tiny variants, as well as a lossless 3.3x parameter reduction over the SWIN-Small model. These results outperform prior art by a large margin. Further analysis is provided on the parameter redistribution insight of NViT, where we show the high prunability of ViT models, distinct sensitivity within ViT block, and unique parameter distribution trend across stacked ViT blocks. Our insights provide viability for a simple yet effective parameter redistribution rule towards more efficient ViTs for off-the-shelf performance boost.'

# Summary. An optional shortened abstract.
summary: Global pruning of vision transformer networks. New parameter redistribution rule for ViT. 2x latency reduction with minor acucracy loss. More than 1.4% accuracy gain when pruned towards smaller model.

tags: 
  - CVPR 2023
  - machine learning

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
 - name: CVPR2023
   url: https://cvpr2023.thecvf.com

url_pdf: 'https://arxiv.org/pdf/2110.04869.pdf'
url_code: 'https://github.com/NVlabs/NViT'
url_dataset: ''
url_poster: ''
url_project: 'https://cvpr2023.thecvf.com/virtual/2023/poster/22150'
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/0D8O7yBw4h4'
---
