# scRNAseq Data Browser
This repository hosts an R Shiny application designed for exploring single-cell RNA sequencing (scRNAseq) data related to three conditions. The application provides an interactive interface for visualizing and analyzing gene expression patterns across various datasets, enabling users to examine cluster-specific markers, compare different sample conditions, and visualize gene expression distributions.

<div style="display: flex; justify-content: space-around;">
  <img src="Pics/Pic 1.PNG" alt="Overall 1 Overview" width="100%">
</div>

<div style="display: flex; justify-content: space-around;">
  <img src="Pics/Pic 2.PNG" alt="Overall 2 Overview" width="100%">
</div>

# Features
**Dataset Selection**: Choose from multiple datasets, including:
1. Sample collection datasets 
2. Condition-based comparisons 
**Gene Expression Visualization**: Visualize gene expression patterns using:
1. Cluster and condition-based differential gene expression
2. UMAP plots to observe clustering patterns
**Dynamic Data Table**: Access and interact with data tables showing differentially expressed genes, which can be sorted, filtered, and searched.

# Usage
1. **Select Dataset**: Use the sidebar to select a dataset. Each option corresponds to a specific sample or condition-based dataset for Down Syndrome analysis.
2. **Explore Gene Expression**: Visualize gene expression across clusters or sample conditions. Interactive plots allow you to investigate specific genes of interest.
3. **Analyze Differential Expression**: Browse tables of differentially expressed genes, and use sorting or filtering options to focus on specific markers or conditions.

The app.R file contains an example R file for creating a similar R shiny app. The exact code used for creating this dashboard can supplied upon request (due to data privacy). 
