**Differential Gene Expression Analysis using DESeq2 on Single-Cell RNA-Seq Data**


*Overview:*

This Jupyter notebook demonstrates how to perform differential gene expression analysis on single-cell RNA-seq data using the DESeq2 package in R. The workflow includes data preprocessing, performing DESeq2 analysis, and visualizing results with a heatmap.



DESeq2: https://bioconductor.org/packages/release/bioc/html/DESeq2.html


*Requirements:*

This analysis requires the following R libraries:

DESeq2 – Differential expression analysis

rJava – Required for Java-based R packages

openxlsx – For reading and writing Excel files

pheatmap – For generating heatmaps


You can install them in R using:

```
install.packages("openxlsx")
BiocManager::install("DESeq2")
install.packages("rJava")
install.packages("pheatmap")
```

*Workflow:*
1) Load Data: Load and preprocess raw count data and sample metadata.
2) DESeq2 Analysis: Perform differential expression analysis with DESeq2.
3) Heatmap Visualization: Generate a heatmap of the most variable genes.
