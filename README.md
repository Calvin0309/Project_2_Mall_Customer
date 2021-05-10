# **[Project 2: Mall Customers clustering: Project Overview]** 

For this project, I will build a clustering model (unsupervised Machine Learning model) to identify the pattern of customers from a mall and group them into clusters accordingly. By this, I will also get a dependent variable from the result and can be used in further analysis using Supervised ML Model.

-2 models(K-Means clustering and Hieratchical clustering) are implemented to idenitify the customer patterns.

-In order to visualise the data cleary, I only pick up 2 independent variables (annual incomes and spending scores) so that the result can be shown in a 2D graph. 

-Different marketing strategy can be implement by the mall to maximize the profit and at the same time, doing their social responsibility. (eg: target the high annual income group, and protecting the low annual income group with high spending scores) 

## **Result:**

Both of the models give different results.

     Hierarchical clustering gives a better clustering as the clusters keep a good distance with each others (no overlapping).

I decided to pick the Hierarchical Clustering model.

*Dataset= Mall_Customers.csv*

*Code= Mall_Customers_KMeans_ML_Model.ipynb, Mall_Customers_Hierarchical_ML_Model.ipynb*


## **Resources** 

The dataset is collected from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Mall+Customers)
