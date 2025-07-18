# 🛒 E-Commerce Customer Spending Analysis

This project explores how customer activity on an e-commerce platform relates to their yearly spending. By analyzing behavioral data and using a simple Linear Regression model, we aim to predict how much a customer is likely to spend, based on factors like their time on the website or mobile app and their membership duration.

---

## 🎯 Objective

To identify the most important features that influence a customer’s **Yearly Amount Spent**, and build a model that can help the business understand and potentially increase customer value.

---

## 📊 Dataset Overview

The dataset contains the following key variables:
- **Average Session Length** – average time a customer spends per session
- **Time on App** – total time spent on the mobile app
- **Time on Website** – total time spent on the website
- **Length of Membership** – how long the customer has been with the company
- **Yearly Amount Spent** – the amount a customer spends in a year (our target variable)

---

## 🔍 Project Workflow

1. **Data Exploration**
   - Loaded and inspected the dataset for structure and missing values
   - Used visualizations (pairplots, heatmaps) to examine relationships between variables

2. **Feature Selection**
   - Selected relevant features that are most likely to impact spending behavior

3. **Model Building**
   - Split data into training and testing sets
   - Built a Linear Regression model using scikit-learn

4. **Model Evaluation**
   - Evaluated performance using Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE)
   - Checked residuals to assess the quality of model predictions

5. **Interpretation**
   - Identified **Length of Membership** and **Time on App** as the most influential factors in predicting yearly spending

---

## ✅ Business Insights

- **Mobile App Engagement Matters**: Customers who spend more time on the app tend to spend more overall, suggesting that mobile experience plays a significant role in purchase behavior.
- **Customer Retention is Key**: Longer membership duration is strongly associated with higher spending, highlighting the value of loyalty programs and long-term engagement.
- **Website Use is Less Predictive**: Compared to app usage, website time showed a weaker link to spending. This could help the company focus development efforts more effectively.

---

## 🧰 Tools Used

- Python  
- Pandas  
- Matplotlib & Seaborn  
- Scikit-learn  

---

Thanks for reading! This project demonstrates how simple regression techniques can provide meaningful business insights from customer data.
