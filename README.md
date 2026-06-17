🛒 Customer Segmentation using KMeans Clustering
📌 Project Overview
This project applies unsupervised machine learning (KMeans clustering) to segment customers based on their demographic and behavioral attributes. The goal is to identify distinct customer groups to help businesses tailor marketing strategies, improve customer engagement, and optimize product offerings.

📂 Dataset Summary
Features used:

Age

Annual Income (k$)

Spending Score (1–100)

Size: ~200+ customer records

Source: Mall Customer dataset (commonly used for segmentation tasks)

⚙️ Methodology
Data Preprocessing

Handled missing values
Converted categorical variables (e.g., Gender) into numeric form

Normalized features for clustering

Exploratory Data Analysis (EDA)

Visualized distributions of Age, Income, and Spending Score

Correlation heatmap to understand feature relationships

Clustering with KMeans

Applied the Elbow Method to determine optimal number of clusters

Trained KMeans model on selected features

Assigned cluster labels to each customer

Visualization

Scatter plots of clusters (Annual Income vs Spending Score)

Cluster centroids highlighted with star markers

Comparative analysis of cluster averages
