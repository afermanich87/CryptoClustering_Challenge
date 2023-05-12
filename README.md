# CryptoClustering_Challenge


## Intro

1. This challenge utilizes newly gained knowledge of unsupervised machine learning. 
2. Download the challenge 19 files and import the `crypto_market_data.csv`(found in the `Resources` folder). 
3. Use the StandardScaler() module from scikit-learn to normalize the data from the CSV file.
4. Create a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.
    * The first five rows of the scaled DataFrame should appear as follows:
  
![image](https://github.com/afermanich87/CryptoClustering_Challenge/assets/120151717/fda54894-19eb-4757-a3a8-180b55757188)

## Find the Best Value for k Using the Original Scaled DataFrame

* Use the elbow method to find the best value for k.
* Plot a line chart with all the inertia values computed with the different values of k to visually identify the optimal value for k.
* Answer the following question in your notebook: What is the best value for k?

## Cluster Cryptocurrencies with K-means Using the Original Scaled Data

* Cluster the cryptocurrencies for the best value for k on the original scaled data.
* Create a scatter plot using hvPlot.


## Optimize Clusters with Principal Component Analysis

* Using the original scaled DataFrame, perform a PCA and reduce the features to three principal components.
* Retrieve the explained variance to determine how much information can be attributed to each principal component. 
* Answer the following question in your notebook: What is the total explained variance of the three principal components?
* Create a new DataFrame with the PCA data. The first five rows of the PCA DataFrame should appear as follows:

![image](https://github.com/afermanich87/CryptoClustering_Challenge/assets/120151717/1b89cfeb-a163-4dde-8885-6e12d1b9bf57)


## Find the Best Value for k Using the PCA Data

* Use the elbow method on the PCA data to find the best value for k.
* Plot a line chart with all the inertia values computed with the different values of k to visually identify the optimal value for k.
* Answer the following questions in your notebook: 
    1. What is the best value for k when using the PCA data?
    2. Does it differ from the best k value found using the original data?


## Cluster Cryptocurrencies with K-means Using the PCA Data

* Cluster the cryptocurrencies for the best value for k on the PCA data.
* Create a scatter plot using hvPlot.
* Answer the following question in your notebook: What is the impact of using fewer features to cluster the data using K-Means?


## Conclusion

* All plots created in the Jupyter Notebook `Crypto_Clustering.ipynb` were saved to the `Final_Results` folder for comparison and analysis.
* I used previous activities from module 19 to guide me through pieces of the KMeans and PCA data analysis. 
* I used hvplot documentation to help with saving my plots as `.png` image files.





