# Recommendation_system_association_rule
#### Association Rule (ARL)

Association rules are normally written like this: {Diapers} -> {Beer} which means that there is a strong relationship between 
customers that purchased diapers and also purchased beer in the same transaction. An association rule has two parts: an antecedent 
(if) and a consequent (then). An antecedent is an item found within the data. A consequent is an item found in combination with the antecedent. 
In the above example, the {Diaper} is the antecedent and the {Beer} is the consequent.

### Story of the dataset

The dataset includes the sales of an online store between 2009 and 2011.

#### Variables

Invoice — Invoice Number “If this code starts with C, it means that the operation has been cancelled..”
StockCode — Product code “Unique number for each product.” 
Description — Product Description
Quantity — Number of products purchased
InvoiceDate — Invoice Date
Price — Unit price(Sterling)
CustomerID - Unique number for each customer
Country — Name of the country 

##### recommend_item()
This function recommends items based on association rule
