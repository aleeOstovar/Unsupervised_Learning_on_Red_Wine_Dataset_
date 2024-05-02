#Red Wine Dataset Clustering Analysis
##Overview
This repository contains code for applying unsupervised learning methods, specifically KMeans and Hierarchical Clustering, on the Red Wine Dataset from the UCL Machine Learning Repository. The aim is to analyze and cluster the data to gain insights into different groups or patterns within the dataset.

##Dataset
The Red Wine Dataset is publicly available on the UCL Machine Learning Repository. It includes various physicochemical properties of red wine samples, such as acidity, pH, alcohol content, etc. The dataset also includes a quality rating for each wine sample.

Dataset Link: [Red Wine Dataset]([https://pip.pypa.io/en/stable/](https://archive.ics.uci.edu/dataset/186/wine+quality))

##Requirements
*Python 3.x
*Libraries: 
    **pandas, 
    **numpy, 
    **scikit-learn, 
    **matplotlib, 
    **seaborn
    **yellowbrick

##Results
The results of the clustering analysis are visualized using scatter plots and dendrograms for KMeans and Hierarchical Clustering, respectively. The elbow method and KElbowVisualizer are utilized to determine the optimal number of clusters for KMeans. The silhouette score is calculated to evaluate the quality of the clusters.

##File Structure
wine_classification.ipynb : Python script for performing clustering analysis in jupyter notebook
README.md: Documentation for the repository
dataset.csv: Red Wine Dataset

##License
This project is licensed under the MIT License.
