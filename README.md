# **Analyze AdventureWorks Using Power BI**

#### In this report, We will explain some analysis and predictions on the AdventureWorks database 2012.

![ad](https://user-images.githubusercontent.com/65326291/132260190-d5e1e56e-8581-4ec1-9260-22983002f36e.png)

###### AdventureWorks Dashboard


## **Introduction:**
AdventureWorks Database is a Microsoft product sample for an online transaction processing (OLTP) database. The AdventureWorks Database supports a fictitious, multinational manufacturing company called AdventureWorks Cycles.

## **Methodology:**
The data was cleaned and specific it to the small target to analyse.
Starting with some important analytic numbers that show AdventureWorks company:
1. Number of orders
2. Total SubTotal
3. Total Tax
4. Total Freight
5. Total Due

### **Number of orders by Ship Method:**

![bysh](https://user-images.githubusercontent.com/65326291/132260414-20e698ca-16d7-454c-a9a8-7023403bb79d.png)

That explain all ship methods were sufficient to deliver all orders.

### **Number of online - offline orders:**

![byon](https://user-images.githubusercontent.com/65326291/132260729-bbfd54c0-4a19-4e81-b3bc-58648956eb58.png)

This chart shows that the company had highly online orders until 2012 by (87.9%). Unlike offline orders in the same year (12.1%).So, the company increased its ship methods to cover all that online orders that were explained in the previous chart.

### **Number of orders by status:**

![bys](https://user-images.githubusercontent.com/65326291/132260990-387ee3bb-71d2-4140-b335-d54268ce3a2c.png)

The order status has many stages such as: (In process-Approved-Backordered-Rejected-Shipped-Cancelled). All orders in the company until 2012 were shipped successfully.

### **Top 10 Sales Person with number of orders and total subtotal achievements:**

![ad6](https://user-images.githubusercontent.com/65326291/132260867-4f44df78-0548-4353-a5b7-19c469b84b72.png)

### **Number of orders by Category, Sub Category, Product:**

![ad7](https://user-images.githubusercontent.com/65326291/132261001-95aaba35-ce57-43d3-a525-f493ae7db780.png)

It shows the products for each category with its number of orders. This helps us to know top product sales.

### **Number of orders and total due by territory:**

![te](https://user-images.githubusercontent.com/65326291/132261217-335bb248-2b6d-4bbc-9d28-52ddaaff9550.png)

This shows that the number of orders with total due was spread in North America, Europe and Australia.

### **Number of orders by order date, ship date and due date:**

![ad8](https://user-images.githubusercontent.com/65326291/132261226-7747c743-3806-4b30-901f-fd50c050c585.jpg)

It shows that orders came to increase in 2007. For more details about each order and its dates we use the tooltip page.

## **Resources:**

[AdventureWorks sample database](https://docs.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms).
