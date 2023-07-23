Overview:
This project with the knowledge of Python and Unsupervised Machine learning techniques we have predicted whether the cryptocurrencies are affected by 24-hour or 7 day price changes. 

Scope: 
In this report we have used sklearn library from python to scale/preprocessing the data, pandas for data manipulation and analysis, hvplot.pandas to create the interactive visualization, KMeans – algorithm to cluster the data and lastly Principal Component analysis to lower the dimension. 

Methodology:
Firstly, csv file has been loaded to read and load into the DataFrame, and the data has been plotted in line graph to visualize the original data patterns and structures.

Tasks Performed:
Computing the best value of K using the Original Scaled Dataframe:
Plotting the line graph representing the inertia values against the number of cluster. 
Elbow Curve:
![image](https://github.com/Bar89bas/CryptoClustering/assets/122665451/7c9698ab-4a39-4f1d-ba06-c22942fd61bc)
Looking at the elbow curve we can say that the optimal value for “K” is 8 and it can be said that going this value won’t reduce the inertia. 

Cluster Cryptocurrencies with K-means using the Original Scaled Data
Scatter Plot:

![image](https://github.com/Bar89bas/CryptoClustering/assets/122665451/5c2bc2ca-d191-4d7a-90e6-b4cb67fd0751)

Based on the scatter plot, we can conclude that the price of cryptocurrencies are highly affected by 24 hour price than 7 day price change as more datapoint fall on right-hand side of the graph. 

Optimize Clusters with Principal Component Analysis (PCA)
Dataframe after the dimension reduction – crypto currencies csv file
Reproducing the reduce- dimensionality of data.

![image](https://github.com/Bar89bas/CryptoClustering/assets/122665451/51c31778-8efb-4ed5-b7f2-a86ae4138c28)




