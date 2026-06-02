# AI & ML Task 3: Model Validation, Overfitting Control & Hyperparameter Tuning

## Overview
This project is part of the Artificial Intelligence & Machine Learning Internship at **MainCrafts Technology**.  
In this task, I enhanced the California Housing Price Prediction model by implementing:

- Overfitting detection and control
- Cross-Validation for reliable evaluation
- Hyperparameter Tuning using GridSearchCV
- Final model selection with proper justification

## Key Features Implemented

- **Overfitting Analysis**: Compared Train vs Test performance on default Decision Tree
- **Cross-Validation**: Used 5-Fold Cross Validation for stable performance estimation
- **Hyperparameter Tuning**: Optimized Decision Tree using GridSearchCV
- **Model Comparison**: Linear Regression, Ridge Regression, and Tuned Decision Tree
- **Best Model**: Tuned Decision Tree Regressor (Best generalization)

## Repository Contents

- `AI_ML_Task3_Model_Validation_Tuning.ipynb` → Main Jupyter Notebook
- `best_tuned_model.pkl` → Trained & Tuned Best Model
- `scaler_task3.pkl` → Fitted StandardScaler
- `AI_ML_Task3_Report.pdf` → Project Report

## Technologies Used
- Python
- scikit-learn
- pandas, numpy, matplotlib, seaborn
- Jupyter Notebook

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/manidharbtech4-commits/california-housing-task3.git
