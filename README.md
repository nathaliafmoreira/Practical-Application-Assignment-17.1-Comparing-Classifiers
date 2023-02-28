# Practical-Application-Assignment-17.1-Comparing-Classifiers
Comparing Classifiers

This practical application consists in compare the performance of different classifiers: K Nearest Neighbor, Logistic Regression, Decision Trees, and Support Vector Machines. 

It was used a dataset related to marketing bank products offered by telephone.
The dataset collected is related to 17 campaigns that occured between May 2008 and November 2010.
No feature from the dataset has null values. Categorical values were converted to numeric and some categories classified as unknown (which would look like a null value) were discarded. The target was converted to numeric too.

The main objective of this analysis is to improve the conversion rate of the marketing campaign, more accurately identifying the audience with the greatest potential to adhere to the product.

The model that performed best was Logistic Regression, with the best training time vs accuracy.
To try to improve the performance of the model, new features were included (campaigns and duration).

The Logistic Regression model continued to be the best model, it presented a better accuracy with the inclusion of new features.
The decision tree, using the new features and the Grid Search CV, presented a better performance when compared to a simple decision tree, but could not overcome the Logistic Regression

As next steps, to improve this classification model, we could test other variables and other techniques such as Ensemble Techniques and Neural Networks.
As a recommendation, it would be interesting to raise other characteristics of the clients, such as investment profile: if the client has other investments or not and what are the characteristics of these investments (is this client's profile a conservative or risky investor?). 
