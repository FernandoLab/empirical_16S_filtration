## Influence of empirically derived filtering parameters, ASV, and OTU pipelines on assessing rumen microbial diversity
This repository documents the development of empirical filtration abundance and prevalence derived from ZymoBIOMICS Microbial Community DNA Standard run in 10 replicates on an illumna miseq. We then test these filtration parameters using three ASV/OTU calling algorithms on a rumen microbiome study. The V4 hypervaraible region of the 16S rRNA was amplified for all samples in this analysis. Raw sequencing fastq files can be found in NCBIs SRA archive under project number: PRJNA1082806.

The avo_master.Rmd file contains the analysis performed for this houses the analysis for the other files are the supplementary data from raw fastq processing necessary for analysis including ASV/OTU count data, sample metadata, ASV/OTU fasta files, and taxonomic classifications. This analysis was performed in R using R Studio. To run this analysis please clone this repository to a directory of your choice, and then in the avo_master.Rmd be sure when you begin to reset your working directory in R/Rstudio: setwd("/path/to/empirical_16S_filtration/"). 

### References:
R Core Team (2021). R: A language and environment for statistical
computing. R Foundation for Statistical Computing, Vienna, Austria.
URL https://www.R-project.org/.
