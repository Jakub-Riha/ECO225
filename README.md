# ECO225 Replication Project

This repository contains code and supporting files for the ECO225 replication project. Due to file size limitations on GitHub, not all datasets used in the analysis are stored directly in this repository.

## 📊 Code and Analysis

The full analysis is contained in the Jupyter Notebook:

- `ECO225_Code.ipynb` – Contains data cleaning, visualisation, and machine learning pipeline for classification tasks on Kiva loan data.

To replicate the results, ensure you’ve downloaded the required datasets (see below), place them in the appropriate folder, and run the notebook from top to bottom.

## Accessing the Full Datasets

To access the full datasets required for replication, please visit the following Kaggle page:

🔗 [https://www.kaggle.com/code/mhajabri/kiv-me-a-loan/input](https://www.kaggle.com/code/mhajabri/kiv-me-a-loan/input)

From that page, download:

- **`loans.csv`** – The full primary dataset used in the analysis.  
- **`loan_coords.csv`** – Contains geographical coordinates (latitude and longitude) for each loan.

## Included in This Repository

The following supporting datasets have been uploaded here for convenience:

- `gdp_data.csv` – Country-level GDP data.  
- `mpi_data.csv` – Multidimensional Poverty Index (MPI) data.  
- `llm_subsample.csv` – A labeled subsample of 2,000 loans using a Large Language Model (LLM) for machine learning tasks.
