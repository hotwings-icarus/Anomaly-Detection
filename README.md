# Anomaly-Detection
## What is an Anomaly?
Anomalies are basically observations that deviate significantly from the rest.
## Anomaly/Outlier Detection
Outlier Detection, often referred to as anomaly detection is the process of identifying and detecting points of observations from a given dataset that deviate from the rest of the data and do not conform to an expected pattern.
### Types
Anomalies can be categorized as Global and Local. Further, based on the number of features, anomalies can also be classified as Univariate andMultivariate. The former kind of anomalies, univariate, are found in the distribution of values within a single feature space as the name suggests. The latter, multivariate, are found within an
n-dimensional (multi-dimensional or higher dimensional) space. It is often very computationally heavy to analyse high dimensional data, hence, a model that is fitted with a labeled training set that can analyse the anomalies in the test set efficiently is required.

## CBIF (Cluster-Based Isolation Forest) Algorithm
The objective of this  project is to contribute to the area of research of Anomaly Detection in High Dimensional Data by analysing and showing simulations in the
following manner:
1. A two-step progressive distance-ensemble based model to overcome the challenges posed by clustering and iForest individually (CBIF)
2. Two types of datasets are being taken- synthetic and real time data. The synthetic dataset gives an output of random instances, whereas the real time data gives an output of customer trading reports. It is difficult to find datasets with little to no inconsistencies, hence, comparing synthetic and real-time datasets will enable viewers to analyse the accuracy difference and understand real-life applications.
3. In this, clustering, based on distance, is the first step and is implemented to group the data into various clusters. Here, our aim is to use k-means clustering which is one of the most efficient algorithms to implement.
4. Next, iForest is applied on each individual cluster, iterated over them and based on the decision trees formed, anomalies are extracted.
