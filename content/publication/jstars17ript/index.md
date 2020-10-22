---
title: "Reweighted Infrared Patch-Tensor Model with Both Nonlocal and Local Priors for Single-Frame Small Target Detection"
authors:
- admin
- Yiquan Wu
date: "2017-05-23T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-05-23T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing"
publication_short: "JSTARS"

abstract: "Many state-of-the-art methods have been proposed for infrared small target detection. They work well on the images with homogeneous backgrounds and high-contrast targets. However, when facing highly heterogeneous backgrounds, they would not perform very well, mainly due to: 1) the existence of strong edges and other interfering components, 2) not utilizing the priors fully. Inspired by this, we propose a novel method to exploit both local and non-local priors simultaneously. Firstly, we employ a new infrared patch-tensor (IPT) model to represent the image and preserve its spatial correlations. Exploiting the target sparse prior and background non-local self-correlation prior, the target-background separation is modeled as a robust low-rank tensor recovery problem. Moreover, with the help of the structure tensor and reweighted idea, we design an entry-wise local-structure-adaptive and sparsity enhancing weight to replace the globally constant weighting parameter. The decomposition could be achieved via the element-wise reweighted higher-order robust principal component analysis with an additional convergence condition according to the practical situation of target detection. Extensive experiments demonstrate that our model outperforms the other state-of-the-arts, in particular for the images with very dim targets and heavy clutters. "

# Summary. An optional shortened abstract.
summary: "IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, 2017, 10(8): 3752-3767."

tags:
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/document/7932858
url_code: 'https://github.com/YimianDai/DENTIST'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
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
slides: example
---
