# Kickstarter-Analysis
Performing analysis on Kickstarter data to uncover trends.
# Kickstarting with Excel

## Overview of Project
- The overview of this project is to find out the correlation of goal amount/launch date, to the success of a project specified by Category, "Theater" and Subcategory, "Plays"

### Purpose
-find out the correlation of goal amount/launch date, to the success of a project specified by Subcategory, "Plays"

## Analysis and Challenges
-Analysis performed, taking results for 'Theater' by month and pivoting the results into 'successful, Failed, Canceled' subsections - to find the total amount of projects under the "Theater" Category. After doing this, a potential challenge would be to ensure the proper columns/rows are selected for a pivot table. Next, we calculate results for subcategory based on the same criteria regarding "Success, Failure, Cancelation." and goal amount needed for respective 'Play' - Potential challenges with this portion of analysis, would be if there is not enough data to correlate amount to success rate. 


### Analysis of Outcomes Based on Launch Date
- Overall, it is clearly shown that the 'Theater' Category is most popular during the month of May. However, the data shows that there is a major positive spike from April to May, almost a 50% increase in success rate from April to May. The provided data also shows the linear decline post May. June, July, August, September, each have an approximate 20% decrease per month. Comparing May to September, there is a 60% decrease in success rate. 


### Analysis of Outcomes Based on Goals
-Regarding the success rate based on needed goal, it is proven that a lesser goal amount has a much higher success to failure ratio starting with less than 1000, there is an approximate 3:1 ratio of success to failure rate. Moving to 1000 to 4999, there is a similar an approximate 3:1 Success:Failure ratio. Moving to the next set of data, the ratio jumps significantly to be an approximate 2:1 ratio. Once getting to the 10000-35000 range, the ratio turns into Failure:success - More failures for each success. However, an oddity occurs once we reach the 35000-45000 range of data, where success becomes higher than failures - This may be due to the smaller amount of projects total in this portion of the dataset.
  

### Challenges and Difficulties Encountered
- Primary challenges were ensuring the data is properly set and formulas are properly written for accurate data analysis. 
- Minor challenges were the inclusion of data that has little to no information correlation to it.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
- The first conclusion is that the best time to launch a project for theater is during the month of May as the success rate is ~66% 
- The next conlcusion to be drawn is the fact that the months after May have a linear decline of ~20% per month up to September, where after, the success to fail rate ratio gets closer together.

- What can you conclude about the Outcomes based on Goals?
-Firstly, the lower amount of money a 'play' needs, the more likely it is to succeed. Also, a majority of the data is based on a lower goal amount needed. 

- What are some limitations of this dataset?
- The majority of the data for 'Theater' and 'plays' is based on a lower necessary goal amount, and that under the 'Play' subcategory, there were 0 Canceled projects.

- What are some other possible tables and/or graphs that we could create?
- We could also study the pledged amount vs goal amount - the backer amount to goal amount - the average donation per backer - the date started vs success rate
