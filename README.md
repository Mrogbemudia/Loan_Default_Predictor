# Loan Default Prediction (Machine Learning Project)

Good Day! This s my Machine Learning project. 

I built this project to practice using Python, Pandas, and Scikit-Learn. My goal was to explore borrower data and build a machine learning pipeline to predict whether a borrower will fail to repay their loan (`repay_fail`).

---

## What I Aimed to Do
* **Data Exploration:** Understand key features like home ownership, loan purpose, and income verification.
* **Data Preprocessing:** Clean the dataset, handle missing values, and encode categorical variables for machine learning models.
* **Model Building:** Train classification algorithms to identify high-risk borrowers automatically.

---

## What the Data Showed (Exploratory Phase)

Out of **38,480 total borrowers** in the dataset, **5,829 defaulted** on their loans (around 15%). 

Some key patterns before training models:
* **Housing:** Renters (49.6%) and mortgage holders (42.0%) made up the vast majority of defaults compared to homeowners (7.9%).
* **Loan Purpose:** Nearly half of all defaulted loans (47.7%) were taken out for debt consolidation.

---

## Tools & Libraries Used
* **Python** (Core language)
* **Pandas & NumPy** (Data cleaning and feature transformation)
* **Matplotlib & Seaborn** (Data visualization)
* **Scikit-Learn / XGBoost** (Machine learning modeling and evaluation)
* **Jupyter Notebook** (Code development)

---

## How to Run the Project

1. Clone or download this repository.
2. Install the required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter