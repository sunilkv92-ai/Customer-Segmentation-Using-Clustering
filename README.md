Customer Segmentation Using Clustering. 

Title: "Customer Segmentation Using Clustering"

Libraries Imported: It uses libraries such as pandas, numpy, matplotlib, seaborn, and various scikit-learn components (e.g., StandardScaler, PCA, KMeans, DBSCAN, etc.).
Dataset: A dataset is loaded from a CSV file called Dataset.csv.

Data :

The notebook loads a dataset called Dataset.csv. Make sure this file is available in the same directory as the notebook or provide the correct path.

Procedure : 

Library Import: The notebook begins by importing necessary libraries such as pandas, numpy, matplotlib, and scikit-learn.
Dataset Loading: The dataset is loaded from a CSV file and is processed for analysis.
Data Preprocessing: Features are standardized using StandardScaler to prepare for clustering.
Principal Component Analysis (PCA): Dimensionality reduction using PCA is applied to visualize and handle high-dimensional data.

Clustering Algorithms:
K-Means Clustering: The algorithm is applied to group customers based on the optimal number of clusters.
DBSCAN: Another clustering algorithm that groups customers based on density.
Evaluation: The notebook evaluates the clustering performance using metrics like silhouette score.

How to Run :

Clone or download this repository.
Ensure that you have the required dependencies installed.
Place the dataset (Dataset.csv) in the working directory.
Open the Clustering.ipynb file using Jupyter Notebook or any other compatible editor.
Run each cell sequentially to execute the analysis.

Results :

The final section of the notebook provides visualizations of the clusters and evaluates the performance of each clustering algorithm. Insights from the clustering results help in understanding customer segments.
