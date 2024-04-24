# Customer Segmentation Analysis

## Problem Statement:
The objective of this project is to perform in-depth customer segmentation analysis using electric vehicle (EV) usage data. By segmenting customers based on their EV usage patterns, we aim to assist an EV company in tailoring their marketing strategies and product offerings to specific customer segments. This analysis will enable the company to target the right customer groups effectively, thereby maximizing their marketing efforts and sales potential.

## Process:
* **Exploratory Data Analysis (EDA):**
    - Conducted thorough data cleaning, including handling missing values, duplicates, and outliers.
    - Utilized descriptive statistics and visualizations to gain insights into the distribution and characteristics of the data.
    - Identified key features that could potentially influence customer segmentation.

* **Feature Encoding:**
    - Applied label encoding to categorical variables to convert them into numerical format for machine learning algorithms.
    - Ensured consistency in data representation to facilitate model training.

* **Feature Scaling:**
    - Performed feature scaling using min-max scaling to normalize feature values within a specified range.
    - Addressed potential biases in the data caused by varying feature scales.

* **Creation of Dataset Copy:**
    - Created a copy of the original dataset to preserve the integrity of the raw data.
    - Conducted all subsequent analysis and modeling on the copied dataset to avoid data corruption.

* **Cumulative Explained Variance Plot:**
    - Constructed a cumulative explained variance plot to determine the optimal number of principal components for PCA.
    - Identified the principal components that captured the maximum variance in the data.

* **Principal Component Analysis (PCA):**
    - Implemented PCA to reduce the dimensionality of the dataset while preserving as much variance as possible.
    - Transformed the dataset into a lower-dimensional space for efficient clustering.

* **Elbow Curve Analysis:**
    - Utilized the elbow method to determine the optimal number of clusters for k-means clustering.
    - Selected the number of clusters based on the point of inflection in the elbow curve.

* **K-means Clustering:**
    - Applied the k-means clustering algorithm to group customers into distinct segments based on their EV usage patterns.
    - Clustered customers into five distinct groups to facilitate targeted marketing strategies.

* **Creation of Grouping Result Dataframe:**
    - Generated a dataframe containing the customer IDs and their respective cluster assignments.
    - Provided a structured format for further analysis and interpretation of clustering results.

## Libraries Used:
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset:
[Link to Dataset](insert_dataset_link_here)

## Grouping Result:
[Link to Grouping Result CSV](insert_grouping_result_link_here)

---

**Short Story (35-40 words):**
Conducted thorough analysis on EV usage data for customer segmentation. Employed data cleaning, encoding, scaling, PCA, and k-means clustering techniques to categorize customers. Delivering actionable insights to optimize marketing strategies for an EV company.
