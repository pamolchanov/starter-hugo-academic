---
title: 'LANA: latency aware network acceleration'
#https://ezgif.com/apng-maker 

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
   - P. Molchanov
   - J. Hall
   - H. Yin
   - J. Kautz
   - N. Fusi
   - A. Vahdat


date: '2022-10-10'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-10-10T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE/CVF Conference on Computer Vision and Pattern Recognition*
publication_short: In *CVPR 2022*

abstract:  'Latency-aware network acceleration (LANA) – an approach that builds on neural architecture search techniques and teacher-student distillation to accelerate neural networks. LANA consists of two phases: in the first phase, it trains many alternative operations for every layer of the teacher network using layer-wise feature map distillation. In the second phase, it solves the combinatorial selection of efficient operations using a novel constrained integer linear optimization (ILP) approach. ILP brings unique properties as it (i) performs NAS within a few seconds to minutes, (ii) easily satisfies budget constraints, (iii) works on the layer-granularity, (iv) supports a huge search space 10^100, sur- passing prior search approaches in efficacy and efficiency. We show that LANA yields effi- cient and accurate models constrained by a target latency budget, while being significantly faster than other techniques. We analyze three popular network architectures: Efficient- NetV1, EfficientNetV2 and ResNeST, and achieve up to 3.0% accuracy improvement for all models when compressing larger models to the latency level of smaller models. LANA achieves significant speed-ups (up to 5ˆ) with minor to no accuracy drop on GPU and CPU. The code will be available soon.'

# Summary. An optional shortened abstract.
summary: Fast NAS-like techinue for trained model compression. Pretraines possible layer candidates via local distillation, does NAS via integer linear programming.

tags: 
  - eccv2022
  - machine learning

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
 - name: ECCV2022
   url: https://eccv2022.ecva.net

url_pdf: 'https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136720136.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/PxqjTxzskzQ'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'LANA'
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
