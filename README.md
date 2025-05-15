#FYP on Predicting apparel batch efficiency using ML model

This is a final-year research project focused on predicting garment production efficiency using machine learning. The project processes raw factory data, cleans and engineers features, and builds a predictive model with business rule integration to assess production efficiency levels.

Project Overview
This system predicts the Overall Efficiency of a garment production line using a variety of operational and planning-related features. It uses data preprocessing, feature engineering, imputation, outlier handling, model comparison, and XGBoost tuning to deliver actionable predictions with integrated rule-based checks.

Key Features
Automated data cleaning and imputation (MICE + Winsorization)
Feature engineering (Efficiency Gap, Standard Hours Ratio, etc.)
Categorical encoding and normalization
PyCaret-powered model training and comparison
XGBoost-based prediction and hyperparameter tuning
Rule-based business logic for real-world production constraints
Human-readable feedback and actionable recommendations

Technologies Used
Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
PyCaret (automated ML workflows)
XGBoost (model training and interpretation)
Jupyter Notebook (development environment)

 Dataset
The system uses a CSV file SAP_output_2024_Prod.csv containing production line data such as:

Estimated Volume for the Season
Production Lead Time
Fabric Lead Time
Total Standard Hours
Total Overhead
Product Family
Efficiency Metrics

Usage
Run Model Training & Evaluation
The script performs:

Data preprocessing and cleaning
Feature engineering and selection
Model training using PyCaret
XGBoost tuning and evaluation

Author
Nilaksha Gajaman
Final year undergratuate of University of Westminster
