# Customer Segmentation using K-Means

## Project Overview

This project performs customer segmentation using unsupervised machine learning techniques.  
The goal is to identify different groups of customers based on their credit card usage behavior.

Customer segmentation allows financial institutions to better understand their clients and design targeted marketing and risk management strategies.

---

## Dataset

The dataset contains information about **8950 credit card customers** and their financial behavior.

Some of the key variables include:

- Balance
- Purchases
- Cash Advance
- Credit Limit
- Payments
- Minimum Payments

Each row represents a customer and their credit card usage patterns.

---

## Methodology

The analysis followed these main steps:

1. **Data Cleaning**
   - Removed identifier column (`CUST_ID`)
   - Handled missing values using median imputation

2. **Exploratory Data Analysis**
   - Boxplots used to inspect outliers
   - Distribution of financial variables analyzed

3. **Feature Scaling**
   - StandardScaler applied to normalize variables

4. **Cluster Selection**
   - Elbow Method
   - Silhouette Score

5. **Clustering Model**
   - K-Means clustering applied with **5 clusters**

---

## Results

The analysis identified five different customer segments:

- **Cluster 0:** High balance customers with significant credit usage
- **Cluster 1:** High spending customers (premium segment)
- **Cluster 2:** Moderate users with balanced behavior
- **Cluster 3:** Low credit limit customers
- **Cluster 4:** Low activity customers

---

## Visualizations

The project includes:

- PCA visualization of customer segments
- Heatmap showing feature profiles per cluster

These visualizations help interpret the behavioral patterns of each segment.

---

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

---

## Repository Structure

data/
notebooks/
README.md
requirements.txt

---

## Author

Alexis Núñez