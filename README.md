# Cryptocurrencies Analysis
![Cryptocurrency-](https://user-images.githubusercontent.com/36451701/139772328-3f1d9036-2170-4394-ab51-8ca37e5bbb51.jpg)


##  Cryptocurrencies Analysis Project Overview:
*Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. To help them, a report will be created that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.*

*The original data we will be working with is not ideal, so it will need to be processed to fit the machine learning models. Since there is no known output for what we are  looking for, we have decided to use unsupervised learning.*


### Technicals used in this project to classify cryptocurrencies:
- Preprocessed data for model using pandas and sklearn library to standardize features
- Reduced data dimensions using Principal Component Analysis (PCA)
- Performed clustering using K-Means
- Visualized results in 2-D and 3-D using hvplot

### Deliverables:
- Deliverable 1: Preprocessing the Data for PCA
- Deliverable 2: Reducing Data Dimensions Using PCA
- Deliverable 3: Clustering Cryptocurrencies Using K-means
- Deliverable 4: Visualizing Cryptocurrencies Results

### Project Resources:
Data Sources:
     - [crypto_data.csv](https://github.com/DSupps/Cryptocurrencies/blob/main/Resources/crypto_data.csv)

Software:
- Jupyter Notebook 6.1.4
- Python 3.8.5
     
  
## Cryptocurrencies Analysis Project Results:

### Clustering Crytocurrencies Using K-Means:
The number of clusters needed was unknown, so to find the best number an Elbow Curve was plotted using hvPlot.

![elbow_curve_2](https://user-images.githubusercontent.com/36451701/130334995-7179d5dc-f5f4-4079-bf56-4004fd5fb54a.png)
- The best value for k is clearly 4.
- 4 clusters can confidently be used in the K-Means model.

### Visualizing Cryptocurrencies Results:
Using the PCA algorithm with three principal components and knowledge of creating scatter plots with Plotly Express and hvplot, four distinct clusters of cryptocurrencies were visualized in 3-D. 

![3d_scatter_deliverable_4_only](https://user-images.githubusercontent.com/36451701/130335173-cc1c7815-17d1-467d-8b99-0d11fa055651.png)

### Tradable Cryptocurrencies Table:
A table with the tradable cryptocurrencies was created using hvplot.

![Tradable_Cryptocurrencies_Table](https://user-images.githubusercontent.com/36451701/130335227-52ad1028-4b3e-4ac7-b5df-62e4b9c4e41c.png)

### 2-D TotalCoinsMined vs TotalCoinSupply:
A scatter plot was created with TotalCoinsMinted on the x-axis and TotalCoinSupply on the y-axis the shows the CoinName when you hover over the data point.

![TotalCoinMined_vs_TotalCoinSupply](https://user-images.githubusercontent.com/36451701/130335269-adfcc66f-f50f-4537-82b1-38471284d9be.png)
- This plot in 2-D does not show a clear seperation in the four clusters.

## Cryptocurrencies Analysis Project Summary:
Based on this analysis we have discovered that there are 532 tradable currencies on the market and they can be divided into four different classification groups. -

- This was done by David Supple
