# Cryptocurrencies
Utilizing unsupervised machine learning to analyze cryptocurrency data.

## Overview
Data source: https://min-api.cryptocompare.com/data/all/coinlist<br>

Preprocessing: 
- only keep Cryptocurrencies that are currently being traded as well as have more than 0 coins mined
- convert categorical variables into indicator variables
- standardize features by removing the mean and scaling to unit variance
- reduce data dimenions with PCA to 3 principal components
- determine the best value for k-means clustering and run a model based on such
- visualize info with scatter plots and table
