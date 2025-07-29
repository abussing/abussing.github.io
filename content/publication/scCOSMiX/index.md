---
title: "scCOSMiX: A Mixed-Effects Framework for Differential Coexpression and Transcriptional Interactions Modeling in Single-Cell RNA-Seq"
authors:
- admin
- Giampiero Marra
- Daping Fan
- Russell Shinohara
- Danni Tu
- Yen-Yi Ho
author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2025-09-01T00:00:00Z"
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
publication: "*Statistics in Medicine (accepted)*"
publication_short: ""

abstract: Advancements in single-cell RNA-sequencing (scRNA-seq) technologies generate a wealth of gene expression data that provide exciting opportunities for studying gene-gene interactions systematically at individual cell resolution. Genetic interactions within a cell are tightly regulated and often highly dynamic in response to internal cellular signals and external stimuli. Evidence of these dynamic interactions can often be observed in scRNA-seq data by examining conditional co-expression changes. Existing approaches for studying these dynamic interaction changes in scRNA-seq data do not address the multi-subject hierarchical design commonly considered in single-cell experiments. In this paper, we propose a MiXed-effects framework for differential COexpreSsion and transcriptional interaction modeling in Single-Cell RNA-seq (scCOSMiX) to account for the cell-cell correlation from the same individual. The proposed copula-based approach allows the zero-inflation, marginal, and association parameters to be modeled as functions of covariates with subject-level random effects, to enable analyses to be tailored to the data under consideration. A series of simulation analyses were conducted to evaluate and compare the performance of scCOSMiX to other existing approaches. We applied the proposed method to both droplet and plate-based scRNA-seq datasets GSE266919 and GSE108989 to illustrate its applicability across distinct scRNA-seq experimental protocols.

# # Summary. An optional shortened abstract.
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
