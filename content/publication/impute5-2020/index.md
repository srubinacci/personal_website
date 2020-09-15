---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Genotype imputation using the Positional Burrows Wheeler Transform"
authors: [Simone Rubinacci, Olivier Delaneau, Jonathan Marchini]
date: 2019-10-14T00:00:00+00:00
doi: "10.1101/797944"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-14T14:25:59+03:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Genotype imputation using the Positional Burrows Wheeler Transform"
publication_short: ""

abstract: "Genotype imputation is the process of predicting unobserved genotypes in a sample of individuals using a reference panel of haplotypes. In the last 10 years reference panels have increased in size by more than 100 fold. Increasing reference panel size improves accuracy of markers with low minor allele frequencies but poses ever increasing computational challenges for imputation methods.

Here we present IMPUTE5, a genotype imputation method that can scale to reference panels with millions of samples. This method continues to refine the observation made in the IMPUTE2 method, that accuracy is optimized via use of a custom subset of haplotypes when imputing each individual. It achieves fast, accurate, and memory-efficient imputation by selecting haplotypes using the Positional Burrows Wheeler Transform (PBWT). By using the PBWT data structure at genotyped markers, IMPUTE5 identifies locally best matching haplotypes and long identical by state segments. The method then uses the selected haplotypes as conditioning states within the IMPUTE model.

Using the HRC reference panel, which has ~65,000 haplotypes, we show that IMPUTE5 is up to 30x faster than MINIMAC4 and up to 3x faster than BEAGLE5.1, and uses less memory than both these methods. Using simulated reference panels we show that IMPUTE5 scales sub-linearly with reference panel size. For example, keeping the number of imputed markers constant, increasing the reference panel size from 10,000 to 1 million haplotypes requires less than twice the computation time. As the reference panel increases in size IMPUTE5 is able to utilize a smaller number of reference haplotypes, thus reducing computational cost."

# Summary. An optional shortened abstract.
summary: "Genome-wide association studies (GWAS) typically use microarray technology to measure genotypes at several hundred thousand positions in the genome. However reference panels of genetic variation consist of haplotype data at >100 fold more positions in the genome. Genotype imputation makes genotype predictions at all the reference panel sites using the GWAS data. Reference panels are continuing to grow in size and this improves accuracy of the predictions, however methods need to be able to scale to increased size. We have developed a new version of the popular IMPUTE software than can handle referenece panels with millions of haplotypes, and has better performance than other published approaches. A notable property of the new method is that it scales sub-linearly with reference panel size. Keeping the number of imputed markers constant, a 100 fold increase in reference panel size requires less than twice the computation time."

tags: []
categories: [imputation]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://www.biorxiv.org/content/10.1101/797944v2.full.pdf"
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
  preview_only: true

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
