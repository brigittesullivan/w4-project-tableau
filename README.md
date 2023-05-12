# Final-Project-Tableau

## Project/Goals
(fill in your description and goals here)
Conduct an analysis of the Canadian housing market over the past 70 years. Using the following data sources:
* weekly earnings
* consumer price index
* housing price index
* housing and commercial prices 
* housing and commercial benchmarks

For my presentation, I will focus on how the following economic indicators changed (or were changed) by major financial crises (dot com bubble, black Monday, etc..)


## Process
### (your step 1)
### (your step 2)

1. import data into Tableau, json was difficult, creating necessary relationships between 
2. review high-level data in each table (Exploratory Data Analysis
3. work through all tasks in the assignment 
4. re-import missing housing data,


## Results
(Fill in which Option you chose, either 1 or 2. List the dataset you selected for the project if you selected Option 2. Also, discuss the visualizations you created, and why. For Option 2, also identify what your data question was, and how you went through the prompts.)

Selected option 1 - Canadian Housing Market Data, See tableau workbook file. 

New Housing constructions were most reactive to economic crises, whereas earnings saw the least variance and had a steady increase over time. 

Question 9 : 
If the data is clustered first then a regression is performed, and predictability increases

## Challenges 
(discuss challenges you faced in the project)
1. Data Access 
    - missing housing price index data meant that I started on analysis before having all the data, this created a disorganized network of connections in Tableau. This caused issues during analysis since there was no way to clean the data source relationships without losing previous work. I did not have the time to re-do the charts so decided to work with the disorganized data set.
    - did not have 2002 data for item # 7, so used 2005 data instead for the comparison.
2. Creating proper relationships in Tableau 
3. updating data types from DateTime to date. The obvious method didn't work even after several attempts, which also created relationship issues. in the end, the date time feature had to be converted to a string, trimmed, then converted to a date type for Tableau to accept a date-based relationship on this item. 
4. Importing Json into Tableau took several attempts using Tableau and Python. In the end, I used Python to create a data frame of the required data, exported it to CSV then imported the CSV into Tableau 


## Future Goals
(what would you do if you had more time?)
1. investigate other items not listed to find patterns. Investigate why CPI has a significant increase in the '80s (is this a data quality issue?)
2. Improve the interactivity /elegance of the charts. I would have liked users to be able to select multiple metrics of interest across data sources. 
3. For question 9, perform clustering then re-run regression only on some clusters to find a stronger model. 
4. Re-set the data connections and relationships in a clear organized way that does not create issues when you go to use multiple data sources. 
