---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "GWAS in the cloud"
summary: "Learn how to use publicly available, open-source tools to perform a genome wide association analyses in a cloud computing environment."
authors: ["admin"]
tags: []
categories: []
date: 2020-04-23T15:10:55-04:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

# Overview
While at the Broad Institute, I have developed a number of platform-independent tools for genome-wide association analyses. These workflows and notebooks enable scientists with varying computational experience, from first time programmers to experienced coders, to perform GWA analyses in the cloud. The tools span a typical GWA analysis, from file conversion to association testing to summary figure generation. Written in the [Workflow Description Language (WDL)](https://openwdl.org/) with accompanying [Docker images](https://www.docker.com/), each workflow can be deployed through most major cloud providers, as well as locally or on a high performance compute cluster.  

## Try out the tools
---
To get started, head over to the featured workspace [on the Terra platform for a tutorial](https://app.terra.bio/#workspaces/amp-t2d-op/2019_ASHG_Reproducible_GWAS-V2). This workspace was developed and presented at the 2019 [American Society of Human Genetics](https://www.ashg.org/) meeting in Houston, TX. It is the product of a collaboration between [the Manning Lab](https://manning-lab.github.io/) and the [Data Sciences Platform](broadinstitute.org/data-sciences-platform) at the Broad Institute. Special thanks to Dr. Alisa Manning, Allie Hajian, and Geraldine Van der Auwera.

## Access the workflows
---
Each workflow is hosted on [the Dockstore platform](https://dockstore.org/) and available for download or export to multiple cloud computing infrustructures. Access each below:

- File conversion: the [vcfToGds workflow](https://dockstore.org/workflows/github.com/manning-lab/vcfToGds:master?tab=info) will convert variant call format (VCF) files to genomic data structure (GDS) format. GDS format is required to utilize the association testing and LD calculation workflows.  
- Association testing: the [genesis_GWAS workflow](https://dockstore.org/workflows/github.com/AnalysisCommons/genesis_wdl/genesis_GWAS:v1_4_1?tab=info) can be used for single- and multi-variant association testing using [the GENESIS software package](https://www.bioconductor.org/packages/release/bioc/html/GENESIS.html).  
- Linkage disequalibrium: the [LDGds workflow](https://dockstore.org/my-workflows/github.com/tmajaria/LDGds) is used to generate linkage disequalibrium measures from genotype data.
