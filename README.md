# Data Science Project: Mastering Unsupervised Machine Learning, K-Means Method for Clustering 
K-means clustering is a widely-used machine learning technique for grouping similar data points. It iteratively assigns points to clusters based on their proximity to a central point, then recalculates that point to better represent the data. This continues until clusters stabilize, revealing patterns in the data.

The project's idea is to use Spotify's audio features to create meaninful playlists by using Unsupervised Machine Learning. Scikit-Learn provides a powerful implementation of K-Means clustering through the KMeans class from the cluster submodule. K-Means method is simple but powerful for grouping data, and the goal of the project was to to assess whether machine learning can effectively automate playlist creation or not.

## Project Overview:
Moosic is a start-up, its music experts create personalized playlists for the clients. As the business scales rapidly, the team is concerned that playlist creation is too slow. They are considering hiring data scientists to automate the process. While some team members doubt that audio features can truly capture a song's mood, others hope data science can enhance and streamline playlist creation. 

## Project Contributors:
A team of three people searched for an answer to the question posed.

## Main Questions:
1. Are Spotify’s audio features able to identify “similar songs”, as defined by humanly detectable criteria? 
2. Is K-Means a good method to create playlists? Would you stick with this algorithm moving forward, or explore other methods to create playlists?

## Steps of the Project:

1. Collection, Evaluation of Database
- Import the data of 5000 songs from Spotify API to Jupyter Notebook.
Perform Data Cleaning
K-Means Clustering
Elbow Method to decide optimal no. of clusters(K)
Cluster examination to evaluate the characteristics of each cluster
Reclustering
Final evaluation of clusters to form the playlists
