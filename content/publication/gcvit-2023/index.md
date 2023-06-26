---
title: 'Global context vision transformers'
#https://ezgif.com/apng-maker 

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
   - A. Hatamizadeh
   - H. Yin
   - J. Kautz
   - P. Molchanov

date: '2023-01-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-01-10T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Machine Learning 2023*
publication_short: In *ICML 2023*

abstract:  'We propose global context vision transformer (GC ViT), a novel architecture that enhances parameter and compute utilization for computer vision. Our method leverages global context self-attention modules, joint with standard local self-attention, to effectively and efficiently model both long and short-range spatial interactions, without the need for expensive operations such as computing attention masks or shifting local windows. In addition, we address the lack of the inductive bias in ViTs, and propose to leverage a modified fused inverted residual blocks in our architecture. Our proposed GC ViT achieves state-of-the-art results across image classification, object detection and semantic segmentation tasks. On ImageNet-1K dataset for classification, the variants of GC ViT with 51M, 90M and 201M parameters achieve 84.3%, 85.0% and 85.7% Top-1 accuracy, respectively, at 224 image resolution and without any pre-training, hence surpassing comparably-sized prior art such as CNN-based ConvNeXt and ViT-based MaxViT and Swin Transformer by a large margin. Pre-trained GC ViT backbones in downstream tasks of object detection, instance segmentation, and semantic segmentation using MS COCO and ADE20K datasets outperform prior work consistently. Specifically, GC ViT with a 4-scale DINO detection head achieves a box AP of 58.3 on MS COCO dataset.'

# Summary. An optional shortened abstract.
summary: New vision transformer architecture optimized for number of parameters and FLOPs. 

tags: 
  - icml2023
  - machine learning

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
 - name: ICML2023
   url: https://icml.cc

url_pdf: 'https://arxiv.org/pdf/2206.09959.pdf'
url_code: 'https://github.com/NVlabs/GCVit'
url_dataset: ''
url_poster: ''
url_project: 'https://github.com/NVlabs/GCVit'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'GCViT'
  focal_point: ''
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [model_compression]


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
