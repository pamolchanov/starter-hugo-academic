---
title: 'DoRA: Weight-Decomposed Low-Rank Adaptation'
#https://ezgif.com/apng-maker 

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
   - Shih-Yang Liu
   - Chien-Yi Wang
   - Hongxu Yin
   - Pavlo Molchanov
   - Yu-Chiang Frank Wang
   - Kwang-Ting Cheng
   - Min-Hung Chen


date: '2024-05-07'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-04-07T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: ICML 2024
publication_short: ICML 2024

abstract:  ''

# Summary. An optional shortened abstract.
summary: PEFT technique for efficient LLM/VLM adaptation. Significantly better than LoRA, supported in HF.

tags: 
  - Arxiv
  - machine learning

# Display this page in the Featured widget?
featured: true

abstract:  '![Teaser](dora_details.png) DoRA decomposes the pre-trained weight into two components, magnitude and direction, for fine-tuning, specifically employing LoRA for directional updates to efficiently minimize the number of trainable parameters. By employing DoRA, we enhance both the learning capacity and training stability of LoRA while avoiding any additional inference overhead. DoRA consistently outperforms LoRA on fine-tuning LLaMA, LLaVA, and VL-BART on various downstream tasks, such as commonsense reasoning, visual instruction tuning, and image/video-text understanding. 

Resources:
[Jeremy Howard - general introduction](https://twitter.com/jeremyphoward/status/1782575220051915175)
[Sebastian Raschka - QDoRA](https://twitter.com/rasbt/status/1758502685995589698)
'

#![HAT](hierarchial_attn.png)
# Custom links (uncomment lines below)
# Custom links (uncomment lines below)
links:
 - name: ICML2024 (Oral)
  url: https://icml.cc
 - name: Overview
  url: https://twitter.com/jeremyphoward/status/1782575220051915175
 - name: QDoRA
  url: https://twitter.com/rasbt/status/1758502685995589698


url_pdf: 'https://arxiv.org/abs/2402.09353'
url_code: 'https://github.com/NVlabs/DoRA'
url_dataset: ''
url_poster: ''
url_project: 'https://nbasyl.github.io/DoRA-project-page/'
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=m7KQdGSr0Dg'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'DoRA'
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
