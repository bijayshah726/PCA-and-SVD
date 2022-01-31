# PCA-and-SVD
I have tried to explain the subtle difference between the Principal Component Analysis and Singular Value Decomposition in this.

.ipynb file is shared that explains the step to perform the PCA and SVD analysis in Python.


In PCA, for a given dataset X(that is centered i.e mean=0) with shape n* m, where m is the number of features and n is the number of measurements, X'X/(n-1) will be the covariance matrix and eigen vector of this covariance matrix can be used to transform the data into another space where most important features are extracted (3blue1brown Linear Algebra series is a must watch for any engineering students).

In SVD, same matrix X is decomposed into X=USV' and US gives the transformed dataset.

I found Jon Shlens paper a very good resource to understand this concept. 
https://arxiv.org/pdf/1404.1100.pdf

Feel free to comment about any mistakes or errors.
