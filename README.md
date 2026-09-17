# Emergency Department Resource Phenotyping vs. Triage

This repository contains the Python and Jupyter Notebook source code for the data analysis pipeline presented in our study on emergency 
department (ED) resource utilization.

## 📌 Repository Structure

The analysis is organized into sequential steps:
* `0_run_pipeline.py`: Main Python script executing the core clustering workflow.
* `1_code_find_and_merge_xl.ipynb` to `6b_full_df_tabular_cleaning_...`: Data preparation, cleaning, and feature harmonization.
* `7_descriptive_analysis_clean.ipynb` & `8_correlation_hospit_vs_conso.ipynb`: Exploratory data analysis and correlations.
* `9_clustering_pipeline.ipynb` & `9bis_BERTopic.ipynb`: Core clustering implementation and topic modeling.
* `10_clusters_and_outliers_description.ipynb` to `13_alluvial_clusters.ipynb`: Cluster evaluation, visualization, and down-stream characterization (decision trees, regressions).

## 🛠️ Prerequisites

To run these notebooks, you will need Python 3.x along with the following data science libraries:
```bash
pip install pandas numpy scikit-learn hdbscan matplotlib seaborn bertopic jupyter
```

## 🔐 Data Privacy Note
The dataset used in this study contains sensitive, routinely collected electronic health records from Pellegrin Hospital (Bordeaux University Hospital, France). In compliance with medical confidentiality and data protection regulations (GDPR), the raw patient data cannot be made publicly available in this repository.

## 📨 Contact
For any questions or detailed explanations regarding the implementation, please contact the corresponding author.
