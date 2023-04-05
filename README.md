# Cryptocurrency Classification

## Overview

Cryptocurrency data is analyzed to gain insight on the classification of the different currencies available on the market. With no clear output, the following analysis employs the use of unsupervised machine learning techniques through scikit-learn in Python with application of K-Means clustering and Principal Component Analysis (PCA). 

The order of analysis includes the following: 
- Preprocessing the data using Pandas in Python
- Using scikit-learn's PCA algorithm to reduce data dimensions
- Creating an elbow curve to determine the best K value for K-Means
- Visualization of results

The original data set is from [CryptoCompare](https://min-api.cryptocompare.com/data/all/coinlist), utilized as [crypto_data.csv](/resources/crypto_data.csv). 

## Results and Summary

Following the processing and algorithm output and upon charting each cryptocurrency via principal components, the following graph is developed: 

![3D Plot](/screenshots/3dplot.png)

In following processing the general supply of each cryptocurrency, a scatter plot was created: 
![Chart 2](/screenshots/Chart2.png)

While the scope of this analysis isn't to provide formal recommendations on which or any to invest in, this is something that can be given to the client's financial team to support further research. The first figure may help with decisionmaking regarding portfolio diversification, with the second figure giving a slice of the information through the specific parameters at hand. 