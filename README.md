# Kickstarting with Excel

## Overview of Project

### The purpose of this analysis is to determine outcomes of campaigns based on the goal amount for funding, and outcomes based on the time the campaign was launched. It is a resource that can be used to make informed decisions about when to launch a campaign and deciding goal funding amounts for a campaign.


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

#### I analyzed the outcomes of campaigns based on launch date by creating a pivot table to show the number of successful, failed, and canceled campaigns per each month of the year. Filters were applied to the pivot table to narrow the results to theater campaigns only. The pivot table was then used to create a line chart to visualize the outcomes over time. 

#### ![](Outcomes_by_Launch_Date_PivotTable.png)
#### ![](Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

#### Next, I analyzed the outcomes of play campaigns based on the goal funding amount by creating a new table from the data set. The table shows the number of successful, failed, and canceled campaigns within the play subcategory based on several different ranges of goal amounts. It shows the total number of projects for each range, and the percent of campaigns that were successful, failed, or canceled for each range. I used the COUNTIFS function (Microsoft, 2022) to calculate the number of campaigns based on outcome for each range, then calculated the total number of campaigns for each range, and calculated the percent of each outcome. 

#### ![](Outcomes_Based_on_Goals.png)

#### A line graph was created from this new table to show the percent of campaigns that were successful, failed, or canceled based on goal amounts.

#### ![](Outcomes_vs_Goal.png)

### Challenges and Difficulties Encountered

#### There were a few challenges to this analysis. One challenge was to ensure that the data set is filtered correctly. In the analysis of outcomes based on goals, I looked at campaigns in the play subcategory only, whereas the analysis of outcomes based on launch date looked at theater campaigns. Another challenge is that the COUNTIFS function was time consuming to write. It might have been simplified if the format of entries in the Goal column were mathematical expressions, instead of having to re-write the goal criteria within the COUNTIFS function.


## Results

#### From the analysis of outcomes based on launch date, we can conclude that the highest number of successful theater campaigns occurred in the month of May. Another conclusion is that relatively the same number of theater campaigns failed throughout the year, or in other words, there was no significant time of year when theater campaigns failed.

#### From the analysis of outcomes based on goals, one conclusion is that a higher percent of play campaigns were successful if the goal amount was less than $5,000. 

#### There are a few limitations to this analysis. One limitation is that the Kickstarter data set represents many countries in the northern hemisphere. The results show that campaigns are more successful in May, however if we assume that is because it is in the Spring, then someone who wants to launch a campaign in the southern hemisphere may need to do it at another time. Another limitation is that the outcomes based on launch date are a sum of 9 years of data, so there may be variations in outcomes from year to year. If the pivot table is filtered to only show one year at a time, then in certain months there is zero data, and it may be difficult to predict the outcome unless we have more data.

#### Future analysis could involve creating other tables and graphs and answering different questions. One possible graph could show outcomes based on goals for each month of the year. This would be similar to the current analysis, but could be filtered by each month to show what the outcomes were at a certain time. Another graph could show outcomes based on launch date for each country. This could help determine where the best location is to launch a campaign. 


## References

#### 1. Microsoft. (2022). *COUNTIFS function*. https://support.microsoft.com/en-us/office/countifs-function-dda3dc6e-f74e-4aee-88bc-aa8c2a866842?ns=excel&version=90&ui=en-us&rs=en-us&ad=us

