# unsupervised-machine-learning-challenge
Module 20 Challenge

This notebook reads in the myopia csv file and attempts to cluster the data in the dataset.
After dropping the "MYOPIA" column, the values are standardized such that columns that contain larger values do not influence the outcome more than columns with smaller values.

Next, dimensionality reduction using PCA was utilized and found to have a variance of 0.96.
T-SNE was also used to further reduce the dataset and graph a scatterplot of the values.
Displaying the two species of data, it was determined that no distinct clusters existed in the dataset because neither of the species clearly grouped up with each other separate from the other species.

Next, a cluster analysis using k-means was conducted.
An elbow plot was generated. The shape of the elbow curve was smooth and did not definitively/sharply change direction anywhere on the graph.
The biggest shift was located at k = 3.

It was not recommended to cluster the patients in the myopia dataset based on the findings of the analysis.