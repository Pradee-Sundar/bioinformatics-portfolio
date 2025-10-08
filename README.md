# GeoMX Data Analysis

This repository contains the **GeoMX DSP data analysis workflow**, focusing on **sample-wise differential expression analysis**
using **Linear Mixed-Effects Models (LMM)** to correct for batch effects and assess fixed effects such as tumor site.

This workflow was **adapted from the reference cited in the first markdown cell** of the Colab notebook, but modified to perform
**sample-wise differential expression** instead of cohort-wise analysis.

---

## 📘 Notebook

**Colab Notebook:** [Open in Google Colab](https://colab.research.google.com/drive/1R4Nxvg7Bq5m2k3PzG8paMxjCapTJmVyD?usp=sharing#scrollTo=CE8wTT7c7LE6)

### Highlights
- Data import, cleaning, and normalization of GeoMX DSP datasets.
- Application of **Linear Mixed-Effects Models (LMM)** for DE analysis to remove batch effects.
- Evaluation of **fixed effects (e.g., tumor site)** within the model.
- Visualization of DE results using volcano plots, heatmaps, and PCA.
- Automated generation of QC and summary plots for reproducibility.

---

## ⚙️ Setup Instructions

### Option 1: Run Locally
```bash
git clone https://github.com/Pradee-Sundar/bioinformatics-portfolio.git
cd bioinformatics-portfolio
pip install -r requirements.txt
jupyter notebook
```

### Option 2: View Online via Binder
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Pradee-Sundar/bioinformatics-portfolio/HEAD)

---

## 📦 Repository Structure
```
bioinformatics-portfolio/
│
├── notebooks/
│   └── GeoMX_data_analysis.ipynb  
├── data/
│   └── annotation/
│   └── dkcs/
│   └── pkcs/
├── README.md                           # Overview and instructions
├── requirements.txt                     # R dependencies for GeoMX workflow
└── LICENSE                              # MIT License
```

---

## 🧠 About
Developed by **Pradeepa S**, *Data Scientist – Bioinformatics*  
This repository demonstrates reproducible multi-omics data analysis workflows focused on **GeoMX DSP datasets**.
