---
title: "Non-Negative Infrared Patch-Image Model: Robust Target-Background Separation via Partial Sum Minimization of Singular Values"
authors:
- admin
- Yiquan Wu
- Yu Song
- Jun Guo
date: "2017-04-23T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-04-23T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Infrared Physics & Technology"
publication_short: ""

abstract: "To further enhance the small targets and suppress the heavy clutters simultaneously, a robust non-negative infrared patch-image model via partial sum minimization of singular values is proposed. First, the intrinsic reason behind the undesirable performance of the state-of-the-art infrared patch-image (IPI) model when facing extremely complex backgrounds is analyzed. We point out that it lies in the mismatching of IPI model’s implicit assumption of a large number of observations with the reality of deficient observations of strong edges. To fix this problem, instead of the nuclear norm, we adopt the partial sum of singular values to constrain the low-rank background patch-image, which could provide a more accurate background estimation and almost eliminate all the salient residuals in the decomposed target image. In addition, considering the fact that the infrared small target is always brighter than its adjacent background, we propose an additional non-negative constraint to the sparse target patch-image, which could not only wipe off more undesirable components ulteriorly but also accelerate the convergence rate. Finally, an algorithm based on inexact augmented Lagrange multiplier method is developed to solve the proposed model. A large number of experiments are conducted demonstrating that the proposed model has a significant improvement over the other nine competitive methods in terms of both clutter suppressing performance and convergence rate."

# Summary. An optional shortened abstract.
summary: 

tags:
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/abs/pii/S1350449516303723
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
