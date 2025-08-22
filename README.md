# CustomerSegmentation

Mall Customer Segmentation using KMeans Clustering
Project Overview
This project aims to segment mall customers into distinct groups based on their annual income and spending score using the KMeans clustering algorithm. By identifying these customer segments, businesses can gain insights into customer behavior and develop targeted marketing strategies.

Dataset
The dataset used for this project is Mall_Customers.csv. It contains the following columns:

CustomerID: Unique identifier for each customer.
Gender: Gender of the customer.
Age: Age of the customer.
Annual Income (k$): Annual income of the customer in thousands of dollars.
Spending Score (1-100): Score assigned by the mall based on customer behavior and spending nature (1-100).
The dataset contains 200 entries with no missing values, making it suitable for direct use.

Methodology
The project utilizes the KMeans clustering algorithm, an unsupervised machine learning technique, to group customers. The steps involved are:

Data Loading and Exploration: Loading the dataset and understanding its structure and contents.
Feature Selection: Selecting 'Annual Income (k$)' and 'Spending Score (1-100)' as the features for clustering.
Determining Optimal Clusters: Using the Elbow Method (WCSS) to find the optimal number of clusters. The elbow plot suggested that 5 clusters would be appropriate.
KMeans Clustering: Applying the KMeans algorithm with 5 clusters to the selected features.
Cluster Profiling: Analyzing the characteristics of each cluster based on the average annual income and spending score.
Visualization: Visualizing the clusters and their centroids to understand the segmentation visually.
Results
The KMeans algorithm segmented the customers into 5 distinct clusters. Each cluster represents a different customer group with unique characteristics based on their income and spending habits. The cluster profiling revealed groups such as high income-high spending, low income-low spending, etc. The visualizations clearly show these distinct groups in the annual income vs. spending score scatter plot.

Potential Applications
The identified customer segments can be highly valuable for the mall management for:

Targeted Marketing: Designing specific marketing campaigns and promotions tailored to the needs and preferences of each customer segment.
Personalized Offers: Offering personalized discounts and product recommendations based on the cluster a customer belongs to.
Store Layout and Product Placement: Optimizing store layout and product placement to cater to the dominant customer segments.
Customer Relationship Management: Developing strategies to improve engagement and loyalty within each customer group.
How to Use
To run this project:

Ensure you have Python and the necessary libraries (pandas, numpy, matplotlib, seaborn, scikit-learn) installed.
Download the Mall_Customers.csv dataset.
Run the provided Python notebook or script. The code will perform the clustering and visualization steps.
Conclusion
This project successfully demonstrates the application of KMeans clustering for customer segmentation based on mall customer data. The resulting clusters provide actionable insights that can be used to develop effective business strategies aimed at improving customer satisfaction and profitability.
