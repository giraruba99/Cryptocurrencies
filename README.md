# Cryptocurrencies
## Purpose and Overview
   * The main purpose of this analysis is to determine the status of trading among different cryptocurrencies using unsupervised machine learning techniques. If followed correctly, unsupervised machine learning is very effective method when there is no known output for what we are expecting.
   * To group different cryptocurrencies to a cluster/classification, that way we can determine which ones are safe to invest on.

## Results and Analysis
   
   * Preprocessing the Data for PCA
   - In this step of the analysis, we were able to load the raw data to be processed and cleaning. Without clean data, we cannot correctly do our predictions using unsupervised machine learning. Thus, we were able to check and drop null values. We also standardized our data using the `get_dummies` and `SatadardScaler` methods.

   - A clean DataFrame is created for further analysis.

   * Reducing Data Dimensions Using PCA
   - In this step, we used PCA to reduce the DataFrame dimensions just to three principal components. Out of the above created clean DataFrame, we were able to create a new DataFrame for our further analysis.

   * Clustering Cryptocurrencies Using K-Means
   - Clustering is one of the important steps in unsupervised machine learning. Using the K-means algorism, we were able to predict the K clusters for cryptocurrency data, based on which we can make very important investment strategy.
   - In this step, we also created an elbow curve that gave us a way to do the clustering of cryptocurrencies.

   * Visualization
   - Visualizing an analyzed data is one of the greatest ways a data scientist can summarize his/her work in very meaningful, but also easier way.
   - In this step, we were able to display our data in both 2D and 3D data that refers `Total Coins Mined` and `Total Coin Supply`. 

   ## Conclusion
   - In this analysis, we were able to cluster our unpredicted cryptocurrency data and gave us a way to take a data driven decisions on future investment. Since we never had any idea on possible outcomes or input data, we used unsupervised machine learning techniques to classify cryptocurrencies based on some shared traits. While cryptocurrency trading is still very volatile investment and will continue to be volatile, we at least determined unsupervised machine learning is an awesome method to give ample information to an investor in taking data informed business decisions.