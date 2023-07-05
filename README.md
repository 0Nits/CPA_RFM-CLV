# Customer Personality Analysis - RFM and CLV

Problem Statement:

Customer Personality Analysis is a detailed analysis of a company's ideal customers. It helps a business to better understand its customers and makes it easier for them to modify products according to the specific needs, behaviors and concerns of different types of customers.

Customer personality analysis helps a business to modify its product based on its target customers from different types of customer segments. For example, instead of spending money to market a new product to every customer (in the company's database, a company can analyze which customer segment is most likely to buy the product and then market the product only on that particular segment.

The main objective here is -
1. What people say about your product: what gives customers' attitude towards the product.
2. What people do: which reveals what people are doing rather than what they are saying about your product
</b><br/><br/>
<hr/>
<b>Person</b> <br/>
ID: Customer's unique identifier<br/>
Year_Birth: Customer's birth year<br/>
Education: Customer's education level<br/>
Marital_Status: Customer's marital status<br/>
Income: Customer's yearly household income<br/>
Kidhome: Number of children in customer's household<br/>
Teenhome: Number of teenagers in customer's household<br/>
Dt_Customer: Date of customer's enrollment with the company<br/>
Recency: Number of days since customer's last purchase<br/>
Complain: 1 if the customer complained in the last 2 years, 0 otherwise<br/><br/>
<b>Products</b>
<br/>
MntWines: Amount spent on wine in last 2 years<br/>
MntFruits: Amount spent on fruits in last 2 years<br/>
MntMeatProducts: Amount spent on meat in last 2 years<br/>
MntFishProducts: Amount spent on fish in last 2 years<br/>
MntSweetProducts: Amount spent on sweets in last 2 years<br/>
MntGoldProds: Amount spent on gold in last 2 years<br/><br/>
<b>Promotion</b>
<br/>
NumDealsPurchases: Number of purchases made with a discount<br/>
AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise<br/>
AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise<br/>
AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise<br/>
AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise<br/>
AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise<br/>
Response: 1 if customer accepted the offer in the last campaign, 0 otherwise<br/><br/>
<b>Place</b>

NumWebPurchases: Number of purchases made through the company’s website<br/>
NumCatalogPurchases: Number of purchases made using a catalogue<br/>
NumStorePurchases: Number of purchases made directly in stores<br/>
NumWebVisitsMonth: Number of visits to company’s website in the last month<br/>

<br><br>
<hr/>
<h4>Steps Followed: </h4> 
<b>
  1. Import Data and analyze or Describe data <br/>
  2. Reduce memory size of dataset . Then performed cleaning Data such as remove null <br/>
  3. Performed Dimensionalty Reduction , by merging two or more columns to one and removing unwanted columns<br/>
  4. Added new featured which were neccessary for my future visualiztion<br/>
  5. Created a RFM analysis on our dataset<br/>
  6. Done customer segmentation based on RFM Score<br/>
  7. Performed CLTV [Customer lifetime value]
</b>
<br/><br/>

![image](https://github.com/0Nits/CPA_RFM-CLV/assets/32134641/7d5f3dba-725e-4e1c-8746-e4c44de391c2)

