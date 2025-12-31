🚀 KMeans Clustering from Scratch

📝 Project Overview
This project implements the KMeans clustering algorithm from scratch in Python.
It focuses on understanding the internal mechanics of KMeans, including centroid initialization, cluster assignment, and iterative optimization, without using any pre-built machine learning libraries.

🔍 Problem Statement
The goal is to group data points into K clusters based on feature similarity.
Key technical challenges include:

Initializing centroids effectively

Assigning data points to the nearest centroid

Iteratively updating centroids until convergence

Handling convergence criteria and empty clusters

💻 Technologies Used

Python

NumPy – Numerical computations and matrix operations

Matplotlib & Seaborn – Data visualization

⚙️ How It Works

Load Data: Import your dataset (CSV, NumPy arrays, etc.).

Initialize Centroids: Randomly select K points as initial centroids.

Cluster Assignment: Assign each data point to the nearest centroid.

Update Centroids: Recalculate centroids as the mean of assigned points.

Repeat: Iterate cluster assignment and centroid update until centroids stabilize.

Visualization: Plot clusters to verify results.

🛠 Installation
To install the required packages, run:

pip install -r requirements.txt
