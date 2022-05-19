# Cluster analysis in customer segmentation

When analyzing a large amount of data, the problem that the data on the objects of observation are not connected and structured, but are only "thrown" into the database, often arises. The most commonly used mathematical-statistical method for classifying objects into groups of similar characteristics is cluster analysis.

This project focuses on cluster analysis through application in market segmentation. The database is taken from the Kaggle  site and contains data on supermarket customers, obtained on the basis of their membership cards. It consists of 200 observations, i.e. customers, with 5 variables: CustomerID, Gender, Age, Annual Income ($ 000) and Spending Score (1-100), i.e. the value assigned to the customer based on data on purchasing behavior.

![image](https://user-images.githubusercontent.com/99446425/169404186-8269f9b8-498b-4a0b-89af-be23c277bb47.png)


Through this project I managed to develop and improve my skills of data visualization in Python, as well in Tableau. I've successfully conducted cluster analysis and came up with following results and conclusions:

I have decided that the number of cluster should be 4, after conducting elbow method and silhouette analysis. With k-means I got next results

![image](https://user-images.githubusercontent.com/99446425/169404426-2fb1479b-76d2-47d2-80cc-90a90457faba.png)

From the graph we can see our 4 clusters:

-Brown cluster consisting of young customers which have high values of spending score and high values of annual income
-Blue cluster consisting also of young customers with mid-high values of spending score, but low annual income
-Green cluster consisting of older clients with mid values of spending score and low-mid annual income
-Purple cluster consisting of persons with mid-high age, low spending score and high annual income


Data taken from:
https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

Tableau file available in repository.

Public Tableau visualization link:
https://public.tableau.com/views/Customers_16527237121710/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link
