## Customers Segmentation by Kmeans

### Table of Contents

1. [Project Overview and Motivation](#motivation)
2. [File Descriptions](#files)
3. [Installation](#installation)
4. [Results](#results)


## Project Motivation<a name="motivation"></a>
Customers are important to the survival and success of any business because they are the source of the revenue. The success of a business is the ability to satisfy customers and make them happy, and therefore turn a profit from them. To achieve a business success, the business has to find the right potential customers. 
Using customers’ data can help to build models for predicting the future behaviors of the customers and targeting customers who  help the business to make more money. 

In this project, I will analyze a mall customers’ dataset to answer the following question:
1. Who is the customers we should target?

To answer this question, I will build a K-means clustering model to group the customers by their characteristics. This grouping is to understand each segment and target the right customers to let them stay with the business.

## File Descriptions <a name="files"></a>
- One notebook file `Customers_Segmentation_by_Kmeans.ipynb` which contains the code. 
- One csv file `Mall_Customers.csv` which contains the customer dataset. The dataset is avilable in [Kaggle](https://www.kaggle.com/shwetabh123/mall-customers) website.
	
## Installation <a name="installation"></a>
All libraries are avilable in Anaconda distribution of Python.  The code should run using Python versions 3.*.
 
## Results<a name="results"></a>
There are five type of cluster which are:
* Cluster 0: medium sending score and medium annual income.
* Cluster 1: low spending score and high annual income.
* Cluster 2: low sending score and low annual income.
* Cluster 3: high sending score and low annual income.
* Cluster 4: high spending score and high annual income.


Customers data clustering help us to understand the customers’ characteristics. Here are some suggestion for each cluster:
1. The customers in clusters 0, who have medium annual incomes and medium spending scores, can be attractive by marketing campaigns.
2. The customers in clusters 1, who have low annual incomes and low spending scores, are usually older than 35 years. So, we need to the find a way to attract old customers for example special offers for the products that they usually buy it, and investigate the causes of the low spending scores.
3. The customers in clusters 2, who have high annual incomes and low spending scores, are usually males or old females. So, we need to the find a way to attract them customers for example special offers for the products that they usually buy it, and investigate the causes of the low spending scores.
4. The customers in clusters 3, who have low annual incomes and high spending scores, are special customer because their incomes are low and spending scores are high. We should to keep these customers by designing a loyalty programs which offers discounts to the members.
5. The customers in clusters 4, who have high annual incomes and high spending scores, are the most valuable customers. We should keep these customers by appropriate pricing or special offers. 
From the clustering we found that, the customers in cluster 3 and cluster 4 are usually female who are between the ages of 20 and 30 years old. So, to obtain new customers, we can fouces on female who are between 20 and 30 in the advertising campaign. 


