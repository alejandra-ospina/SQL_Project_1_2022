# SQL_Project_1_2022
Analyzing data from public data sets

## This is my subheader 

This is my SQL code:

#arrange Ids of people by descending value of total steps during their daily activities

1 SELECT ID, TotalSteps

2 FROM `first-sql-to-github1.kaggle_fitbit_data.dailyActivity_merged_table` 

3 ORDER BY TotalSteps DESC

#find IDs of the person with the maximum steps: 

4 SELECT Id

5 FROM `first-sql-to-github1.kaggle_fitbit_data.dailyActivity_merged_table`
 
6 WHERE TotalSteps= 36019

Row	Id	
1	1624580081