---
title: 'Do gradient inversion attacks make federated learning unsafe?'
#https://ezgif.com/apng-maker 

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
   - A. Hatamizadeh
   - H. Yin
   - P. Molchanov
   - A. Myronenko
   - L. Wenqi
   - and others


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
publication: IEEE Transactions on Medical Imaging
publication_short: In *TMI 2022*

abstract:  'Federated learning (FL) allows the collaborative training of AI models without needing to share raw data. This capability makes it especially interesting for healthcare applications where patient and data privacy is of utmost concern. However, recent works on the inversion of deep neural networks from model gradients raised concerns about the security of FL in preventing the leakage of training data. In this work, we show that these attacks presented in the literature are impractical in real FL use-cases and provide a new baseline attack that works for more realistic scenarios where the clients' training involves updating the Batch Normalization (BN) statistics. Furthermore, we present new ways to measure and visualize potential data leakage in FL. Our work is a step towards establishing reproducible methods of measuring data leakage in FL and could help determine the optimal tradeoffs between privacy-preserving techniques, such as differential privacy, and model accuracy based on quantifiable metrics.'

# Summary. An optional shortened abstract.
summary:  We provide a new baseline attack that works for realistic scenarios in the medical federated learning where the clients' training involves updating the Batch Normalization (BN) statistics.

tags: 
  - machine learning

# Display this page in the Featured widget?
featured: false


url_pdf: ''
url_code: 'https://github.com/NVIDIA/NVFlare/tree/dev/research/quantifying-data-leakage'
url_dataset: ''
url_poster: ''
url_project: 'https://arxiv.org/abs/2202.06924'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'LANA'
#   focal_point: ''
#   preview_only: true

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
