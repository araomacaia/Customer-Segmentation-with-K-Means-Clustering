# Customer Segmentation with K-Means Clustering

----
## Project Overview

In this project, I explored the Mall_Customers.csv dataset with the main focus on customer segmentation using K-Means clustering. The goal was to identify distinct customer groups based on Age, Annual Income, and Spending Score.

Through this analysis, I learned how K-Means clustering groups similar customers into distinct clusters, how to interpret cluster centroids to understand segment characteristics, and how to determine the optimal number of clusters using the Elbow Method. I also gained insights into different customer behaviors that could be useful for targeted marketing and business decision-making.

---
Dataset

The dataset contains 200 entries with the following columns:

  - **CustomerID** – Unique ID for each customer

  - **Gender** – Male or Female

  - **Age** – Age of the customer

  - **Annual Income (k$)** – Customer’s annual income in thousands

  - **Spending Score (1-100)** – Score representing spending behavior

  - **Shape:** (200, 5)

---
## What I Did in This Project

**1. Data Exploration**

  - Explored the dataset for missing values and understood the distribution of features.

  - Visualized Age, Annual Income, and Spending Score to identify patterns and potential clusters.

  - Learned how feature distributions can influence clustering results in K-Means.

**2. Preprocessing**

  - Encoded the Gender column to numerical values for analysis.

  - Prepared the data to ensure fair clustering and avoid bias due to scale differences.

  - Learned that proper preprocessing improves the quality and interpretability of K-Means clusters.

**3. K-Means Clustering**

  - Applied K-Means clustering to group customers into distinct segments.

  - Used the Elbow Method to determine the optimal number of clusters and learned why selecting the right k is crucial for meaningful segmentation.

  - Interpreted cluster centroids to understand the typical profile of each customer group, including income levels and spending behavior.

  - Learned that K-Means clusters can reveal hidden structures in customer data that are not obvious from raw features alone.

---
## Visualizations

## Customer Segments (K-Means Clustering)

The plot below shows the clusters of customers based on Annual Income and Spending Score:
<img width="2085" height="1634" alt="Customer Segments" src="https://github.com/user-attachments/assets/d26f5322-9c3e-47d1-a1f0-5e33db5a1ef0" />


## Elbow Method for Optimal K

The plot below shows the Elbow Method used to determine the optimal number of clusters:
<img width="2164" height="1403" alt="Elbow Method" src="https://github.com/user-attachments/assets/621c5ba5-ce24-4721-b718-9d79e4bd736a" />

---
## Key Insights

From the clustering analysis, I observed:

  - Clear separation of customer groups based on spending behavior and income.

  - High-income, high-spending customers, and low-income, low-spending customers form distinct clusters.

  - Cluster centroids helped summarize the characteristics of each segment and identify potential target groups.

  - Learned that K-Means is a powerful tool to discover hidden patterns and similarities among customers that can drive marketing strategies or business decisions.

---
## Tools and Libraries

  - Python 3.x

  - Pandas for data handling

  - NumPy for numerical computations

  - Matplotlib & Seaborn for visualization

  - scikit-learn for clustering

---
## Acknowledgements / References

I referred to the following materials while completing this project:

  - Steorts, Rebecca C. – K-means Clustering, Duke University, STA 325, Chapter 10 ISL

  - Ullman, Shimon; Poggio, Tomaso; Harari, Danny; Zysman, Daneil; Seibert, Darren – Class 13: Unsupervised Learning, Clustering

  - Scikit-learn Documentation – KMeans

  - Adams, Ryan P. – K-Means Clustering and Related Algorithms, COS324–Elements of Machine Learning, Princeton University

  - CSE 291: Geometric Algorithms – Lecture 3: Algorithms for k-means clustering, Spring 2013

  - Scikit-learn Documentation – 2.3. Clustering

  - Sharma, Pulkit – K-Means Clustering Algorithm, 01 May 2025

  - Statgraphics – K-Means Clustering, Revised 9/9/2019

  - CSC380: Principles of Data Science – Class Notes, Clustering (K-Means)

  - Lab 5: Clustering with Scikit-Learn, Scikit-learn Docs

  - Mihir Chandra & Ratul Das – Unsupervised Learning: K-Means, DBSCAN and Enumeration of Clusters, CS460, NISER

  - Kanungo, Tapas et al. – An Efficient K-Means Clustering Algorithm: Analysis and Implementation, IEEE

  - Rohini College of Engineering and Technology – Unsupervised Learning: K-Means Clustering Algorithm

---
## 📝 Author

**Arao Macaia**

AI & ML Internship Task 8 (2025)
