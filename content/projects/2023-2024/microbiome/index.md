---
title: "A novel statistical method for handling zeros in microbiome data"
subtitle: ""
date: 2023-10-15T17:10:20-07:00
authors:
  - juxin
draft: false
summary: |
  In this project, students will tackle the problem of handling zeros in
  sequencing data to try to overcome limitations in modern sequencing
  technologies.
url_code: ""
url_pdf: "/projects/2023-2024/microbiome/microbiome-report.pdf"
url_poster: "microbiome-poster.pdf"
url_video: ""

tags:
  - '2023-2024'
---

## Project Leader
  * [Juxin Liu](/authors/juxin/), University of Saskatchewan

## Problem Statement
Modern sequencing technologies, such as 16S rRNA sequencing, provide a valuable
approach to large-scale profiling of microbial communities. However, the
sequencing data are compositional, over-dispersed, and zero-inflated due to the
limitations of the sequencing technologies. There has been an extensive amount
of work on how to tackle these challenges. This project focuses on how to handle
zeros. The importance of handling zeros cannot be overstated because almost all
different types of downstream analyses, such as network analysis, rely on the
quality of imputed data.

To our knowledge, none of the existing zero-imputation methods use phylogenetic
distances. The proposed project aims to fill this gap in the literature. We will
first identify the sources of zeros, i.e., biological zeros or sampling zeros.
We will only impute sampling zeros by borrowing information from the taxa that
are phylogenetically close.

### Details
  * **Expected team size**: 2
  * **Student Experience Level**: Advanced: students who have taken multiple upper-level mathematics courses

##### Prerequisites
Where course numbers are give, students should look for the closest equivalent
course given at their home institution

  * [STAT 241 (Probability Theory)](https://catalogue.usask.ca/STAT-241)
  * [STAT 242 (Statistical Theory and
    Methodology)](https://catalogue.usask.ca/STAT-242)
  * [STAT 344 (Elementary Statistical
    Concepts)](https://catalogue.usask.ca/STAT-244)

##### Skills
  * R programming
