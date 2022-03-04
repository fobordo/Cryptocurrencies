# Cryptocurrencies Analysis

## Overview
Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, they asked us to create a report that includes what cryptocurrencies are on the trading market, and how they could be grouped to create a classification system for this new investment.

The [cryptocurrency data](/Resources/crypto_data.csv) used in this analysis was preprocessed to fit the machine learning models. Since there was no known output for what we were looking for, we decided to use unsupervised learning. To group the cryptocurrencies, we decided on a clustering algorithm. We used data visualizations to share our findings with the board. Using Python, Plotly, `StandardScaler`, `MinMaxScaler`, `PCA`, and `KMeans`, we were able to generate an Elbow Curve, as well as 2D and 3D Scatter Plots of the cryptocurrencies grouped into 4 clusters.

## Results

### Elbow Curve

Creating an elbow curve allowed us to find the best value for K, which was determined to be 4.
![Elbow Curve](/Resources/Images/elbow_curve.png)

### 3D Scatter Plot

The clusters were visualized in a 3D Scatter Plot.
![3D Scatter Plot](/Resources/Images/3d_scatter.png)

### 2D Scatter Plot

The clusters were visualized in a 2D Scatter Plot.
![2D Scatter Plot](/Resources/Images/2d_scatter.png)