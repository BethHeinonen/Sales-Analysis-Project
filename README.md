# General Sales Insights

Short exercise evaluating a year of sales.

Do to the size of the Dataset the finds were far faster and easier to read with Tableau, however, it is a good practice to work in both platforms to reinforce which platform works best when you have "X" data. I plan to add an SQL/MySQL work up as well with a breakdown within Excel to show the pros / cons of each or at the every least to show what is possible with each platform.

### Data Source

https://github.com/KeithGalli/Pandas-Data-Science-Tasks

Code to recreate the dataset is included in the Sales_Data_csv. If you are not intrested in cloning the original repo.

Additionally futher chart breakdowns and an interactive chart that lets you filter information by Month/ Product/ City can be found on my Tableau Public 
https://public.tableau.com/profile/beth.heinonen

To see the code in a Jupyter Notebook(ipynb) click on the Full Work Analysis folder
or click here https://github.com/BethHeinonen/Sales-Analysis-Project/blob/main/Full%20Work%20Analysis.ipynb


### Data Description
This is from a created dataset that has no operational expenses included. 
The random creation of fake "Purchase Address"s removes the ability to compare "stores" to evaluate individual preformance. One year of sales records also removes any instights of trends or sales preditions of the project.

There are 186,305 sales records across 10 cities for 19 products. Prices of the products range from $2.99 - $1,700. There are 140,787 separate "store" locations with only 31.7% of locations that have more than one sale. 

### Project Goal
The main goals for the analysis is to find general insights on a city level and identify trends if any.
* Top grossing City
* Top grossing product
* Best selling Month
* Best selling Hours

# Findings

### General 
Total Sale across all location reached **$34,331,640.00**

San Francisco, CA performed the best for the year, **$8+ M** 

Port Land, ME performed the worst for the year with **$447,000**

Average Yearly Sales landed at **$3.4 M**  


<img width="993" alt="Product by City" src="https://user-images.githubusercontent.com/66493323/111655866-601efe00-87e0-11eb-8424-c22a965c245e.png">


#### Best Selling Month

December **$4.5 M** followed by October **$3.7 M** and April **$3.3 M**

Q4 had the best sales, as to be expected for holiday shopping. Smaller spikes are seen where typical graduation months fall (April / May) 

<img width="965" alt="Monthly Preformance" src="https://user-images.githubusercontent.com/66493323/111655926-6dd48380-87e0-11eb-8476-b134a8835a16.png">


#### Best Selling Hours across the cities peaked at 11a- 1pm and 6pm - 8pm

These are standard lunch rush and post work shopping timeframes. 

<img width="1211" alt="Time of day" src="https://user-images.githubusercontent.com/66493323/111656034-8a70bb80-87e0-11eb-8e65-4d1a31fcbdcb.png">

#### Orders Broken Down By City
This chart can be easier to read for pin pointing how much of a difference there is between some of the cities.
Quanitites for the orders differ drastically across the cities. The Grand Totals are sums of the Product orders shown on the right side and Grand Total sums by city run along the bottom. All Grand Totals are for the year.

<img width="825" alt="Order Quantites" src="https://user-images.githubusercontent.com/66493323/111658068-67470b80-87e2-11eb-816b-da0474c45691.png">


# Conclusion

More data(operational cost) would be needed to make a better analysis as to how profitable a City / Location truly is. 

Based on what we have
* Portland, ME could be shutdown or at the very least put on a PIP with a year to improve 
* Additional locations should be added in
* San Francisco, Los Angeles, New York, Boston (MA) in that order
* Additional marketing in spike months / before spike to drive sales higher
* Add bundle packages for products sold together
* look into product expanion 




