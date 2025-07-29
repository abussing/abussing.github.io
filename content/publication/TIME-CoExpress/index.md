---
title: "Time-coexpress: temporal trajectory modeling of dynamic gene co-expression patterns using single-cell transcriptomics data"
authors:
- Shuyi Yang
- admin
- Giampiero Marra
- et al.
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
# date: "2015-09-01T00:00:00Z"
doi: "10.1186/s12859-025-06218-w"


tags:
  - published

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*BMC Bioinformatics, 26*, 199"
publication_short: ""

abstract: The rapid advancement of single-cell RNA sequencing (scRNAseq) technology provides high-resolution views of transcriptomic activity within individual cells. Most routine analyses of scRNAseq data focus on individual genes; however, the one-gene-at-a-time analysis is likely to miss meaningful genetic interactions. Gene co-expression analysis addresses this limitation by identifying coordinated changes in gene expression in response to cellular conditions, such as developmental or temporal trajectories. Existing approaches to gene co-expression analysis often assume restrictive linear relationships. However, gene co-expression can change in complex, non-linear ways, which suggests the need for more flexible and accurate methods. We propose a copula-based framework, TIME-CoExpress, with proper data driven smoothing functions to model non-linear changes in gene co-expression along cellular temporal trajectories. Our method provides the flexibility to incorporate characteristics commonly observed in scRNAseq data, such as over-dispersion and zero-inflation, into the modeling framework. In addition to modeling gene co-expression, TIME-CoExpress captures dynamic changes in gene-level zero-inflation rates and mean expression levels, providing a more comprehensive analysis of scRNAseq data. Through a series of simulation analyses, we evaluated the performance of the proposed approach. We further demonstrated its implementation using a scRNAseq dataset and identified differentially co-expressed gene pairs along the cellular temporal trajectory during pituitary embryonic development, comparing Nxn−/ and wild-type mice. The proposed framework enables flexible and robust identification of dynamic, non-linear changes in gene co-expression, zero-inflation rates, and mean expression levels along temporal trajectories in scRNAseq data. Detecting these changes provides deeper insights into the biological processes and offers a better understanding of gene regulation throughout cellular development.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Source Themes
featured: false

# links:
# - name: ""
# url: ""
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
slides: ""
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->