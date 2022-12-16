# Cryptocurrencies
Demonstrating the Power of Unsupervised Machine Learning
<BR><BR>
## Purpose
Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. I created a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.
<BR><BR>
## Data Preparation
I preprocessed the data to prepare it for for dimension reduction and clustering
<br>
• Data was retrieved from <a href="https://min-api.cryptocompare.com/data/all/coinlist" target=”_blank”>CryptoCompare</a>
<BR>
• Filtered the DataFrame & dropped columns not needed and removed null values
<BR>
• Created a new DataFrame that holds only the cryptocurrency names
<BR>
<img src="https://github.com/meggrooms/Cryptocurrencies/blob/main/images/new_dataframe.png" height=400>
<BR><BR>
## Reducing Data Dimensions Using PCA
• Applied PCA to reduce the dimensions to three principal components
<br>
<img src="https://github.com/meggrooms/Cryptocurrencies/blob/main/images/PCA_pc.png" height=400>
<BR><BR>
## Clustering Cryptocurrencies Using K-means
• Created an elbow curve to determine the best value for K
<BR>
• Used the K-means algorithm to predict the K clusters for the cryptocurrencies’ data.
<br>
• Edited the DataFrame as necessary to reflect the required information
<Br><BR>
## Visualizing Cryptocurrencies Results
