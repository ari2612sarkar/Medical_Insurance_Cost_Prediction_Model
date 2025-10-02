# ES60011 - Application of Machine Learning in Biological Systems  
## Project 1: Medical Insurance Cost Prediction  

### Objective
Estimate individual medical insurance expenses based on age, BMI, smoking status, and other health-related variables using **manual linear regression** (no scikit-learn).

### Dataset
- `age`: Age of primary policyholder  
- `sex`: Gender (male/female)  
- `bmi`: Body Mass Index  
- `children`: Number of dependents  
- `smoker`: Smoking status (yes/no)  
- `region`: US region (northeast, southeast, southwest, northwest)  
- `charges`: Medical expenses billed  

### Methodology
1. Data exploration and feature engineering  
2. Manual implementation of Linear Regression using the closed-form OLS solution:  
   \[
   \\beta = (X^T X)^{-1} X^T y
   \]
3. Coefficient analysis to identify most influential factors.  

### Deliverables
- **Notebook**: `notebooks/Project1_Aritra_ManualLR.ipynb`  
- **Predictions**: `outputs/predictions.csv`
- **Model**: `model/Medical_Linear_Regression_model.pkl` 
- **Dataset**: `data/data_insurance.csv`  

### Results
- Model achieves good predictive performance with manual regression.  
- Smoking, age, and BMI are the most influential predictors.  
