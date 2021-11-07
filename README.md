# Customer-Segmentation
Customer Segmentation is the process of division of customer base into several groups called as customer segments such that each customer segment consists of customers who have similar characteristics.
The segmentation is based on the similarity in different ways that are relevant to marketing such as gender, age, interests, and miscellaneous spending habits.
The customer segmentation has the importance as it includes, the ability to modify the programs of market so that it is suitable to each of the customer segment, support in business decision; identification of products associated with each customer segment and to manage the demand and supply of that product; identifying and targeting the potential customer base, and predicting customer defection.

# Problem Statement
Customer Segmentation is a popular application of unsupervised learning. Using clustering, identify segments of customers to target the potential user base. They divide customers into groups according to common characteristics like gender, age, interests, and spending habits so they can market to each group effectively.
Use K-means clustering and also visualize the gender and age distributions. Then analyze their annual incomes and spending scores.

# Solution
The data set used consists of 5 attributes i.e. CustomerID, Age, Gender, Annual Income and Spending Score.
Upon proper visualization of the data, performing clustering between Annual Income and Spending Score seems the perfect fit.
After Implementing K – Means clustering on both the attributes, 5 discrete clusters can be seen clearly. The clustering can be seen in the next slide.

# Technology Used
Language used – Python
Version – 3.8.1

Libraries Used 
  1. Pandas (version – 1.1.3)
  2. Sklearn (version – 0.23.2)
  3. Matplotlib (version – 3.3.2)
  4. mpl_toolkit.mplot3d

# Methodology
Data set contains 200 entries representing data of 200 peoples and a total of 5 attributes.
After proper visualization of the data, clustering needs to be done. But, to perform clustering knowing the optimal number of clusters is necessary.
Elbow method is used to calculate the optimal number of clusters.
Once the number of cluster are calculated, all that is required is to implement the K – Means clustering algorithm and providing it with the cluster number and visualizing it

# Implementation
Using the methodology stated before, 4 different clusterings are performed i.e. between -
  1. Income and Spending Score
  2. Age and Income
  3. Age and Spending Score
  4. Age, Income and Spending Score

# Conclusion
 From the clustering performed between Annual Income and Spending Score, following conclusion can be drawn – 
      1.Red cluster shows people with less annual income and high yearly spend
      2.Green cluster shows people with high annual income as well as high yearly spend
      3.Blue cluster shows people with medium annual income and medium yearly spend
      4.Pink cluster shows people with less annual income as well as less annual spend
      5.Cyan cluster represents people with high annual income and less annual spend.
We can conclude that, people belonging to Pink and Cyan cluster are Frugal in nature and people belonging to Red and Green cluster spends money a lot. The Blue cluster belongs to middle class people with average income and expenditure. We can also say that Green and Cyan cluster people belongs to high class due to their high annual income and Pink and Red cluster people belongs to a relatively low class due to their low annual income.

