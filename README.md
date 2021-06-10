# Cryptocurrencies
Use unsupervised machine learning to determine patterns in cryptocurrencies.
## Overview
The goal was to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system using unsupervised machine learning.
## Results
* An elbow curve was created using hvPlot to find the best value for K, which was 4.
  * ![kmeans_plot.png](https://github.com/RuthLD/Cryptocurrencies/blob/main/Resources/kmeans_plot.png)
* A 3D scatter plot was created using the Plotly Express scatter_3d() function to plot the three clusters.
  * ![3D_Scatter.png](https://github.com/RuthLD/Cryptocurrencies/blob/main/Resources/3D_Scatter.png)
* There are 532 tradable cryptocurrences.
* A scatter plot was created to show the relationship between Total Coin Supply and Total Coins Mined and the data is ordered by Class.
  * ![bokeh_plot.png](https://github.com/RuthLD/Cryptocurrencies/blob/main/Resources/bokeh_plot.png)
