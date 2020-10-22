---
title: "Attention as Activation"
authors:
- admin
- Stefan Oehmcke
- Fabian Gieseke
- Yiquan Wu
- Kobus Barnard
date: "2020-07-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-07-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Activation functions and attention mechanisms are typically treated as having different purposes and have evolved differently. However, both concepts can be formulated as a non-linear gating function. Inspired by their similarity, we propose a novel type of activation units called attentional activation (ATAC) units as a unification of activation functions and attention mechanisms. In particular, we propose a local channel attention module for the simultaneous non-linear activation and element-wise feature refinement, which locally aggregates point-wise cross-channel feature contexts. By replacing the well-known rectified linear units by such ATAC units in convolutional networks, we can construct fully attentional networks that perform significantly better with a modest number of additional parameters. We conducted detailed ablation studies on the ATAC units using several host networks with varying network depths to empirically verify the effectiveness and efficiency of the units. Furthermore, we compared the performance of the ATAC units against existing activation functions as well as other attention mechanisms on the CIFAR-10, CIFAR-100, and ImageNet datasets. Our experimental results show that networks constructed with the proposed ATAC units generally yield performance gains over their competitors given a comparable number of parameters."

# Summary. An optional shortened abstract.
summary: Accepted by 25th International Conference on Pattern Recognition (ICPR 2020)

tags:
featured: false

links:
# - name: ""
#   url: ""    
url_pdf: https://arxiv.org/abs/2007.07729
url_code: 'https://github.com/YimianDai/open-atac'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---


