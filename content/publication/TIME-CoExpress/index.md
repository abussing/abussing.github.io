---
title: "TIME-CoExpress: Temporal Trajectory Modeling of Dynamic Gene Co-expression Patterns Using Single-Cell Transcriptomics Data"
authors:
- Shuyi Yang
- admin
- Giampiero Marra
- Michelle L. Brinkmeier
- Sally A. Camper
- Shannon W. Davis
- Yen-Yi Ho
author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2026-05-01T00:00:00Z"
doi: ""

share: false

tags:
  - published


# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*BMC Bioinformatics (accepted)*"
publication_short: ""

abstract: The rapid advancements of single-cell RNA sequencing (scRNAseq) technology provide high-resolution views of transcriptomic activity within a single cell. Most routine analyses of scRNAseq data focus on individual genes; however, the one-gene-at-a-time analysis is likely to miss meaningful genetic interactions. Gene co-expression analysis addresses this issue by identifying coordinated gene expression changes in response to cellular conditions, such as developmental or temporal trajectory. Identifying differential co-expression gene combinations along the cell temporal trajectory using scRNAseq data can provide deeper insight into the biological processes. Existing approaches for gene co-expression analysis assume a restrictive linear change of gene co-expression. In this paper, we propose a copula-based approach with proper data-driven smoothing functions to model non-linear gene co-expression changes along cellular temporal trajectories. Our proposed approach provides flexibility to incorporate characteristics such as over-dispersion and zero-inflation rate observed in scRNAseq data into the modeling framework. We conducted a series of simulation analyses to evaluate the performance of the proposed algorithm. We demonstrate the implementation of the proposed algorithm using a scRNAseq dataset and identify differential co-expression gene pairs along cell temporal trajectory in pituitary embryonic development comparing Nxn - / - mutated versus wild-type mice.

# Summary. An optional shortened abstract.
# summary: Zero-inflated bivariate Gaussian copula model with negative binomial marginals. Marginal, zero-inflation, and copula association parameters are made functions of covariates and random effects are incorporated to account for cells from multiple patients. 

# tags:
# - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

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
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
