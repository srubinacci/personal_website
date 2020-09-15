---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Efficient phasing and imputation of low-coverage sequencing data using large reference panels"
authors: [Simone Rubinacci, Diogo Ribeiro, Robin Hofmeister, Olivier Delaneau]
date: 2020-04-14T00:00:00+00:00
doi: "10.1101/2020.04.14.040329"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-14T14:25:59+03:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Efficient phasing and imputation of low-coverage sequencing data using large reference panels"
publication_short: ""

abstract: "Low-coverage whole genome sequencing followed by imputation has been proposed as a cost-effective genotyping approach for disease and population genetics studies. However, its competitiveness against SNP arrays is undermined as current imputation methods are computationally expensive and unable to leverage large reference panels.

Here, we describe a method, GLIMPSE, for phasing and imputation of low-coverage sequencing datasets from modern reference panels. We demonstrate its remarkable performance across different coverages and human populations. It achieves imputation of a full genome for less than $1, outperforming existing methods by orders of magnitude, with an increased accuracy of more than 20% at rare variants. We also show that 1x coverage enables effective association studies and is better suited than dense SNP arrays to access the impact of rare variations. Overall, this study demonstrates the promising potential of low-coverage imputation and suggests a paradigm shift in the design of future genomic studies."

# Summary. An optional shortened abstract.
summary: "In this work, we address the challenge of genotype imputation and haplotype phasing of low-coverage sequencing datasets using a reference panel of haplotypes. To this aim, we propose a novel method, GLIMPSE (Genotype Likelihoods Imputation and PhaSing mEthod), that is designed for large-scale studies and reference panels, typically comprising thousands of genomes. We show the remarkable performance of GLIMPSE using low-coverage whole genome sequencing data for both European and African American populations, and we demonstrate that low-coverage sequencing can be confidently used in downstream analyses. We provide GLIMPSE as a part of an open source software suite that makes imputation for low-coverage sequencing data as convenient as for traditional SNP array platforms."

tags: [low-coverage, imputation, phasing]
categories: [imputation]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://www.biorxiv.org/content/10.1101/2020.04.14.040329v1.full.pdf"
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [internal-project]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
