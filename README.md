# Team-6-Dataset-Group-Project-2

Team 6 MIST 4610 Group Project 2
## Team Name:

21482 Group 6 

## Team Members:

Matthew Zimmerman [Mattyyzz](https://github.com/Mattyyzz)

Jordan Wheat [jordanwheat](https://github.com/jordanwheat)

Joe Song [JTR213](https://github.com/JTR21)

Zoe Lee [zoemk1](https://github.com/zoemkl)

Minjun Kim [MinjunKim1213](https://github.com/MinjunKim1213)

## Describing your dataset and what data it contains:
The dataset was obtained from https://catalog.data.gov/dataset. It contains records of property sales in the state of Connecticut from the year 2001-2021
The dataset contains the following columns.

1. Serial Number: A unique identifier for each entry.

2. List Year: The year the property sale was listed.

3. Date Recorded: The date when the sale transaction was recorded.

4. Town: The town where the property is located.

5. Address: The address of the property.

6. Assessed Value: The assessed value of the property for tax purposes.

7. Sale Amount: The amount for which the property was sold.

8. Sales Ratio: The ratio of the sale amount to the assessed value.

9. Property Type: Indicates whether the property is classified as residential, commercial, or vacant land.

10. Residential Type: Further specifies residential properties, such as single-family, condo, or two-family.

11. Non Use Code: Potentially a code indicating any non-standard use of the property.

12. Assessor Remarks: Remarks or notes from the assessor about the property.

13. OPM Remarks: Additional remarks or notes, possibly from another department or agency.

14. Location: The geographical coordinates of the property.

It contains various data types, including integers (for serial number, list year, assessed value, sale amount), dates (for date recorded), strings (for town, address, property type, residential type, assessor remarks, OPM remarks), floating-point numbers (for sales ratio), and geographical coordinates (for location).
Overall, this dataset provides comprehensive information on property sales, making it valuable for real estate analysis, tax assessment, and other related purposes.

## The 2 questions the team generated and why they are interesting and important:

1. Which year has the highest number of property sales? Which year had the lowest number of property sales?

The number of property sales is an important economic indicator. We decided to plot the number of property sales over all years in order to visually analyze which years seem to have the best sales versus which had the worst. Our team was interested in discovering which two years were the best/worst for sales to see if we could find an underlying pattern between those two years which may point to various events or trends that may have occured at that time.

2. When comparing the two years identified above, is there a difference between average assessed value, average sale amount, and average sales ratio that might explain the number of sales?

After identifying the best and worst year for the number of property sales, we wanted to see if there was any contrast between the assessed value and sales value of homes listed during those years. We also wanted to identify the difference in the average sales ratio of these years. Sales ratio is an adaptable metric determined by dividing the sale amount by the assessed value of a property. In combination with the previous knowledge of property sales, we can determine the impact of property sales on sales ratio. Whether sales ratio is increased during a point of property sales because of either increased assessment or a potential inverse where sale amount is lowered then assessed values because of economic downturn. From there, we can make estimates about economic factors by relating question 1 and 2, and determine if any of these variables possess a relationship.

## The manipulations applied to the data set as part of the analysis:
Some built in functions where used in Tableau such as COUNT DISTINCT(CNTD) and AVERAGE(AVG). We also utilized filters to narrow our display for Question 2, so only the data for years "2007" and "2020" was visualized.

## Analysis and Results:
Analyze and visualize the results of your analysis and describe the implications of your analysis.
Please provide any citations if required as well as supporting visualizations and analysis
generated from Tableau.

Graph 1:

  In this graph, we notice Connecticut residents struggling to gain purchasing power throughout the first decade of real estate transactions in the state. This can be the result of two factors: the Dot-com bubble burst and the relaxation of home-buying standards. Many loans were being extended to borrowers with poor credit histories throughout the early 2000s, which would end up affecting good-standing buyers as well in coming years because borrowers who initially got these loans would default and not repay lenders. 
  Along with the Dot-com bubble burst was the start of the Great Recession in 2007, which was also the year that the distinct count of serial numbers which represents the number of houses sold was the lowest in Connecticut. The decline in the housing market led to increased foreclosures, made it harder for borrowers to purchase their homes, and led to a decrease in sale price of homes as the economy became increasingly unstable. The Great Recession ended in 2009 and the graph shows a rising trend in the distinct count of serial numbers between 2007 and 2009 as the economy became more stable as well as the housing market and more houses began to sell and prices began to rise again. 
  We can notice a jump in the distinct count of serial numbers in 2020 because this is when the American government introduced stimulus checks to people as a result of the average American not being able to pay for common necessities. Americans who did not really need the stimulus checks may have found it worthwhile to take advantage of this extra money to begin a mortgage on a house during this stimulus check timeframe. So, we found the distinct count of serial numbers to reach a peak of 10,169 in 2020 for Connecticut and expect this observation to be similar in states across the country. 

<img width="1435" alt="PNG image" src="https://github.com/Mattyyzz/Team-6-Dataset-Group-Project-2/assets/150203797/c06c7cc0-c31b-47fa-8e33-9086fa727efd">

Graph 2:

  In this graph, we are analyzing three different factors related to our real estate sales data: average sale amount, average assessed value, and average sales ratio. As the average sale amount per house increases, we see a slight decrease in the average assessed value. This could be because property value was unable to get stronger in overall value throughout the sale of homes from 2007 to 2020. When consumers buy homes during this era, we can notice a limited market growth that does not give them appreciating power if they were to sell it. So, as consumers continue to buy homes over this time period, they may notice that the value they are getting in return of the sale amount is more negative than before. 
  The average sales ratio measures the average sale amount of a house as compared to its average assessed value. An overall downward trend is seen in the average sales ratio from 2007 to 2020 which typically indicates that demand is decreasing leading to a weakened housing market. This tells us that the houses are selling for less than their assessed values. This decrease in demand can be largely due to the state of the economy such as if it is unstable or there is an excess amount of homes for sale. The declining average sales ratio pushes the market closer towards a Buyer’s market which gives buyers more power to negotiate prices and can cause an overall drop in the average sale amount. 


<img width="1435" alt="PNG image" src="https://github.com/Mattyyzz/Team-6-Dataset-Group-Project-2/assets/150203797/152873eb-dea0-4867-920a-13d7d56790b5">

## Tableau Workbook
The workbook file can be found in the repository files. Please download the CSV data from the link provided in "Describing your dataset and what data it contains" section and connect the CSV file to the workbook. 

The packaged workbook can be found on ELC under our assignment submission.
