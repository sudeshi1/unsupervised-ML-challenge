# Unsupervised Machine Learning Challenge - Cryptocurrency Clusters

![Unsupervised ML](/images/2.gif)

## Background

* A famous investment bank, one of a financial consultancy's clients, is interested in launching a new cryptocurrency investment portfolio to its consumers
* The company, however, is lost in the vast universe of cryptocurrencies
* Create a report that includes what cryptocurrencies are on the trading market and determine whether they can be grouped to create a classification system for this new 
investment

![Crypto](/images/1.gif)

## Requirements

1. Notebook: *Jupyter Notebook*
2. Scripting: *Python*
3. Libraries: *pandas, matplotlib, sklearn.preprocessing, sklearn.decomposition, sklearn.manifold, sklearn.cluster* 

## Accomplishments

#### Data Preparation

* Read in the CSV file
* Discard cryptocurrencies that are not being traded
* Filter for cryptocurrencies that have been mined
* Convert categorical data (*Algorithm*, *ProofType*) into numerical data
* Standardize the dataset

#### Dimensionality Reduction 

**PCA**

![PCA](/images/1.jpg)

**t-SNE**

![t-SNE](/images/2.jpg)

#### Cluster Analysis with k-Means

![k-Means](/images/3.jpg)

## Results/Conclusions

* The t-SNE and k-Means elbow plot indicate that the dataset does not include meaningful clusters
* There is not enough evidence to justify substantial clustering
* The elbow chart is trending downhill with no elbow point to offer a worthwhile selection value
* On the k-Means plot, the closest number is 6 but that elbow point is not stable and continues to trend downwards linearly

![?](/images/3.gif)