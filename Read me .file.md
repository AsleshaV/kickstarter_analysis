# Kickstarting with Excel



## Overview of Project
kick starter data set shows the data related to different campaigns which funds the creative projects in various countries. Using Excel, we analysed the given data for studying the outcomes trends related to theaters and plays and using the results we finally created pivot chart images for data visualization.
### Purpose
The main objective for this analysis is to understand how different Campaigns performed in comparision to their launch dates and funding goals for theaters and plays category.
## Analysis and Challenges
 Initially The Kickstarter dataset needed to be further breakdown into little more detail from category column to new columns,theaters and palys to conduct more detailed analysis. The data from dataset is analysed creating new columns using different functions from Excel such as applying filters , sorting the data and using formulas to get the values needed for creating pivot tables. Then pivot charts were created using results from pivot tables to visualize the trends for the campaign.

 

### Analysis of Outcomes Based on Launch Date
TO analyse the outcomes based on launch date, First, In the Kickstarter dataset a new column “years” was created, by extracting the year from the “date created conversion” column. Next, a pivot table was created with the entire data set, the fields were customised by applying filters with “parent category” and “years,” rows with dates and years from “date created conversion” and columns to values with “outcomes”. After setting up these fields, the pivot chart is created and further filtered to show only outcomes from succesful, failed and canceled campaigns, removing  live campaigns. The rows were modified to show the months of the year and parent category to show data for “theater” only. A line chart was created from the pivot table data to show the trends in theater campaign outcomes based on their launch date.


### Analysis of Outcomes Based on Goals
First, the percentage of successful, failed and canceled plays were analysed, in order to analyse the outcomes based on funding goals. A pivot table was created to get the outcomes based on funding goals, which are further divided into ranges, from less than $1,000 up to greater than $50,000. The COUNTIFS function was then applied to get the number of successful, failed and canceled campaigns based on their respective funding goals. Then, Using this data, the total number of successful, failed and canceled projects were calculated by using the SUM function.Later, the percentage of successful, failed and canceled projects were calculated in a new column. A line chart was then created using the resultant data from the pivot table to visualize the trends based on funding goals.

### Challenges and Difficulties Encountered
There are certain challenges during this data analysis and visualization like reading the huge amount of data from data set was difficult. Another challenge was we needed to use lot of fuctions in Excel to get the data required for analysing the trends by applying filters,formulas,sorting,creating new columns. Using formulas such as countifs was difficult based on given values. we need to verify the data with the dataset for making sure it is right one. Before creating pivot table, it is reqiured to know which data elements might be needed and creating them accordingly.  while creating pivot tables another challenge is using appropriate filters in columns, rows and values field to get the data for visualising the right data .sometimes it was misleading until we cross verify with the data from dataset back and forth.




## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
By analysing the data in the outcomes based on Launch date, May had the highest success rate and followed by June. October to December had gradual decline in success rate with relatively increase in failed campaigns.

- What can you conclude about the Outcomes based on Goals?
It can be concluded that the success rate is higher for campaigns with a funding goal less than $5,000. Campaigns with high funding goals showed less success rate with more failures.

- What are some limitations of this dataset?
Lack of data in the dataset for theaters and palys during certain years is the major limitation. data inputs during 2009 for theater category is not available and showed higher inputs in 2014 making it less reliable.Including data from other crowding funding sources to better visualize the success rate of theaters and palys would be helpful.

- What are some other possible tables and/or graphs that we could create?
there is a possiblity to compare how the duration of a campaign impacts its outcome.The outcomes for successful, failed, and cancelled projects can be obtained by subtracting the launch date from the deadline, and the resultant data can be used to create pivot tables and line graph.
