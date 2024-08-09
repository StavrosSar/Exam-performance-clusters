**Project Overview**

This repository contains a Python script that analyzes the 2012 SAT Results dataset to identify clusters of schools based on their exam performance. The script uses clustering algorithms (KMeans and DBSCAN) and dimensionality reduction techniques (PCA) to visualize the results.

**Code Structure**

The script consists of several sections:

1. **Data Loading**: The script loads the 2012 SAT Results dataset from a CSV file and removes rows with "s" values in specified columns.
2. **Data Preprocessing**: The script sets environment variables to avoid memory leak warnings and suppresses FutureWarning related to use_inf_as_na.
3. **Visualization**: The script creates histograms and pie charts to visualize the distribution of exam scores and the number of schools in each cluster.
4. **Clustering**: The script applies KMeans and DBSCAN clustering algorithms to identify clusters of schools based on their exam performance.
5. **Cluster Analysis**: The script calculates the average number of test takers for each cluster and identifies the schools in each cluster.
6. **Intersection of Clusters**: The script identifies the intersection of school names between two clusters (KMeans and DBSCAN) and prints the school names.

**Requirements**

* Python 3.x
* Pandas library
* NumPy library
* Scikit-learn library
* Matplotlib library
* Seaborn library

**Running the Script**

To run the script, simply execute the Python file using Python 3.x. You can also modify the script to change the clustering algorithm, number of clusters, or other parameters to suit your analysis needs.

**Results**

The script produces several visualizations and outputs that provide insights into the clustering results. The results include:

* Histograms of exam scores
* Pie charts of average scores by cluster
* Bar plots of number of schools in each cluster
* Intersection of school names between two clusters

**License**

This script is licensed under the MIT License. Please see the LICENSE file for details.

**Acknowledgments**

This script is based on the 2012 SAT Results dataset, which is publicly available from the College Board website.
