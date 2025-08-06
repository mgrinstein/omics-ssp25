# Transcriptomic Data Analysis for NASA OSD-599 Dataset

## Study Description

This analysis uses data from the NASA study **OSD-599 Version 4: Transcriptomic Effects on the Mouse Heart Following 30 Days on the International Space Station (ISS)**, available at [NASA OSDR Repository](https://osdr.nasa.gov/bio/repo/data/studies/OSD-599). It aims to study the effects of microgravity on the heart-brain axis by exploring upregulated and downregulated genes, and performing Gene Set Enrichment Analysis (GSEA) to connect them to corresponding relevant biological pathways.


## Analysis Overview

- Load and clean the dataset  
- Filter genes based on adjusted p-value (≤ 0.05)  
- Identify and visualise the top 10 upregulated and downregulated genes by log2 fold change  
- Examine selected genes of particular interest
- Perform Gene Set Enrichment Analysis using the `GO_Biological_Process_2021` dataset

## Acknowledgements

Chen EY, Tan CM, Kou Y, Duan Q, Wang Z, Meirelles GV, Clark NR, Ma'ayan A.  
[Enrichr: interactive and collaborative HTML5 gene list enrichment analysis tool. BMC Bioinformatics. 2013; 128(14)](https://www.ncbi.nlm.nih.gov/pubmed/23586463)
