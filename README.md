# Do Microfinance Institutions Prioritise Need? Evidence from Loan Allocation and Repeat Borrowing Patterns 

Replication files & code for an ECO225 course project.

---

## 📄 Project Description

This repository contains the paper PDF, conference presentation PDF, code, and supporting files, for a regression and machine learning analysis of microloans from Kiva.org. The project aims to use  loan descriptions classified into low-need and high-need loans to investigate whether microfinance institutions allocate loan capital in proportion to borrower financial need, and whether repeated borrowing grows or shrinks.

---

## 💻 Code & Analysis

**Main File:**
- `ECO225_Code.ipynb` – A Jupyter Notebook containing:
  - Data cleaning and preprocessing  
  - Visualisations of key trends  
  - Feature engineering  
  - Machine learning pipeline for loan classification
  - Regression analysis of loans and disbursement amounts

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
- `ECO225_Paper.pdf` – Paper PDF for the project
- `Tech-Econference_Presentation.pdf` – Presentation PDF for the project at the 5th Annual Econ-Tech Conference (2025), University of Toronto

---

## ⚙️ Dependencies

- Python 3.8+
- Jupyter Notebook  
- Core packages used: `pandas`, `numpy`, `sklearn`, `matplotlib`, `seaborn`

---

## 📌 Notes

Due to GitHub’s file size limits, only essential supporting files are included. For full replication, refer to the Kaggle dataset linked above.
