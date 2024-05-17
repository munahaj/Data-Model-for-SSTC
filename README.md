# Data-Model-for-SSTC
In this project, we created a data model and Power BI report for Seven Sages Tea Company (SSTC) that combines information from all over the company. The CFO is eager to get some help translating all the disjointed sales files and product records into something usable so that they can help the owners make sense of what is generating not only sales but profitability. We are aiming for this data model to make it possible for the company's CFO to quickly review and analyze which tea beverages sell well and which ones generate the highest profitability, and to know which selling point (Referred to in this report as Customer type) has the highest sales and the Gross profit margin.

Important notes:
- It is already established that the flagship tea beverage, Bamboo Grove Tea is the company's biggest seller. However, with the way the data is collected in-house, they are not even sure whether all the products are generating a profit at this stage.
- Seven Sages teas are sold in Washington State (USD) and British Columbia (CAD), so there's a currency consideration as well.
- The company runs on a fiscal calendar (Begins on October 1st and runs until September 30th).

Below screenshot is the summary of the final submitted report:

![Untitled](https://github.com/munahaj/Data-Model-for-SSTC/assets/169274166/31952794-f045-41a8-92a1-213a46591161)

# Project/Report:
After combining and cleaning the data, we went ahead with creating a date table to accommodite to their fiscal year which included columuns for Calendar year, month name and number, Fiscal year, Fiscal quarter and Fiscal period.

![Untitled](https://github.com/munahaj/Data-Model-for-SSTC/assets/169274166/9b430ef4-5bdb-4526-99c7-e150b39d3d8e)

Table relationships has been established for the Model View:

![Untitled](https://github.com/munahaj/Data-Model-for-SSTC/assets/169274166/074a8e0a-5d8e-4bb8-ab0a-949a4ce03585)

After calculating the total Sales (In USD and CAD), Cost of Sales and Gross Profit Margin, we created a visualized table to summarize the output of our data model for the CFO. The basic version of this report  have two tabs, one summarizing sales by customer and customer type across quarters. The second table  summarizes the unit sales by product and percentages of gross profit by Product.

![Untitled](https://github.com/munahaj/Data-Model-for-SSTC/assets/169274166/4c517aef-8ae6-444f-a289-b8d39458feab)

With this report we were able to conclude that the product with the generates the highest profit compared to sales is (Han Dynasty Spiced Tea) with total Sales of USD 6840.00 (CAD 9105.4) and with a gross profit margin of 37.98% and Gross profit by Product of 10.53%.

![Untitled](https://github.com/munahaj/Data-Model-for-SSTC/assets/169274166/906f6b8a-f76f-4deb-8828-d9c5a2dd08d3)

 Meanwhile their bigger seller beverage, the Bamboo Grove Tea, has generated sales of more than USD 69K (CAD 93K) however the gross profit margin is only at 11.18%.
 
![Untitled](https://github.com/munahaj/Data-Model-for-SSTC/assets/169274166/32f38c90-fb08-428c-a405-2caeb1579c9c)

Below notes regarding the customer types were shared with the CFO in the report:
- Customer with the Highest Sale - Distributor
- Customer with the Highest GPM for FY - SSTC Restaurant
- Customer with the 2nd Highest Sale - Grocery Store
- Customer with the Highest 2d GPM for FY - Grocery Store

 # Further Insights
- Imperial Poet Tea beverage has generated great sales however the GPM is also low compared to the sales. It is also noted that the beverage is a seasonal drink as the analysis show there is a sales ression of the sold quantity between the month period of May 2021 and August 2021.

![Untitled](https://github.com/munahaj/Data-Model-for-SSTC/assets/169274166/db5333e0-8a90-400d-930b-418962000bdd)

- Although the gross profit margin for Liu Ling's Black Tea is high compared to the total sales, however the gross profit by product percentage is lower compared to the Unit sold by product.

![Untitled](https://github.com/munahaj/Data-Model-for-SSTC/assets/169274166/7b99cceb-a5e5-4cf2-bc68-72eb430dcf86)

