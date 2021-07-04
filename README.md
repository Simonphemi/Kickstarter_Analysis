# Kickstarting with Excel
Performing Analysis on Kickstarter Data with Excel to find trends

## Overview of Project
know how different campaigns fared in relation to their launch dates and their funding goals. We obtained kickstarter data and performed different types of analyses on the data to reach some relevant & valid conclusions.

### Purpose
Help Louise get information in setting up a fundraiser in attracting new investors

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Analysis was performed by comparing the data of the Outcomes against Launch-dates of the Theatre category. As that would be a good indicator of how invested people were at the initial date of release. The outcomes and launch dates were displayed on a line chart to show how effective each category was on different dates through the years 

### Analysis of Outcomes Based on Goals
  Analysis was done on the Percentage of outcomes in relation with the expected goal of the pledged amount from investors. Line chart were created for this analysis to give a visual representations. Our first approach was to compare the outcomes of all kickstarter under the “theatre” with the month of the year when they were launched. In order to perform this analysis, we filtered the data for theatre category and created a table which summarises the different outcomes of a campaign (successful, failed and cancelled) for each month of the year. 
![Theatre_Outcomes_Vs_Launch](https://user-images.githubusercontent.com/79813670/124402497-8f5d6a80-dcfe-11eb-904a-171d0feacce1.png)
  
  Our second approach was to compare the outcomes of all kickstarter campaigns under the sub-category “plays” and compare them with their goals. In order to do this, we filtered the data for plays sub-category and then created a table which summarises the different outcomes of a campaign (successful, failed and cancelled) for different ranges of goals. The goal ranges are segregated with an interval of $5,000. We then created a line chart to visualize the data
  ![Outcomes_Vs_Goals](https://user-images.githubusercontent.com/79813670/110271794-b5643f80-7f96-11eb-90e1-c0b800a12660.png)

### Challenges and Difficulties Encountered
  One of the challenges faced was to convert the raw dates of the campaigns into a format that could be easily understood. The launch dates, when extracted from kickstarter, were in the "unix" format which is unrecognizable in excel. However, we were able to convert them into readable formats using a functionality of excel.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. The month of May appears to be the most viable month in regards to achieving a successful campaign since may has the highest number of successful campaigns.
2. Based on this analysis, the month of May also appears to be the busiest month when it comes to campaign launches under the theater category. Over time, the month of May has the highest number of campaigns launched in a given month.

- The percentage of successful outcomes in relation with the pledge goals starts of high, however slowly declines as the donated amount rises towards the $50,000 mark
  Campaigns which have a target of 5,000 or less appear to be the most successful campaigns. The range 1,000 to 4,999 have the highest number of successful campaigns as well as a very close second, when comparing percentages.

- What are some limitations of this dataset?
  One limitation found is the dataset used to compare campaign outcomes with campaign start dates is the category used. The theater category was used but would have had a better result if we went further by select the plays sub-category.

- What are some other possible tables and/or graphs that we could create?
  We could take a subset of the successful campaigns for each goal range and compare the actual funds raised with the goal fund to be raised. We could use that to estimate the amount or percentage by which we are likely to exceed our goal for each goal range. This could be represented on bar charts and pivot tables



