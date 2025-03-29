**Customer Segmentation Using K-Means Clustering**

📌 **Overview**

This project performs Customer Segmentation using K-Means Clustering, a popular unsupervised machine learning algorithm. The goal is to group customers based on their spending behavior, allowing businesses to understand different customer segments and target them effectively.

📊 **Dataset**

The dataset used for this project is the Mall Customers Dataset, downloaded via KaggleHub.
🔗 **Dataset Source:**

The dataset contains the following features:

CustomerID: Unique identifier for each customer.

Gender: Customer's gender.

Age: Customer's age.

Annual Income (k$): Customer's annual income in thousand dollars.

Spending Score (1-100): A score assigned based on customer behavior and spending patterns.
🚀 **Project Workflow**

Dataset Download & Loading

The dataset is downloaded using KaggleHub.

It is then loaded into a Pandas DataFrame for analysis.

Data Preprocessing

Checking for missing values.

Selecting relevant features (Annual Income & Spending Score) for clustering.

Standardizing the data for better clustering performance.

Finding Optimal Clusters

The Elbow Method is used to determine the optimal number of clusters.

We plot the Within-Cluster-Sum-of-Squares (WCSS) to find the "elbow point."

Applying K-Means Clustering

The dataset is clustered into 5 groups based on spending behavior.

Each customer is assigned a cluster label.

Data Visualization

A scatter plot is created to visualize different customer segments.

Cluster centroids are highlighted to show the center of each cluster.
📈 **Results**

The customers are grouped into different clusters based on their annual income and spending score. Businesses can use these clusters for targeted marketing strategies.

✨ **Visualization Example**

Scatter plot showing different customer clusters with centroids.

🎯 **Key Takeaways**

K-Means Clustering effectively segments customers based on spending patterns.

Elbow Method helps determine the optimal number of clusters.

Data visualization is crucial to understand cluster distribution.
📢 Contributing

**Feel free to fork this repository and make improvements! Pull requests are welcome. 😊
💡 Want to contribute? Feel free to fork, star ⭐, and raise issues!** 
🔗 Connect with me: https://www.linkedin.com/in/poorvi-shrivastava-4a34a9256/
