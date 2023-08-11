# Online-Retail-unsupervised-project-Unsupervised-ML
Unsupervised ML

![Online retail](https://github.com/AshuKoche/Online-Retail-unsupervised-project-Unsupervised-ML/assets/129480612/065335a5-e5c7-4834-a0fd-42b7e44a0d5d)

# Project Summary: -

**Objective:**
This project aims to perform customer segmentation using unsupervised machine learning algorithms to identify distinct groups of customers based on their buying behavior.
**Approach:**
To achieve the objective, the following steps were followed:
**In-depth EDA:**
Exploratory data analysis is performed on the customer dataset to understand the data distribution, missing values, and outliers.
**Data preprocessing:**
The dataset is preprocessed by removing irrelevant columns, handling missing values, and scaling the features.
**Implementing Machine Learning Models**
**K-means clustering:*** K-means clustering algorithm was implemented to group the customers into K clusters based on their buying behavior. The optimal value of K is selected using the elbow method and silhouette score. In this project, it is found that the optimal number of clusters was 2.
**Hierarchical clustering:*** Hierarchical clustering algorithm was implemented to group the customers based on their similarity in buying behavior. The dendrogram was used to select the optimal number of clusters. In this project, the optimal number of clusters was found to be 2.
**DBSCAN:*** DBSCAN clustering algorithm was implemented to group the customers based on their density of buying behavior. The optimal values of eps and min_samples were selected using the elbow method.
**Results:*** The results of the project showed that customer segmentation using unsupervised machine learning algorithms can be a powerful tool for businesses to understand their customers' behavior and target them with appropriate marketing strategies. The project identified two distinct groups of customers based on their buying behavior and suggested appropriate marketing strategies to target each group.
**Conclusion:*** In conclusion, the project successfully implemented K-means clustering, hierarchical clustering, and DBSCAN machine learning algorithms to perform customer segmentation. The project's results demonstrate the effectiveness of unsupervised machine learning algorithms in customer segmentation, which can help businesses improve their marketing strategies and increase their sales. Additionally, the project found that there were two clusters that could effectively group the customers based on their buying behavior.


# **Problem Statement: -**

**In this project, the task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.**

# **Conclusion: -**

EDA

*   The United Kingdom accounted for the majority of orders at 88.95%, followed by Germany at 2.33%, France at 1.84%, Ireland at 1.84%, and Spain at 0.62%.
*   The top stock codes, ranked by count values, are 85123A, 22423, 85099B, 47566, and 84879.
*   The following customer IDs are identified as the top five: 14646.0, 14911.0, 12415.0, 17450.0, and 18102.0.
*   The top 5 high demanded stock are 12197, 84077, 85099B, 84879 and 21212.
The months with the most sales are November, October, December, September, and May.
*   The highest sales are recorded on Thursday followed by Tuesday.
*   The majority of customers made purchases between 10:00 A.M. and 2:00 P.M.
*   The top 5 repeated customers are 14911, 12784, 1784, 14606 and 13081.

**ML Model**

*   Different clustering algorithms were applied to the dataset, considering Recency, Frequency, and Monetary (RFM), and 2 optimal clusters found.
