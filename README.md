# Gene Expression Cancer Analysis

## Overview

Exploratory analysis of RNA-seq gene expression data across five
cancer types using Python.

The dataset contains **801 patient samples and 20,531 genes** from
The Cancer Genome Atlas (TCGA).

The project explores gene expression patterns across different cancer
types and identifies genes showing substantial variation between
groups.

## Cancer Types Analyzed

| Cancer Code | Cancer Type | Samples |
|-------------|-------------|---------|
| BRCA | Breast Cancer | 300 |
| KIRC | Kidney Cancer | 146 |
| LUAD | Lung Cancer | 141 |
| PRAD | Prostate Cancer | 136 |
| COAD | Colon Cancer | 78 |
| **Total** | | **801** |

## Project Objectives

The main objectives of this analysis were to:

- Explore RNA-seq gene expression patterns across cancer types
- Identify highly variable genes
- Compare average gene expression between cancer groups
- Visualize differences in gene expression
- Investigate genes showing notable differences between cancer types

## Analysis Workflow

```text
RNA-seq Expression Data
        ↓
Data Loading & Preprocessing
        ↓
Cancer Type Annotation
        ↓
Exploratory Data Analysis
        ↓
Gene Variability Analysis
        ↓
Top Variable Gene Selection
        ↓
Visualization & Comparison
        ↓
Biological Interpretation
