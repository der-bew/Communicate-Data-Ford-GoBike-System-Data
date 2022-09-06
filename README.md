# Communicate Data: Ford GoBike System Data
## by (Derbew Felasman)


## Dataset

This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis which is as Capstone project part of the Udacity Data Analysis Nanodegree course and the data set I selected for this project is fordgobike_tripdata.csv. This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.
- The first part, Exploratory data visualization, I will use Python visualization libraries to systematically explore fordgobike_tripdata.csv dataset, starting from plots of single variables and building up to plots of multiple variables.
- The second part, Explanatory data visualization, I will produce a short presentation that illustrates interesting properties, trends, and relationships that I discovered in my fordgobike_tripdata.csv dataset. The primary method of conveying my findings will be through transforming my exploratory visualizations from the first part into polished, explanatory visualizations.

After cleaning the dataset it has 174952 rows and 20 columns (duration_sec, start_time, end_time, start_station_id, start_station_name, end_station_id, end_station_name, bike_id, user_type, member_birth_year, member_gender, start_date, start_hourofday, start_dayofweek, start_month, end_date, end_hourofday, end_dayofweek, end_month, and age ). The data type of the variables are 2 category, 2 datetime, 6 numerical, and 10 of them are object.


## Summary of Findings

> I observed that The most rides took about (100 - 1500) seconds, The majority of the user type are Subscribers but Customer bikers spend more time riding a bike in comparison of Subscribe bikers, 5 PM and 8 AM are the most busy hours, Males are more likley to bike (Males constitue the majority of the dataset by 74%, females constitue just 23%, and others constitue 2%) despite the fact that Others and females tend to spend more duration per a trip. In genral the multivariate exploration strengthened some of the patterns discovered in the previous bivariate exploration as well as univariate exploration, the relationship between the multiple variables plotted are visualized altogether and information are presented combined. 

## Key Insights for Presentation

> User type distributions: The majority of the user type are Subscribers almost 90.53% and Customer are only 9.47%. In order to do this I used a pie chart.
> Relationship between duration_sec and day of week: Tuesday to Friday are higher durations than other days. In order to do this I used a line plot.