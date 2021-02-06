# Cryptocurrencies Analysis Using Unsupervised Machine Learning

## Project Overview

In this project unsupervised clustering algorithm is used to categorise cryptocurrencies from the ```crypto_data.csv``` which is retrieved from 
[CryptoCompare](https://www.cryptocompare.com/) website.

The coins are categorized based on :
- Coin Name 
- Algorithm
- Total Coins Mined 
- Total Coin Supply


Raw csv data is filtered to retrieve: 

- Cryptocurrencies that are being traded and have a working algorithm.
- Remove rows that have at least one null value
- DataFrame that has only rows where coins have been mined.

Finally a new DataFrame is created that holds the cryptocurrency names.

## Results

### Data with dummy variables for Algorithm and ProofType using get_dummies() method

![Data using get_dummies().png](https://github.com/smj452/Cryptocurrencies/blob/main/Resources/Data%20using%20get_dummies().png)

### Data reducing to 3 principal features using PCA model
![Data using PCA.png](https://github.com/smj452/Cryptocurrencies/blob/main/Resources/Data%20using%20PCA.png)


### Clustering Crytocurrencies Using K-Means

**Best Value for k Using the Elbow Curve**

![elbow curve.png](https://github.com/smj452/Cryptocurrencies/blob/main/Resources/elbow%20curve.png)

**HVPlot with different coin classes**

![HVPlot.png](https://github.com/smj452/Cryptocurrencies/blob/main/Resources/HVPlot.png)

**Scatter Plot of the coins based on the clustered classes**

![Scatter Plot.png](https://github.com/smj452/Cryptocurrencies/blob/main/Resources/Scatter%20Plot.png)
