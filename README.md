# Unsupervised Machine Learning and Cryptocurrency

In this module we were tasked with using Unsupervised Machine Learning, in order to cluster different types of cryptocurrencies for investors looking to enter into the crypto-
market. We started with cleaning and reformatting the data source, keeping only the currencies that were actively being traded & mined. We then used the get_dummies method to
create variables out of the “Algorithm” and “ProofType'' columns. Following that we standardized the data with StandardScalers fit_transform() function, which gave us our 
dataframe. 
Next, we used Principal Component Analysis to reduce dimensions in our dataframe to three principal components. This dataframe was ran through the k-means algorithm, with
predictions being saved under the column name class. 
	Finally we created a simple scatter plot, as well as a 3d scatterplot to convey the data. 
