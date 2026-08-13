# Google Colab 
https://colab.research.google.com/drive/1EWuxwkBuzvY-rwAoBu-fp1jZS4z6kiti?usp=sharing 

# Customer Segmentation and Prediction

## Project Overview

This project analyzes customer purchasing behavior and predicts future purchase patterns using Python and machine learning.

## Objectives

- Clean and preprocess customer transaction data
- Perform exploratory data analysis
- Engineer customer-level features
- Perform RFM analysis
- Calculate Average Order Value (AOV)
- Calculate Purchase Frequency
- Estimate Customer Lifetime Value (CLV)
- Segment customers using K-Means clustering
- Predict future customer purchases using Random Forest
- Evaluate model performance
- Generate actionable business insights

## Dataset

Online Retail transactional dataset containing customer purchase history, products, quantities, prices, dates, and countries.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- K-Means Clustering
- Random Forest

## Project Workflow

1. Data Cleaning
2. Exploratory Data Analysis
3. Feature Engineering
4. RFM Analysis
5. Customer Lifetime Value
6. Feature Scaling
7. K-Means Clustering
8. Elbow Method
9. Silhouette Score
10. Customer Segmentation
11. Future Purchase Prediction
12. Random Forest Classification
13. Model Evaluation
14. Feature Importance
15. Business Insights

## Customer Segmentation Results

The optimal number of clusters was determined as:

**K = 2**

Silhouette Score:

**0.9400**

### Segment 1 — Regular / Lower-Value Customers

- Customers: 4,323
- Average Monetary Value: £1,654.22
- Average AOV: £375.43
- Average CLV: £2,276.89

### Segment 2 — High-Value / Loyal Customers

- Customers: 15
- Average Monetary Value: £115,734.55
- Average AOV: £12,582.84
- Average CLV: £133,663.24

## Predictive Model

A Random Forest Classifier was used to predict future purchase behavior.

### Model Performance

- Accuracy: 63.26%
- Precision: approximately 0.63
- Recall: approximately 0.63
- F1-score: approximately 0.63

## Feature Importance

The most important features for future purchase prediction were:

1. Monetary — 31.17%
2. Recency — 27.14%
3. AOV — 27.02%
4. Frequency — 10.98%
5. Purchase Frequency — 3.69%

## Business Insights

High-value customers represent a very small portion of the customer base but have substantially higher spending and customer lifetime value.

Regular customers can be targeted with personalized discounts, recommendations, cross-selling, and re-engagement campaigns.

High-value customers can be retained through VIP programs, exclusive offers, personalized recommendations, and premium customer service.

## Conclusion

The project demonstrates how customer transaction data can be transformed into actionable business insights using data cleaning, exploratory analysis, RFM-based feature engineering, K-Means clustering, and Random Forest classification.

The analysis helps businesses identify valuable customer segments and develop targeted marketing and customer retention strategies.

## Project Notebook

The complete analysis and machine learning implementation is available in:

`Customer_Segmentation_Prediction.ipynb`
