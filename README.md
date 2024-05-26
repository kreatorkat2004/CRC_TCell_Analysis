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

## Code
The main analysis is performed in the following R script:
