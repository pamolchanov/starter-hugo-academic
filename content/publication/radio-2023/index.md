---
title: 'VILA: On Pre-training for Visual Language Models'
#https://ezgif.com/apng-maker 

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
   - Mike Ranzinger 
   - Greg Heinrich
   - Jan Kautz
   - Pavlo Molchanov

date: '2023-12-08'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-08T00:00:00Z'

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
summary: Best vision foundation model obtained via multiple model distillation like CLIP, DINOv2, SAM.

tags: 
  - Arxiv
  - machine learning

# Display this page in the Featured widget?
featured: true


abstract:  '![Teaser](am_radio_details.png) What is the best vision backbone for VLM?  We saw that various backbones perform differently at specific tasks. You should use them all!
We study on how to distill large vision models together to beat them. Large improvements in LLaVa-1.5. Main findings:  
(1) Distillation helps with any number of teachers, we use: CLIP, DINOv2, SAM; 
(2) Distilling feature maps is very important; (3) there are multiple challenges in image resolution, different batch-size and parallelization with multiple teachers.
(4) we can beat all teachers if use a strong ViT backbone; 
(5) analysis on using efficient vision backbones showed - many are tuned too much for ImageNet and dont scale to infinite data; 
(6) We propose a new architecture (E-RADIO), that dominates latency-acc and is 10x faster.
(7) SAM is not good if used out of the box, gives great edges but poor description of objects; 
(8) DINOv2 performs much better in VLM tasks; (9) our model requires only 2-5\% of data with no labels comp to CLIP. 
'


#![HAT](hierarchial_attn.png)
# Custom links (uncomment lines below)
# links:
#  - name: CVPR2023 Highlight
#    url: https://cvpr2023.thecvf.com

url_pdf: 'https://arxiv.org/abs/2312.06709'
url_code: 'https://github.com/NVlabs/RADIO'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'AMRADIO'
  focal_point: ''
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

links:
 - name: CVPR2024
   url: https://cvpr.thecvf.com

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
