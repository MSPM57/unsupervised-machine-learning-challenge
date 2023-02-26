# unsupervised-machine-learning-challenge

Instructions
This activity is broken down into four parts:

Part 1: Prepare the Data.

Part 2: Apply Dimensionality Reduction.

Part 3: Perform a Cluster Analysis with K-means.

Part 4: Make a Recommendation.

Part 1: Prepare the Data
Read myopia.csv into a Pandas DataFrame.

Note: This file can be found in your Module 20 Challenge files.
Remove the "MYOPIC" column from the dataset.

Note: The target column is needed for supervised machine learning, but it will make an unsupervised model biased. After all, the target column is effectively providing clusters already!
Standardize your dataset so that columns that contain larger values do not influence the outcome more than columns with smaller values.

Part 2: Apply Dimensionality Reduction
Perform dimensionality reduction with PCA. How did the number of the features change?

From 14 Columnes I Reducated to 10 Columns.

Please see tsne_clusters.png
After applying the K-means please see  elbow_Curve.png and final_clusters.png

The overall perfomnce for this model is .8838709677419355
The clusters remained distinct after applying the Dimensionality Reduction and Performing a Cluster Analysis with K-means.

To my Supervisor I would recommend NOT to cluster the patients.
