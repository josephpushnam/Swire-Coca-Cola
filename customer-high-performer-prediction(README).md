# 🚀 Customer High Performer Prediction

---

## 🧠 Summary of Business Problem and Project Objective
This project focuses on predicting high-performing customers for Swire Coca-Cola, defined as customers ordering **400 or more gallons** in their second year of activity (Y2). Only **approximately 15%** of customers meet this threshold, making early identification critical for targeted marketing, resource prioritization, and operational planning. By predicting future purchasing behavior, Swire Coca-Cola can focus its efforts on customers with the highest growth potential, optimizing revenue and customer lifetime value.

---

## 🛠️ Our Solution
To address this problem, I developed a predictive machine learning model using an XGBoost Classifier. The end-to-end workflow included:
- Cleaning a dataset of approximately **7,000 customer records** and removing **over 20 redundant or irrelevant fields**.
- Encoding **5 categorical variables** into numerical formats.
- Engineering a binary target variable based on the **400-gallon** cutoff.
- Handling severe class imbalance with a **scale_pos_weight of 20** during model training.
- Extracting feature importances and identifying the **Top 10 key drivers** influencing customer performance.
- Exporting a ranked list of top-predicted high performers, representing **approximately the top 10%** of customers by likelihood.

---

## 🙋‍♂️ My Contribution
I independently led the full lifecycle of the project, contributing:
- Data preprocessing and cleaning of **7,000+ records**.
- Feature engineering and target creation based on clear business rules.
- Training and tuning an XGBoost Classifier with appropriate imbalance correction.
- Model interpretability via feature importance analysis, highlighting key variables such as **average gallons ordered**, **order frequency**, and **customer tenure**.
- Exporting actionable customer predictions to CSV files for business use.
- Structuring and documenting the notebook with **over 20 well-commented code cells** for clarity and reproducibility.

---

## 📈 Business Value of the Solution
The model provides a scalable way to drive business outcomes by:
- Identifying the top **10–15%** of customers likely to deliver **400+ gallons** annually.
- Helping sales teams prioritize outreach and account management efforts more efficiently.
- Potentially increasing customer retention rates by **10–20%** through proactive engagement.
- Reducing wasted marketing spend by focusing resources on customers with the highest likelihood of return on investment (ROI).

---

## ⚙️ Difficulties Encountered
The main technical difficulty was the extreme class imbalance, where high performers made up only **~15%** of the dataset. Standard models heavily favored the majority class.  
I addressed this by setting the `scale_pos_weight` parameter to **20** in XGBoost, which improved the model's ability to correctly identify minority class instances while balancing precision and recall.  
Iterative experimentation with probability thresholds was also necessary to optimize business actionability.

---

## 📚 What I Learned
Key learnings from this project include:
- Practical application of machine learning models to real-world class imbalance problems.
- Feature selection and interpretation, with a focus on variables that drive tangible business outcomes.
- Understanding the trade-offs between precision and recall in business settings where false positives and false negatives have asymmetric costs.
- Strengthening technical communication skills by linking model outputs directly to business strategies and operational improvements.

---

## 🖥️ How to Run
This notebook was built and tested in **Google Colab**.

To replicate the analysis:
1. Install the necessary libraries (`xgboost`, `scikit-learn`, `seaborn`, `matplotlib`, `pandas`, `numpy`).
2. Upload the cleaned dataset (excluded from this repository for confidentiality reasons).
3. Execute each code cell sequentially from top to bottom.
4. Review feature importance plots and exported prediction files for actionable insights.

---


# 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
