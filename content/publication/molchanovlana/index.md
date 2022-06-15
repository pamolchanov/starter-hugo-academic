---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'LANA: Latency Aware Network Acceleration'
subtitle: ''
summary: ''
authors:
- Pavlo Molchanov
- Jimmy Hall
- Hongxu Yin
- Jan Kautz
- Nicolo Fusi
- Arash Vahdat
tags: []
categories: []
date: 2021-07-12
lastmod: 2022-06-06T16:13:56-07:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: true

url_pdf: 'https://arxiv.org/pdf/2107.10624.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publication: In *Arxiv*
publication_short: In *Arxiv*
publishDate: '2022-06-06T23:13:56.484573Z'
publication_types:
- '2'
abstract: 'We introduce latency-aware network acceleration (LANA)–an approach that builds on neural architecture search techniques and teacher-student distillation to accelerate neural networks. LANA consists of two phases: in the first phase, it trains many alternative operations for every layer of the teacher network using layer-wise feature map distillation. In the second phase, it solves the combinatorial selection of efficient operations using a novel constrained integer linear optimization (ILP) approach. ILP brings unique properties as it (i) performs NAS within a few seconds to minutes, (ii) easily satisfies budget constraints, (iii) works on the layer-granularity, (iv) supports a huge search space $O(10^{100})$, surpassing prior search approaches in efficacy and efficiency.

In extensive experiments, we show that LANA yields efficient and accurate models constrained by a target latency budget, while being significantly faster than other techniques. We analyze three popular network architectures: EfficientNetV1, EfficientNetV2 and ResNeST, and achieve up to $3.0\%$ accuracy improvement for all models when compressing larger models to the latency level of smaller models. LANA achieves significant speed-ups (up to 5$\times$) with minor to no accuracy drop on GPU and CPU.'
publication: ''
---
