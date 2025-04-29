# A-Comparative-Study-of-FP-Growth-and-Random-Forest-in-Market-Basket-Analysis
#Project Overview
This project presents a comparative study of two popular techniques — FP-Growth and Random Forest — in the context of Market Basket Analysis (MBA). The goal is to identify patterns, associations, and predictions from transaction data and evaluate the effectiveness of both approaches in discovering meaningful insights.

#Motivation
Market Basket Analysis is widely used in retail and e-commerce to understand customer purchasing behavior. Traditional association rule mining (like FP-Growth) uncovers frequent itemsets, while machine learning techniques (like Random Forest) can predict item relationships based on features. This project aims to compare these two paradigms based on:

Accuracy

Execution time

Scalability

Interpretability

#Technologies Used
Python 3.x

Scikit-learn

MLxtend

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

##Methodology
#Data Preprocessing

Cleaning transactional data

Data transformation into suitable formats for FP-Growth and Random Forest

#Applying FP-Growth

Extract frequent itemsets

Generate association rules

Measure support, confidence, and lift metrics

#Applying Random Forest

Feature engineering (one-hot encoding, transaction matrix)

Train/test split

Model training and evaluation (classification metrics)

#Evaluation Metrics

Precision, Recall, F1-Score (for Random Forest)

Rule Quality Measures (for FP-Growth)

Time performance and scalability testing

#Visualization

Itemset frequency plots

Feature importance plots

Comparative charts (accuracy vs. time)

#Results
FP-Growth is faster for large datasets with frequent itemsets.

Random Forest provides better predictive modeling when additional features are considered.

Trade-offs between interpretability (FP-Growth) and predictive power (Random Forest) are analyzed.


#Future Work
Test on larger and more complex datasets

Explore additional machine learning models like XGBoost, LightGBM

Implement hybrid models combining association mining and predictive modeling

Real-world deployment as a market recommendation engine

#Contributions
Contributions, issues, and feature requests are welcome!
Feel free to fork this project and submit a pull request.

#License
This project is licensed under the MIT License — see the LICENSE file for details.
