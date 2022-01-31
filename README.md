# Cryptocurrencies

### Purpose
We are to use unsupervised machine learning techniques to analyze cryptocurrency data. Through the exercise we will discover what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

### Accomplishment
* We have used **data preprocessing** to clean the data, remove null values and cryptocurrencies without coins mined. We also used "get_dummies()" for the text features and StandardScaler() to standardize and transform the data.
* We used **PCA** to reduce data dimensions.
* **K-means** to cluster the cryptocurrencies. We also used elbow curve to find the best value to cluster groups.
* We used 3D scatter to visualise the three PCAs: 
![image](https://user-images.githubusercontent.com/90880564/151887506-90d83680-981d-49a4-9b2d-ad7f544f0bb1.png)

* A 2D scatter plot to visualize "Total Coins Mined" vs. "Total Coin Supply" by coin name and clusters.
![image](https://user-images.githubusercontent.com/90880564/151887558-589b53dd-5bf1-47ee-9d7a-db423d70938d.png)

