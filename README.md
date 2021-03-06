# Customer_Segmentation

In this project, we will analyze a dataset that describes the **customer order summary** of a **Food Delivery business**. One of the objectives of this project is to describe the variations in different types of customers that use the app and hence segment the customers into useful categories. Doing so would help the Food Delivery Service structure their services and business strategies(personalization) by making use of the relevant insights. The dataset can be found in the same directory- **customer_order_summary.xlsx**

**Steps Involved:**
-  **Data Cleaning and Wrangling**: Dealing with missing and invalid values. Outlier detection and removal
-  **Data Exploration**: Data distribution visualizations using correlation and scatter matrix
-  **Feature Engineering**: Creating new derived features. Feature scaling using natural logarithm to overcome skewness
-  **Feature Selection**: Removing redundant features using observations and linear regressions
-  **Dimensionality Reduction**: PCA to visualize data in 2 dimensions
-  **Clustering**: Using Kmeans and Gaussian Mixture Models to find the optimum number of clusters for the dataset

**Cluster Visualise**
<img src="./cluster_visualize.png" alt="Final Output"/>

-  **Data Recovery**: Performing inverse transform on the predicted segmented examples to get the actual segmented examples


**Recoverd data Sample**
<img src="./clusters_result.png" alt="Final Output"/>

-  **Conclusions and Implications**: Discussion about how could this information be used by the company to maximize profit and recover lost customers

Please read the note book for information about the data and implementation of classifiers used.

[Notebook](https://github.com/utkarshut/ML-Projects/blob/master/Customer%20Segmentation/customer_segmentation.ipynb)





