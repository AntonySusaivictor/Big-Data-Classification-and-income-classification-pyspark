# Income Classification Using PySpark

This project builds an income classification model using PySpark, designed to operate on large-scale datasets within a big data environment. It explores how socioeconomic features affect income levels and visualizes results using Tableau.

## Project Overview

- Built on Ubuntu using PySpark (inside Jupyter on VM)
- Applied Random Forest classification to predict income level (>50K or <=50K)
- Evaluated model with ROC AUC, F1-score, Precision, Recall
- Created visual dashboards using Tableau to communicate insights

##  Dataset

- Sourced from Kaggle: "American Citizen Income"
- ~50K records with features like age, education, occupation, capital gains, etc.

## Model

- **Algorithm**: Random Forest
- **AUC**: 0.909
- **F1-Score**: 0.652
- Used StringIndexer, OneHotEncoder, VectorAssembler for feature processing

##  Tools & Tech

- PySpark (MLlib, SQL)
- Ubuntu (VirtualBox VM)
- Jupyter Notebook
- Tableau

##  Insights

- Capital Gain & Capital Loss were most impactful
- Education level strongly correlates with income
- ROC curve and confusion matrix validate strong classification performance

##  Files

- `income_classification.ipynb` – PySpark model notebook
- `visuals.pdf` – Tableau dashboard export
- *Note: Dataset excluded due to file size*

##  Future Work

- Add XGBoost/Gradient Boosting comparison
- Automate preprocessing with pipelines
- Deploy on Spark cluster via Azure or AWS

