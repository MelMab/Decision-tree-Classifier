# Decision-tree-Classifier
# Loan Prediction using Decision Tree Classifier

## Project Overview
This project focuses on building a machine learning model to predict whether a loan application will be approved or not. I used a **Decision Tree Classifier**, applied data preprocessing techniques, and evaluated the model’s performance on both training and test datasets.  

The aim of this project is to demonstrate skills in:
- Data cleaning and preprocessing
- Building a classification model
- Hyperparameter tuning
- Model evaluation and interpretation

## Dataset
The dataset contains loan application records with features such as:
- Applicant’s income
- Loan amount
- Loan term
- Credit history
- Gender, marital status, education, etc.

Target variable: **Loan Status** (Approved / Not Approved).  

The data required cleaning and preprocessing:
- Handling missing values
- Encoding categorical variables
- Scaling/normalizing numerical features where necessary

---

## Methodology
1. **Data Preprocessing**
   - Filled missing values
   - Converted categorical values into numerical form
   - Standardized/normalized data for consistency

2. **Model Selection**
   - Implemented a **Decision Tree Classifier**
   - Used cross-validation to find the best `max_depth` parameter

3. **Model Evaluation**
   - Evaluated with accuracy, precision, recall, and F1-score
   - Compared cross-validation accuracy with test set accuracy

---

## Results
- **Best Max Depth:** 1  
- **Cross-Validation Accuracy:** 0.814  
- **Test Set Accuracy:** 0.789  

**Classification Report (Test Set):**

| Metric         | Class 0 (Not Approved) | Class 1 (Approved) |
|----------------|-------------------------|---------------------|
| Precision      | 0.89                   | 0.77                |
| Recall         | 0.42                   | 0.97                |
| F1-score       | 0.58                   | 0.86                |
| Support        | 40                     | 79                  |

**Overall Performance:**
- Macro Avg F1-score: 0.72  
- Weighted Avg F1-score: 0.76  


## Insights
- The model performs well on predicting **approved loans** (high recall of 0.97).  
- Performance on **not approved loans** is weaker (recall of 0.42), meaning some non-approved cases are misclassified.  
 

## Tools Used
- Python (pandas, numpy, scikit-learn, matplotlib)
- Google Colab

---

## Author
Created by **Mellisa Zandile Mabeza**  
[LinkedIn](http://www.linkedin.com/in/mellisa-z-mabeza25)

---
