# create a machine learning (unsupervised) model that groups cryptocurrencies. 
## The purpose is to assemble investment portfolios that are based on the profitability of those cryptocurrencies


### CryptoClustering

this is the output of the challenge 19


1) content 
create a machine learning model that groups 40 cryptocurrencies. 
The purpose will be to assemble investment portfolios that are based on the profitability of those cryptocurrencies observed during different set of time 

price_change_percentage_24h', 'price_change_percentage_7d',
       'price_change_percentage_14d', 'price_change_percentage_30d',
       'price_change_percentage_60d', 'price_change_percentage_200d',
       'price_change_percentage_1y'

the analyse will be done with the original data and with use of Principal Component Analysis (PCA) method

2) Dependencies
        import pandas as pd
        import hvplot.pandas
        from sklearn.cluster import KMeans
        from sklearn.decomposition import PCA
        from sklearn.preprocessing import StandardScaler


3) directory organization
- jupiter notebook (Crypto_Clustering_mywork.ipynb) t run and execute the code
- resources directory with the CSV data file
- directory Starter_code : contains the original input




