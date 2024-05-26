# CRC_TCell_Analysis

## Description
This repository contains the code for analyzing colorectal cancer T-cell data using Seurat and ggplot2. The analysis includes visualization and comparison of different conditions and T-cell annotations.

## Project Structure
- `realdata_crc_tcells_.rds`: Real dataset of colorectal cancer T-cells.
- `sim_data.rds`: Simulated dataset for comparison.

## Analysis
The analysis is conducted using R and includes the following steps:

1. **Data Preprocessing**:
    - Load the data.
    - Modify metadata for consistency.

2. **Visualization**:
    - **UMAP Plots**:
        - UMAP colored by condition.
        - UMAP colored by T-cell type (CD4+/CD8+).
        - UMAP colored by annotation.
    - **Bar Plots**:
        - Stacked bar plot showing the proportion of annotation types.
        - Dodged bar plot showing the proportion of annotation types.

## Usage
1. Clone the repository:
   '''git clone https://github.com/your-username/CRC_TCell_Analysis.git'''
3. Open the R script in RStudio or any other R environment.
4. Make sure the required libraries are installed: 'install.packages(c("Seurat", "ggplot2", "dplyr"))'
5. Set the correct file paths for the datasets.
6. Run the script to perform the analysis and generate the plots.

## Results
The analysis generates the following plots:

UMAP-Condition.png: UMAP plot colored by condition.
UMAP-CD4-CD8.png: UMAP plot colored by T-cell type (CD4+/CD8+).
UMAP-Annotation.png: UMAP plot colored by annotation.
Proportion-Annotation-Types-Stack.png: Stacked bar plot of annotation type proportions.
Proportion-Annotation-Types-Dodge.png: Dodged bar plot of annotation type proportions.
