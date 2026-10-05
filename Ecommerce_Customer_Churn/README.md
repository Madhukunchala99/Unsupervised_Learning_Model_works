# E-Commerce Customer Churn Analysis – Unsupervised Learning

## Project Overview

This project focuses on analyzing **E-Commerce Customer Churn using Unsupervised Learning techniques**. The objective is to identify groups of customers with similar characteristics and understand which customer segments may have a higher risk of churn.

Unlike supervised learning, no churn label was used to create the clusters. The focus was on discovering hidden patterns and natural customer groups within the dataset.

## Objectives

* Understand customer behavior and characteristics
* Clean and preprocess the customer dataset
* Prepare numerical and categorical features
* Scale the data before clustering
* Reduce dimensionality using PCA
* Apply different clustering algorithms
* Evaluate clustering quality
* Identify meaningful customer segments
* Analyze churn distribution within the discovered clusters

## Techniques Used

The project includes:

* **PCA (Principal Component Analysis)**
* **K-Means Clustering**
* **Hierarchical Clustering**
* **DBSCAN**

## Project Workflow

1. Load and understand the customer dataset
2. Check for missing values and duplicate records
3. Clean and preprocess the data
4. Encode categorical variables
5. Scale the features
6. Apply PCA for dimensionality reduction
7. Apply K-Means clustering and select a suitable number of clusters
8. Apply Hierarchical Clustering
9. Apply DBSCAN to identify dense groups and outliers
10. Evaluate the clustering results using the Silhouette Score
11. Analyze the characteristics and churn distribution of each cluster
12. Assign meaningful names to the customer segments

## Key Analysis

The discovered customer groups were analyzed using factors such as:

* Customer satisfaction
* Monthly charges
* Usage behavior
* Contract type
* Support interactions
* Churn distribution

The clusters were interpreted based on their characteristics to identify groups such as **Higher-Risk Customers** and **More Satisfied Customers**.

## Business Value

The analysis can help an e-commerce or subscription-based business understand different customer groups and identify segments that may require additional attention.

Businesses can use these insights to:

* Prioritize high-risk customers
* Develop targeted retention strategies
* Understand customer behavior
* Improve customer satisfaction
* Design segment-specific offers and engagement strategies

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* PCA
* K-Means
* Hierarchical Clustering
* DBSCAN
* Google Colab / Jupyter Notebook

## Conclusion

This project demonstrates a complete **Unsupervised Learning workflow**, including data preprocessing, feature transformation, dimensionality reduction, clustering, evaluation, and business interpretation. It shows how customer data can be analyzed without directly using churn as a prediction target to discover meaningful customer segments.
