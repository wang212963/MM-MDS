Single-cell analysis of concurrent multiple myeloma and myelodysplastic syndromes (MM-MDS)
This repository contains the code for single-cell RNA sequencing analysis of bone marrow from patients with concurrent multiple myeloma and myelodysplastic syndromes (MM-MDS).

Overview
We performed single-cell sequencing on bone marrow cells from:

4 patients with concurrent MM and MDS (MM-MDS)

MM patients (for comparison)

Healthy donors (controls)

Key findings
Plasma cell malignancy: MM-MDS patients showed lower degree of plasma cell expansion and malignancy compared to MM patients

B cell enrichment: Higher frequency of B cells with positive regulation of immune response in MM-MDS

Myeloid differentiation: Distinct pathways and endpoints, with neutrophil-like monocytes appearing in low-risk MM-MDS patients

Cellular interactions:

In MM: B cells interact with plasma cells mainly via IL-16/CD4 signaling

In MM-MDS: B cells interact with plasma cells mainly via BTLA-TNFRSF14 signaling

Repository contents
Preprocessing scripts for raw scRNA-seq data

Quality control and filtering

Dimensionality reduction (PCA, UMAP)

Clustering and cell type annotation

Differential expression analysis

Cell-cell communication analysis (IL-16/CD4, BTLA-TNFRSF14 pathways)

Visualization scripts for figures

Requirements
R ≥ 4.1

Key packages: Seurat, dplyr, ggplot2, patchwork, CellChat (for interaction analysis)

Data availability
Raw sequencing data and processed count matrices are available at [GEO repository – to be added upon publication].

Usage
bash
git clone https://github.com/yourusername/MM-MDS-scRNAseq.git
cd MM-MDS-scRNAseq
Rscripts scripts/run_analysis.R
Citation
If you use this code in your research, please cite our paper:

[Your paper citation – to be added upon publication]
