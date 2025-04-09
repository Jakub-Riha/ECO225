# ECO225 Replication Project

Replication materials for the ECO225 course project on Kiva loan data.

---

## 📄 Project Description

This repository contains code and supporting files for a machine learning analysis of microloan descriptions from Kiva.org. The project aims to classify loan descriptions using various supervised learning models, incorporating both textual sentiment and economic indicators.

---

## 💻 Code & Analysis

**Main File:**
- `ECO225_Code.ipynb` – A Jupyter Notebook containing:
  - Data cleaning and preprocessing  
  - Visualizations of key trends  
  - Feature engineering  
  - Machine learning pipeline for loan classification  

**To Replicate:**

1. Download the required datasets (see below)  
2. Place them in the appropriate folder  
3. Open the notebook and run all cells sequentially  

---

## 🗂️ Datasets

**External (must be downloaded):**  
📥 [Kiva Kaggle Dataset](https://www.kaggle.com/code/mhajabri/kiv-me-a-loan/input)

Required files:
- `loans.csv` – Primary loan-level data  
- `loan_coords.csv` – Geographical coordinates for each loan  

**Included in this repository:**
- `gdp_data.csv` – Country-level GDP  
- `mpi_data.csv` – Multidimensional Poverty Index  
- `llm_subsample.csv` – Subsample of 2,000 LLM-labeled loans used in classification tasks  
- `ECO225_Paper.pdf` – Final write-up for the project  

---

## ⚙️ Dependencies

- Python 3.8+
- Jupyter Notebook  
- Core packages used: `pandas`, `numpy`, `sklearn`, `matplotlib`, `seaborn`

---

## 📌 Notes

Due to GitHub’s file size limits, only essential supporting files are included. For full replication, refer to the Kaggle dataset linked above.
