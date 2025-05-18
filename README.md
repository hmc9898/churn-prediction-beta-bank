# Churn Prediction for Beta Bank

## Project Overview

This project simulates a real-world business case for Beta Bank, a fictional financial institution aiming to reduce customer churn. The goal was to build a predictive machine learning model that classifies whether a client is likely to leave the service based on contract, service usage, and demographic features.

## Objectives

- Explore and visualize customer behavior
- Preprocess data to prepare for machine learning
- Train and evaluate classification models
- Deliver a reliable churn prediction model to support business retention efforts

##  Tools & Technologies

- **Languages:** Python  
- **Libraries:** pandas, numpy, scikit-learn, LightGBM, matplotlib, seaborn  
- **Environment:** Jupyter Notebook  

## Data Preprocessing

- Handled missing values and outliers
- Encoded categorical variables using OneHot and Label Encoding
- Scaled numeric features where needed
- Split dataset into training and test sets (80/20)

## Modeling & Evaluation

Three supervised learning models were tested:

- Logistic Regression  
- Random Forest Classifier  
- LightGBM (best performer)

**Best result:**  
 LightGBM achieved **~87% accuracy** on the test set with balanced precision and recall.

## Key Findings

- Customers with month-to-month contracts were significantly more likely to churn
- Service-related features like payment method and internet service played a key role
- The final model supports early targeting of high-risk customers to reduce churn

## Future Improvements

- Deploy the model via Streamlit or Flask for business use  
- Integrate additional behavioral data for richer feature sets  
- Schedule periodic retraining to account for changing customer behavior

## Author

Heather Marie Culligan  
[LinkedIn](https://linkedin.com/in/hmc2025)  
[GitHub](https://github.com/hmc9898)
