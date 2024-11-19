# myntra-project
Myntra is a leading Indian fashion e-commerce company known for its wide range of clothing, accessories, and lifestyle products.
While Myntra is recognized primarily for fashion, this dataset relates to the company's online retail operations for Myntra Gifts Ltd., 
a UK-based division specializing in unique all-occasion giftware. This dataset spans transactions from December 1, 2009, to December 9, 2011,
and includes detailed records of sales made through Myntra Gifts Ltd.’s non-store online platform.
The dataset provides a thorough snapshot of the company's international online retail activities during this period.
Problem Description:
In this case study, your task is to identify major customer segments on a transactional data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.
Data Description:
Attribute Information:
InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
Description: Product (item) name. Nominal.
Quantity: The quantities of each product (item) per transaction. Numeric.
InvoiceDate: Invoice Date and time. Numeric, the day and time when each transaction was generated.
UnitPrice: Unit price. Numeric, Product price per unit in sterling.
CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
Country: Country name. Nominal, the name of the country where each customer resides.

![th](https://github.com/user-attachments/assets/f632a62b-df2e-4989-bee4-a584da0c5838)
![th](https://github.com/user-attachments/assets/9e77c15c-3a0c-476a-9c00-8d88e785d468)
Myntra was founded in 2007 by Mukesh Bansal, Ashutosh Lawania, and Vineet Saxena as a venture to sell personalized gifts. However, in 2010, the company shifted its focus to retailing branded apparel, and the rest, as they say, is history. Myntra made strategic tie-ups with famous brands and started retailing their latest and top-selling merchandise. The company soon expanded its portfolio to include international and high-end brands and ventured into the lifestyle section. Today, Myntra sells over 500 Indian and international brands, making it a one-stop-shop for fashion-conscious Indians.
Interpretation:
Cluster 0:

Recency: High (average around 165 days)
Frequency: Low (average around 15 transactions)
Monetary: Low (average around $286)
Interpretation: Customers in this cluster are likely to be 'At-Risk' or 'Lapsed' customers. They haven't made purchases recently, and when they did, they didn't do so very frequently and didn't spend much. These customers might have been one-time buyers or occasional shoppers. Engaging them with reactivation campaigns or exploring why they haven’t returned can be a strategic move.
Cluster 1:

Recency: Very Low (average around 11 days)
Frequency: Very High (average around 259 transactions)
Monetary: Very High (average around $5933)
Interpretation: This cluster represents your 'Champions' or 'Loyal' customers. They shop frequently, recently, and spend the most. They are the most valuable segment, likely to respond positively to new offers, up-sell and cross-sell opportunities. Maintaining their high engagement level is crucial, and they can also be targeted for feedback or as brand ambassadors.
Cluster 2:

Recency: Moderate (average around 68 days)
Frequency: Moderate (average around 69 transactions)
Monetary: Moderate (average around $1200)
Interpretation: Customers in this cluster can be seen as 'Potential Loyalists' or 'Promising' customers. They have a balanced score in all three RFM metrics. These customers have the potential to become more valuable if properly engaged. Tailored marketing strategies, loyalty programs, and incentives to increase their purchase frequency and value can be effective.
Hurrah! You have successfully completed your Machine Learning Capstone Project !!!

