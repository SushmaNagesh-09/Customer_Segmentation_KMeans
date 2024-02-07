# Customer Segmentation using K-Means Algorithm

## This project aims to find the most profitable customer groups within the entire pool of customers to achieve more effective customer marketing.

Environment and Tools Used:
1. Language: Python
2. Libraries: Pandas, Numpy, Matplotlib, ScikitLearn, & Seaborn.

Approach to solve Customer Segmentation problem:
  1. Creating a Business Case
  2. Preparing the data
  3. Data analysis and exploration
  4. Clustering Analysis
  5. Choosing optimal hyperparameters
  6. Visualization and Interpretation

**What is Customer Segmentation?**
  customer segmentation is dividing a company's customers into groups that reflect similarity among customers in each group. The goal of segmenting customers is to decide how to relate to customers in each segment to maximize the value of each customer to the business. The process requires a thought-out strategy understanding of how to manage and group your customers and which data you will use.

Advantages of Customer Segmentation
  1. Price Optimization
  2. Enhances competitiveness
  3. Brand Awareness
  4. Acquisition & Retention
  5. Increases Revenue and ROI

**Why use Machine Learning?**
  Customer Segmentation was previously a challenging and time-consuming task that demanded hours of manually poring over different tables and querying the data in hopes of finding ways to group customers, but thanks to machine learning it finds statistical regularities in data. Machine learning models can process customer data and discover recurring patterns across various features.

**K - Means Algorithm**
  K-Means algorithm is an iterative algorithm that tries to partition the data set into key predefined distinct non-overlapping subgroups where each data point belongs to only one group. It tries to make the intra-cluster data points as similar as possible, while also keeping the clusters as different as possible.
 It assigns data points to a cluster such that, the sum of the squared distances between the data points and the cluster centroid is at the minimum. The less variation we have within clusters the more homogeneous data points are within the same cluster.
 
How to choose the optimum number of clusters?
  There are two possible ways of choosing the number of clusters.
  1. Elbow method: you draw a curve between WSS that is within the sum of squares and the number of clusters it is called the elbow method. Because the curve looks like a human arm and the elbow points give us the optimum number of clusters.
  2. Purpose-based: you can run a game in a clustering algorithm to get different clusters based on a variety of purposes. you can partition the data on different metrics and see how well it performs for the particular case.





