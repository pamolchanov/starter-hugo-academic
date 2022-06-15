---
title: 'Dreaming to Distill: Data-free Knowledge Transfer via DeepInversion'
#https://ezgif.com/apng-maker 

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - H. Yin
  - P. Molchanov
  - J. M. Alvarez
  - Z. Li
  - A. Mallya
  - D. Hoiem
  - N..Jha
  - J. Kautz

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2020-06-16T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-06-16T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE/CVF Conference on Computer Vision and Pattern Recognition*
publication_short: In *CVPR 2022*

abstract:  We introduce DeepInversion ![Teaser](deepinversion_teaser2.pdf), a new method for synthesizing images from the image distribution used to train a deep neural network. We invert a trained network (teacher) to synthesize class-conditional input images starting from random noise, without using any additional information on the training dataset. Keeping the teacher fixed, our method optimizes the input while regularizing the distribution of intermediate feature maps using information stored in the batch normalization layers of the teacher. Further, we improve the diversity of synthesized images using Adaptive DeepInversion, which maximizes the Jensen-Shannon divergence between the teacher and student network logits. The resulting synthesized images from networks trained on the CIFAR-10 and ImageNet datasets demonstrate high fidelity and degree of realism, and help enable a new breed of data-free applications – ones that do not require any real images or labeled data. We demonstrate the applicability of our proposed method to three tasks of immense practical importance – (i) data-free network pruning, (ii) data-free knowledge transfer, and (iii) data-free continual learning.

# Summary. An optional shortened abstract.
summary: Statistics stored in batch normalization layers contain information on training data. Via iterative optimization we recover images from train distribution and use for various applications. 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/1912.08795.pdf'
url_code: 'https://github.com/NVlabs/DeepInversion'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://www.youtube.com/watch?v=_oho5M8aNhY'
url_source: ''
url_video: 'https://www.youtube.com/watch?v=ddEtea4ntEU'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'DeepInversion'
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
#slides: example
---
