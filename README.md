## CryptoClustering
Homework 19 for the unsupervised machine learning module of Datavis bootcamp

## Project Description
In this challenge, you’ll use your knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes. The project analyzes the impact of using fewer features on clustering the data using K-means. Comparing the clustering results of the original data and the PCA data helps to understand the effect of dimensionality reduction on the clustering process.

**Installation**
- Clone this repo and save it in your local directory
- git clone `https://github.com/priyajainnyc/CryptoClustering`
- Open the repo in a code editor to see the codes used to clean and merge the data from the Citi Bike Data webpage within the following Jupyter file 'Crypto_Clustering_starter_code.ipynb', and export the following csv data file 'crypto_market_data.csv' under the Resources folder within the repo.

**Dependencies**
- Python
- Pandas
- NumPy
- Scikit-learn
- HoloViews Plots

## Analysis
**In this challenge, the following was accomplished:**
* Crypto market data was given as a csv file, then normalized and coverted to a DataFrame
  
  ![scaled_data](https://github.com/priyajainnyc/CryptoClustering/blob/main/Resources/scaled_data.png)
  
* The best value for k was found using the original scaled DataFrame
  
  ![elbow_plot](https://github.com/priyajainnyc/CryptoClustering/blob/main/Resources/elbow_plot.png)
  
* The cryptocurrencies were clustered with K-means using the original scaled data
  
  ![market_scaled_plot](https://github.com/priyajainnyc/CryptoClustering/blob/main/Resources/market_scaled_plot.png)
  
* The clusters were optimized with Principal Component Analysis (PCA)
  
  <img width="295" alt="image" src="https://github.com/priyajainnyc/CryptoClustering/blob/main/Resources/pca_data.png">
  
* The best value for k was found using the PCA data
  
  ![elbow_pca_plot](https://github.com/priyajainnyc/CryptoClustering/blob/main/Resources/elbow_pca_plot.png)
  
* The Cryptocurrencies were clustered with K-means using the PCA data
  
  ![market_pca_plot](https://github.com/priyajainnyc/CryptoClustering/blob/main/Resources/market_pca_plot.png)
  
## Conclusions
After visually analyzing the cluster analysis results, we determined the impact of using fewer features to cluster the data using K-Means. We found that with fewer features used to cluster data using K-means, it seemed to reduce the amount of noise in the clusters and made the grouping of the data more clear and interpretable.
