# E-Commerce Recommendation System using Machine Learning

## Project Overview

This project implements an **E-Commerce Recommendation System** using multiple Machine Learning algorithms to improve product recommendations and customer targeting. The system analyzes customer behavior, predicts product ratings, estimates purchase likelihood, and segments customers based on shopping patterns.

The project demonstrates the application of Regression, Classification, Clustering, Hyperparameter Tuning, and Model Evaluation techniques to solve real-world business problems in e-commerce.

---

## Business Problem

E-commerce platforms generate large amounts of customer data through browsing history, purchase history, product ratings, and spending behavior. Businesses can use this information to:

* Recommend products customers are likely to purchase
* Predict customer ratings for products
* Identify customers with high purchase potential
* Segment customers for targeted marketing campaigns
* Improve overall customer experience and sales conversion

---

## Project Objectives

* Predict customer ratings using Regression.
* Predict purchase likelihood using Classification.
* Segment customers using Clustering.
* Optimize model performance using Hyperparameter Tuning.
* Compare multiple machine learning models using evaluation metrics.
* Interpret results from a business perspective.

---

## Dataset

The dataset contains customer, product, and transaction information.

### Features

| Column             | Description                     |
| ------------------ | ------------------------------- |
| User_ID            | Unique customer ID              |
| Product_ID         | Unique product ID               |
| Category           | Product category                |
| Price              | Product price                   |
| Rating             | Customer rating                 |
| Browsing_Time      | Time spent browsing the product |
| Previous_Purchases | Number of previous purchases    |
| Cart_Addition      | Product added to cart (0/1)     |
| Purchase_Status    | Purchased or not (0/1)          |
| Age                | Customer age                    |
| Gender             | Customer gender                 |
| Location           | Customer location               |
| Discount_Applied   | Discount applied (0/1)          |
| Total_Spending     | Total customer spending         |

---

## Machine Learning Tasks

### 1. Regression

**Objective**

Predict the product rating given by a customer.

**Algorithm**

* Linear Regression
* Ridge Regression

**Evaluation Metrics**

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

---

### 2. Classification

**Objective**

Predict whether a customer will purchase a product.

**Algorithm**

* Logistic Regression

**Evaluation Metrics**

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score

---

### 3. Clustering

**Objective**

Group customers based on shopping behavior.

**Algorithm**

* K-Means Clustering

**Evaluation Metrics**

* Inertia
* Silhouette Score
* Elbow Method

---

### 4. Hyperparameter Optimization

The models are optimized using:

* GridSearchCV
* RandomizedSearchCV

Hyperparameters tuned include:

* Ridge Regression (`alpha`)
* Logistic Regression (`C`, `penalty`, `solver`, `max_iter`)
* K-Means (`n_clusters`, `init`, `max_iter`)

---

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Data Preprocessing
4. Exploratory Data Analysis (EDA)
5. Feature Encoding
6. Feature Scaling
7. Regression Model
8. Classification Model
9. Clustering Model
10. Hyperparameter Tuning
11. Model Evaluation
12. Business Interpretation
13. Conclusion

---

## Project Structure

```
Recommendation-System-Ecommerce/
│
├── data/
│   └── ecommerce_dataset.csv
│
├── notebooks/
│   └── Recommendation_System.ipynb
│
├── images/
│
├── models/
│
├── requirements.txt
│
└── README.md
```

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib
* Jupyter Notebook

---

## Exploratory Data Analysis

The project includes visualizations such as:

* Product Category Distribution
* Purchase Status Distribution
* Customer Spending Distribution
* Rating Distribution
* Correlation Heatmap
* Elbow Method Graph
* Customer Segmentation Plot
* Confusion Matrix

---

## Business Benefits

This recommendation system helps businesses to:

* Recommend products with higher predicted ratings.
* Identify customers likely to purchase products.
* Improve personalized recommendations.
* Create targeted marketing campaigns.
* Increase customer engagement.
* Improve sales conversion.
* Enhance customer satisfaction.

---

## Results

The project compares multiple machine learning models based on their evaluation metrics and business usefulness. The best-performing models are selected after hyperparameter tuning to maximize prediction accuracy and recommendation quality.

---

## Conclusion

This project demonstrates how machine learning can be applied to build an effective e-commerce recommendation system. Regression predicts customer ratings, classification estimates purchase likelihood, and clustering identifies customer segments. Together, these techniques enable personalized recommendations, improve marketing strategies, and support data-driven business decisions.

---

## Future Enhancements

* Implement Collaborative Filtering
* Add Content-Based Recommendation
* Build a Hybrid Recommendation System
* Deploy the model using Flask or Streamlit
* Integrate real-time recommendation APIs
* Improve scalability using cloud deployment

---

## Author

**P. Harshitha**

AIML Internship Project
