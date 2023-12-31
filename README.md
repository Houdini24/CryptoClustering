# CryptoClustering
Module 19 Challenge
## Overview
In this challenge, I used my knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes. I used the StandardScaler module from scikit-learn to normalize the data from a CSV file.

The first five rows of the scaled DataFrame appeared as follows:

![](https://github.com/Houdini24/CryptoClustering/blob/main/Resources/Sample%20Data.png)

![](https://github.com/Houdini24/CryptoClustering/blob/main/Resources/DataFrame%20Plot.png)

## Analysis

1. What is the best value for k?
   * I believe that 4 is the best value for the original data based on the elbow curve in the graph below.

   ![](https://github.com/Houdini24/CryptoClustering/blob/main/Resources/Elbow%20Curve%20Original%20Data.png)
   
2. What is the total explained variance of the three principal components?
   * The first principal component explains approximately 37.20% of the total variance in the data. The second principal component explains around 34.70% of the total variance, and the third principal component explains about 17.60% of the total variance.

4. What is the best value for k when using the PCA data?
   * I believe that 4 is the best value for the PCA data based on the elbow curve in the graph below. This did not differ from the elbow curve in the original model.
     
   ![](https://github.com/Houdini24/CryptoClustering/blob/main/Resources/PCA%20Data%20Elbow%20Curve.png)

5. What is the impact of using fewer features to cluster the data using K-Means?
   * Using less features achieved a similar performance to the original model.
  

### Acknowledgements
I used the following resources to help complete this project:

* AskBCS Learning Assistants
* GitHub
* UCB Coding Bootcamp GitLab
* ChatGPT
* Bootcamp Tutor David Chao
* W3 Schools
