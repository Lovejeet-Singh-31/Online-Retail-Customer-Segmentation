# Online-Retail-Customer-Segmentation
![image](https://user-images.githubusercontent.com/104754645/204095336-a7917000-c853-402f-8c74-b3faac0f95c5.png)
# 📖PROBLEM STATEMENT
### In this project, our task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.
# 📖Dataset Discription
* InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
* StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
* Description: Product (item) name. Nominal.
* Quantity: The quantities of each product (item) per transaction. Numeric.
* InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
* UnitPrice: Unit price. Numeric, Product price per unit in sterling.
* CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
* Country: Country name. Nominal, the name of the country where each customer resides.
# 📖ALGORITHMS USED:
I. KMEANS-SILHOUTTE SCORE, ELBOW METHOD
II. HIERARCHICAL CLUSTERING-AGGLOMERATIVE
# 📖CONCLUSION:
* The Top 3 products are white hanging T-Light Holder, Regency cake stand 3 tier and Jumbo Bag red retro spot.
* Top 3  rarely sold product are Blue felt heart flower, Glass cake cover and Cracked glaze earrings red.
* The most Frequent Customer Id is 17841.
* United Kingdom has highest number of customers on the other hand Saudi Arabia has the least number of customers.
* In the Month of November, the sales are very high and in the month of February sales are very low as compered to others.
* The sales are very high on Thursday. 
* At afternoon, the sales count is very high.
* We Found 38 observation which are Anomaly.
* The Silhouette Score on data Frequency and Monetary we get 0.47 which is higher among the all.
* We get Optimal number of cluster are 2 using Elbow method, Silhouette score and dendrogram for all models.
* We can say that our unsupervised model is ready to deploy to solve business problem.
# 📋 Execution Instruction
The given IPython Notebook can be either downloaded to be run on your local Jupyter Notebook or can be directly run on Google Colab.
📜 Credits
