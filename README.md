# Data-Model-for-SSTC
In this project, we created a data model and Power BI report for Seven Sages Tea Company (SSTC) that combines information from all over the company. The CFO is eager to get some help translating all the disjointed sales files and product records into something usable so that they can help the owners make sense of what is generating not only sales but profitability. We are aiming for this data model to make it possible for the company's CFO to quickly review and analyze which tea beverages sell well and which ones generate the highest profitability.

Important notes:
- It is already established that the flagship tea beverage, Bamboo Grove Tea is the company's biggest seller. However, with the way the data is collected in-house, they are not even sure whether all the products are generating a profit at this stage.
- Seven Sages teas are sold in Washington State (USD) and British Columbia (CAD), so there's a currency consideration as well.
- The company runs on a fiscal calendar (Begins on October 1st and runs until September 30th).

Below screenshot is the summary of the final submitted report:
![Untitled](https://github.com/munahaj/Data-Model-for-SSTC/assets/169274166/754bf699-5e80-4e9d-88f3-e86cac4ea6bc)

# Project/Report:
After combuning and cleaning the data, we went ahead with creating a date table to accommodite to their fiscal year which included columuns for Calendar year, month name and number, Fiscal year, Fiscal quarter and Fiscal period.

![Untitled](https://github.com/munahaj/Data-Model-for-SSTC/assets/169274166/9b430ef4-5bdb-4526-99c7-e150b39d3d8e)

Table relationships has been established for the Model View:

![Untitled](https://github.com/munahaj/Data-Model-for-SSTC/assets/169274166/074a8e0a-5d8e-4bb8-ab0a-949a4ce03585)

After calculating the total Sales (In USD and CAD), Cost of Sales and Gross Profit Margin, we created a visualized table to summarize the output of our data model for the CFO. The basic version of this report  have two tabs, one summarizing sales by customer and customer type across quarters. The second table  summarizes the percentages of gross profit and unit sales by product.

![Untitled](https://github.com/munahaj/Data-Model-for-SSTC/assets/169274166/4c517aef-8ae6-444f-a289-b8d39458feab)




