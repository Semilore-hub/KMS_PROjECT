# Kultra Mega Stores (KMS) Inventory Anlysis Report
## Prepared By:
## BAMIGBOYE OLUWASEMILORE DEBORAH 
### DURATION: 2009 -2012

## COMPANY BACKGROUND
 KMS stores is a lagos base company specializing in office supplie and funiture.
The Bussiness servers as a broad range off customers, including consumers, small businesses, and large corporate clients across Nigeria.
This Analysis Focuses on sales and operations data from the Abuja division between 2009 and 2012.

## PROJECT OVERVIEW
To provide actionable insights and recommendations by analysing order data and shipping trends. The dataset was examined using SQL (in SSMS) and excel Pivot Tables)
To answer 11 key business questions
## TOOLS USED
-  Microsoft SQL server Management(SSMS)
-  Microsoft Excel (Tables, Pivot Tables e.t.c.
-  Data cleaning (excel)
-  Data Importation & joins (SQL)
## Task summary and findings
 **Task 1**: Which Product category had the Highest sales?
 ! [Task 1](Images/task1_ Highest_Category.png)
   -  Query:Agregated sales by  Product category
   -  Result: Technology generated the highest sales
   -  Insight: Technology are strong revenue drivers- bundling
 and cross_ promotion can enhance this

## **Task 2**:  Top & bottom 3 regions by sales
 ! [ task 2](images/task 2_ top and bottom 3 region sales.png)
   - Query: ranked sales by region
   - Bottom 3 regions: **Nunavut, North west territories, yukon**
   - Top 3 regions: **Ontairo,Praire, Atlantic**
   - Insights: Marketing focus should increase in underperforming regions
## **Task 3**: Total Appliances sales in Ontairo    
  -  Query: Filtered for Product Sub Category= 'appliances' and Province = 'Ontiaro'
  -  Result: Appliance sales In Ontiro returned Null.But in the excel shhet i worked on it was 20000+
  -  Inight: theee is modest performance here_ could improve through promotions or bundling
## **Task 4** Bottom 10 customers by sales
  ! [Task 4](Images/task 4_ bottom 10 customers by sales)
  -  Query: ranked customers by total sales( ascending).
  -  Insight: Loyalty programs and discount can help increase retention and sales from these low- performing customers

## ** Task 5**: Highest shipping cost  by mode
   ! [Task 5](Images/task 5_Highest shipping cost by mode)
   -  Query: Summed Shipping Cost by Ship Mode.
   -  Result: Delivery truck by 51,972 was the most expensive
   -  Insight shipping Priority cost_effetive option for low priority
     
## ** Task6**: Most valuable customer and what they buy
   ! [Task 6](Images/task 6_ Most valuable customer)
   -  Query: Top 10 customers by total sales.
   -  Valuanle customer: **Emily Phan** was the most valuable customer 
   -  Product Bought: technology
   -  Insight: these customers are crucial_ offerthe, personalized services or premium support
## ** Task 7**: Small business customer with highest sales
  ! [Download](Images Task 7_ Small business customer)
   - Query: filtered by customer segment = ' small Business'
   - Result: One standout small business customer generated the most sales by **DENNIS KANE**
   -  Insight:  They are a good candidate for long term business engagement
## ** Task 8**: Most avtive customers( 2009-2012)
 ! [Download](Images Task 8_ Most Active customer)
   _  Query: couunted (Order ID) per corporate customers, filtered by year
  -  Result: One customer Placed the most order  **ROY SKARIYA**
  -  Insight: Consider Loyalty contracts or exclusive deals
## **Task 9**: Most profitable consumer customer
[download](Image task 9_ Most Profitable consumer customer)
  -  Query: Filtered for consumer segmnt and sorted by total profit
  -  Result: A single customer stood out as most profitable By **EMILY PHAN**
  -  Insight: THis customer could be offered referral bonnuses or early access to new products
## **Task 10** Returned itmes & segment
[download](Image task 10_ Returned items and segment)
  -  Query: joined Order status table to find returned items
  -  Insight: Most returend came from the **consumer segment, Corporate segment, Home Office segment**. This Indicates Potential issues with product Understanding or expectations. Recommenend Improving [re_ scale product clarity and return policies
##  Task 11**: Shipping Cost Vs Order Priority
[download](Image task 11_ Shipping Cost Vs Or![Uploading shipping mode and shipping cost.png…]()
der Priority)
 - Query: Analysed Shipping method against order priority.
 - Insight: While high priority orders were often shipped via Delievery truck. some low priority orders also  used it, increasing cost unnecessarily, Recommend stricter shipping policy enforcement.

   
    
  
 
