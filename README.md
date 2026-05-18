# Proteomics LC-MS/MS Pipeline
**Neutrophil Elastase-Induced Macrophage Surface Proteome Analysis**

## Overview
End-to-end quantitative proteomics pipeline in Python, reproducing the analytical 
workflow from Ahmed et al., IJMS 2024 (DOI: 10.3390/ijms252313038). Analyzes 
label-free quantification (LFQ) data from Orbitrap Fusion Lumos to identify 
differentially expressed surface proteins in NE-treated human macrophages.

## Pipeline Steps
- LFQ data simulation (500 proteins, 6 samples, realistic missing values)
- MinProb missing value imputation + med
