# Gene Expression Cancer Analysis

Exploratory analysis of RNA-Seq gene expression data across 5 cancer 
types using Python. Dataset contains 801 patient samples and 20,531 
genes from The Cancer Genome Atlas (TCGA).

---

### Cancer Types Analyzed

- BRCA — Breast Cancer (300 samples)
- KIRC — Kidney Cancer (146 samples)
- LUAD — Lung Cancer (141 samples)
- PRAD — Prostate Cancer (136 samples)
- COAD — Colon Cancer (78 samples)

---

### What this project covers

- Loading and merging gene expression data with cancer type labels
- Exploratory data analysis on 20,531 genes across 801 samples
- Identifying most variable genes across cancer types
- Heatmap visualization of top 50 most variable genes
- Average gene expression comparison across cancer types
- Box plot showing expression distribution of most variable gene

---

### Key Finding

Gene_9176 showed significantly higher expression in PRAD (Prostate 
Cancer) compared to all other cancer types — a pattern consistent 
with known prostate cancer gene expression profiles.

---

### Tools Used

- Python — pandas, matplotlib, seaborn
- Jupyter Notebook

---

### Files

- `Gene Expression Cancer RNA-Seq.ipynb` — full analysis notebook
