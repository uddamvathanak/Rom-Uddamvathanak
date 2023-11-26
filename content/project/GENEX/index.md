---
title: 'GENEX: Explainable Batch effect removal for Single-cell RNA Sequencing Data'
summary: 'Batch effect correction remains a major challenge in single-cell RNA-sequencing data integration despite the number of methods developed. Most existing methods are unable to fully deconvolute technical and biological variations. Here, we present GENEX that leverages a disentangling generative adversarial net-work to distinguish batch effects and technical variations from biological differences. Moreover, unlike most other batch correction methods, GENEX returns batch corrected gene expression values that pre-serve the original distribution and can be used for downstream analyses.  Additionally, GENEX incorpo-rates an explainable AI component to enable the identification of genes specifically associated with vari-ous covariates such as gender, disease state, and sequencing platform. We evaluated GENEX on both simulated and experimental data.  It outperformed other existing methods in terms of batch correction and biological signal preservation. On the simulated dataset, GENEX reliably recapitulated the ground truth batch-invariant gene expressions. It also identified differentially expressed genes more accurately compared to differential expression analysis using unintegrated data or integrated values returned by oth-er methods. On a peripheral blood mononuclear cell dataset, GENEX identified genes highly influenced by different sequencing platforms. Furthermore, applied to a COVID dataset, GENEX revealed cell type-specific gene signatures associated with disease severity.'
tags:
  - All
date: '2023-11-03T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: 'https://github.com/JinmiaoChenLab/GENEX'

# image:
#   caption: Photo by rawpixel on Unsplash
#   focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: 'https://github.com/JinmiaoChenLab/GENEX'
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---