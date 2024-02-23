---
title: 'VILA: On Pre-training for Visual Language Models'
#https://ezgif.com/apng-maker 

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
   - Ji Lin
   - Hongxu Yin
   - Wei Ping
   - Yao Lu
   - Pavlo Molchanov
   - Andrew Tao 
   - Huizi Mao 
   - Jan Kautz
   - Mohammad Shoeybi
   - Song Han


date: '2023-12-07'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-07T00:00:00Z'

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
summary: Vision language foundation model. Multiple findings on how to train a better model.

tags: 
  - Arxiv
  - machine learning

# Display this page in the Featured widget?
featured: true


abstract:  '![Teaser](vila-danny.png) Findings: (1) after feature alignment, unfreeze LLM for pre-taining, this will improve in-context learning ; (2) interleaved pre-training data is beneficial, or text-only accuracy degrades by 17.2%; (3) Image-text pairs alone are not optimal, use MMC4; (4) re-blending text-only instruction data to image-text data during instruction fine-tuning not only remedies the degradation of text-only tasks, but also boosts VLM task accuracy. 
'

#![HAT](hierarchial_attn.png)
# Custom links (uncomment lines below)
# links:
#  - name: CVPR2023 Highlight
#    url: https://cvpr2023.thecvf.com

url_pdf: 'https://arxiv.org/abs/2312.07533'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'VILA'
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
