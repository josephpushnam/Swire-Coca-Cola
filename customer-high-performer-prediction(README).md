# Customer High Performer Prediction

## Summary of Business Problem and Project Objective
This project focuses on predicting high-performing customers for Swire Coca-Cola, defined as customers ordering 400 or more gallons in Year 2. The goal is to identify these customers early for targeted marketing and sales efforts.

## Our Solution
I developed a predictive model using an XGBoost Classifier. After cleaning and preparing the data, I trained the model to classify customers as high-performers or not. Feature importance analysis was performed to understand the key drivers behind customer behavior. Top predicted high performers were exported for business action.

## My Contribution
In this project, I independently conducted data cleaning, feature engineering, model training, evaluation, and business interpretation. I focused on building a reliable machine learning pipeline that identifies and prioritizes high-value customers.

## Business Value of the Solution
By identifying customers likely to purchase in higher volumes, Swire Coca-Cola can better allocate sales resources, prioritize customer retention efforts, and optimize promotional campaigns, leading to increased revenue and operational efficiency.

## Difficulties Encountered
One challenge was the significant class imbalance, with far fewer customers qualifying as high performers. I addressed this using XGBoost's `scale_pos_weight` parameter to ensure the model did not favor the majority class.

## What I Learned
Through this project, I deepened my skills in predictive modeling, handling imbalanced datasets, interpreting feature importance, and applying machine learning for customer segmentation in a real-world business context.

## How to Run
This notebook was built in Google Colab.  
To replicate:
- Install necessary libraries.
- Upload the cleaned dataset (data not included here for confidentiality).
- Run the notebook sequentially.

# 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
