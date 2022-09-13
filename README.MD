# Sales Dashboard: Project Overview

* Created a dashboard that present the summary of sales for a galvanized pipes trading company.
* Combined data from different files and extract data from text using Regex.
* Investigated several aspect that affect the sales and explained multiple parameters such as Pipe size and types.
  
## Code ENV

**Tableau:** 2019 V 2
**Python Version:** 3.9.2.
**Packages:** Pandas, Numpy.

## Data Cleaning and Features extraction

* Generalized all numbers to english numbers and categorized all expenses using text extraction from excel files
* Extracted important features that contribute in building beneficial dashboard such as Pipe size, type, sell price, sold quantities, price in other foreign currency, cost of product and net profit.
  
## Dashboard building

* Divided the dashboard into three slides: Sales, Profit and Volume.
* Calculated the overall performance metrics: Overall profit percentage, Payback period and total sales.
* Investigated sales considering day of the week, month, pipe size and type.
* Applied same consideration of sales to Profit and Volume.

## Productionization

In this step, I uploaded the dashboard to Tableau Public server and shared the link with the stakeholders.

## Insights

* Monday and Tuesday have 21%,19% Revenue of week days sales respectively, so avoid closing the store on these days.
* September and December have highest with 34.5 M, 32.5 M Revenue SDP respectively where July and January have lowest revenue with 10M and 0.72M respectively while not considering June and April due to incomplete months data.
* Normal type Sold sustainably than other types.
* AND 2.5-inch size have the less sold quantities and revenue between all sizes. However, 6-inch size frequently bought with other sizes where 2.5-inch normally bought alone so you could drop it from the store.
* Pipe with size 1 ,2 and 0.5 inches have highest sold quantities with more than 1500 pieces for each size.
* Pipe with 3 inches size has the highest revenue with 17.09 M SDP contributing by 9.8% of total revenues.
* All Pipe types other than normal have more than 200 % profit because there is no update for sell price for the hole year expect pipe with size 3 inches with type 3mm.
* ERP system such **ODOO** is required for the business to avoid missing data from text extraction. Also to monitor inventory to avoid running out of stock or stock imbalance.Since the inventory wasn't observed, the period where sales was low the reason is not fully clear due to stock shortage or other reasons.
* Sales in July and August are low due to raining season which should considered seriously because the season shift every year because of the climate change.
* Avoid selling huge amount of quantities during the increase of inflation rate because the buying process of the products take considerable time and local fees will be paid in last stages. So, the final cost will be higher that what had been sold with.

[Dashboard link!](https://public.tableau.com/views/Work_16623561475530/Dashboardmain?:language=en-US&:display_count=n&:origin=viz_share_link)