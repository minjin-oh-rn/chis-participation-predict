# Notebooks – Step-by-Step Analysis

This folder contains the Jupyter Notebooks used for the stepwise data analysis.  
Each file reflects a key step in the theory-driven predictive modeling pipeline.

### 01_preprocessing.ipynb
- Cleaned CHIS 2023 dataset  
- Selected predictors based on Donabedian and social capital frameworks  
- Encoded categorical variables and normalized scores  

### 02_modeling.ipynb
- Defined outcome: program continuity (≥2 vs ≤1 participation)  
- Performed logistic regression and XGBoost classification  
- Evaluated feature importance and model performance  

### 03_shap_analysis.ipynb
- Generated SHAP values to assess feature contribution  
- Visualized individual and global importance of trust and access variables  
- Identified dropout risk patterns in low-trust/low-access groups  

These notebooks follow a reproducible structure for interpreting equity-relevant predictors in community health participation.
