# Cryptocurrencies
## An analysis using unsupervised Machine Learning algorithm to discover unknown patterns.
![Cryptocurrency-Slang-Terms-You-Need-to-Know-Before-You-Invest-900x540](https://user-images.githubusercontent.com/103727169/194427438-04072e6c-7c21-438c-9a53-c090e617fd2d.jpg)

# Overview
The purpose of this analysis was to use data from [CryptoCompare](https://min-api.cryptocompare.com/data/all/coinlist) to provide a report and visualization of currently traded cryptocurrencies that can be grouped together to create a new classification system. This report would be used to help **Accountability Accounting** offer a new investment portfolio in the exciting world of cryptocurrency to its customers.

Since the data does not have any known outcome, we needed to preprocess it to fit an unsupervised `Machine Learning` model that will enable us to run a clustering algorithm that will allow us to group the cryptocurrencies.

In this analysis we learned and applied:

* **Data Preprocessing** (Selection, Transformation, Scaling) - the process of helping to prepare data for `Machine Learning` Algorithms.
* **Elbow Curve** - method to determine the best number of clusters needed for the algorithm to group the objects by.
* **Principal Component Analysis (`PCA`)** - statistical technique to speed up machine learning algorithms when the number of features is too high.
* **Clustering Algorithms(`KMeans`)** - the process of grouping similar objects/data points into clusters.
* **Visualization (`hvPlot`, `Plotly`)** - graphic libraries that allows us to create 2D and 3D graphs such as, scatter plots.

# Results

The original dataset contained 1,252 entries, however only 1,144 cryptocurrencies were currently trading. The data was further munged to remove `null values` and only leave cryptocurrencies that had a total number of mined coins greater than 0. The final results identified 532 tradable cryptocurrencies.

![Screenshot 2022-10-06 151814](https://user-images.githubusercontent.com/103727169/194429078-10068f27-00b7-420d-848c-68a2314e226f.png)
