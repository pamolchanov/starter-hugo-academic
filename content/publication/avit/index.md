---
title: 'AViT: Adaptive Tokens for Efficient Vision Transformer'
#https://ezgif.com/apng-maker 

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
   - H. Yin
   - A. Vahdat
   - J. Alvarez
   - A. Mallya
   - J. Kautz
   - P. Molchanov

date: '2022-06-11'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-06-17T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE/CVF Conference on Computer Vision and Pattern Recognition*
publication_short: In *CVPR 2022*

abstract: We present A-ViT, a method to enable adaptive token computation for vision transformers. We augment the vision transformer block with adaptive halting module that computes a halting probability per token. The module reuses the parameters of existing blocks and it borrows a single neuron from the last dense layer in each block to compute the halting probability, imposing no extra parameters or computations. A token is discarded once reaching the halting condition. Via adaptively halting tokens, we perform dense compute only on the active tokens deemed informative for the task. As a result, successive blocks in vision transformers gradually receive less tokens, leading to faster inference. Learnt token halting vary across images, yet align surprisingly well with image semantics (see examples above and more in paper). This results in immediate, out-of-the-box inference speedup on off-the-shelf computational platform.

# Summary. An optional shortened abstract.
summary: Transformer with adaptive inference where simpler images are classified faster. Tokens are automatically stopped at various depth once become irrelevant. Learned via differentiable loss inspired by ACT.

tags: 
  - cvpr2022
  - computer vision
  - machine learning

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
 - name: CVPR2022 (Oral)
   url: https://cvpr2022.thecvf.com

url_pdf: 'https://arxiv.org/pdf/2112.07658.pdf'
url_code: 'https://a-vit.github.io'
url_dataset: ''
url_poster: ''
url_project: 'https://a-vit.github.io'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'AVit'
  focal_point: ''
  preview_only: false

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
