In this project, I'm analyzing cryptocurrency market data to explore how price changes over 24 hours and 7 days affect different coins. First, I'll load the data, clean it up, and check out some summary stats. Then, I’ll use StandardScaler to normalize the data so everything is on the same scale. After that, I’ll apply K-means clustering to group the cryptocurrencies based on their price movements. To find the best number of clusters, I’ll use the elbow method and plot the results.

Once I figure out the optimal number of clusters, I’ll fit the K-means model and predict which cluster each coin belongs to. I’ll visualize these clusters with a scatter plot to see how they look.

After that, I'll use Principal Component Analysis (PCA) to reduce the data to three main components, then rerun K-means clustering with this reduced data. I'll compare the clusters I get from the original data with the ones from the PCA data to see how using fewer features impacts the results. Lastly, I'll visualize and compare everything using some cool plots.