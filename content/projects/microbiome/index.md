---
title: "A novel statistical approach for handling zeros in microbiome data"
subtitle: ""
date: 2022-08-15T17:10:20-07:00
authors:
  - juxin
draft: false
summary: |
  In this project, students will tackle the problem of handling zeros in
  sequencing data to try to overcome limitations in modern sequencing
  technologies.
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

## Project Leader
  * [Juxin Liu](/authors/juxin/), University of Saskatchewan

## Problem Statement
Due to the limitations of modern sequencing technologies (e.g., 16S rRNA
sequencing), the sequencing data are compositional, high dimensional,
over-dispersed, and zero-inflated. There has been an extensive amount of work on
how to tackle those challenges. This project focuses on how to handle zeros. The
importance of handling zeros cannot be overstated because almost all different
types of downstream analyses (e.g., network analysis) rely on the quality of
imputed data.

To our best knowledge, none of the existing zero-imputation methods make use of
the phylogenetic distances. The project aims to fill this gap in the literature.
We will first identify the sources of zeros, i.e., biological zeros or sampling
zeros. We will only impute sampling zeros by borrowing information from the taxa
that are closest in the phylogenetic tree.


### Details
  * **Expected team size**: 2
  * **Student Experience Level**: Advanced: students who have taken multiple upper-level mathematics courses

##### Prerequisites
  * Probability
  * Applied regression analysis
  * Computational statistics

##### Skills
  * R programming
