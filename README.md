## Sales Analysis

Data analysis project completed using Pandas and Matplotlib to analyze and answer business questions about 12 months worth of sales data.

### Overview

The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.
Differrent tasks are completed as following

**Data Cleaning Process**
  - Drop NaN values from DataFrame
  - Removing rows based on a condition
  - Change the type of columns (to_numeric, to_datetime, astype)

**Data Exploration**

There are five high level business questions related to the data
   - What was the best month for sales? How much was earned that month?
   - What city sold the most product?
   - What time should we display advertisemens to maximize the likelihood of customer’s buying product?
   - What products are most often sold together?
   - What product sold the most? Why do you think it sold the most?

Different pandas and matplotlib methods are used to completed to answer these questions and visualize the results. Methods include:
  - Concatenating multiple csvs together to create a new DataFrame (pd.concat)
  - Adding columns
  - Parsing cells as strings to make new columns (.str)
  - Using the .apply() method
  - Using groupby to perform aggregate analysis
  - Plotting bar charts and lines graphs to visualize our results
  - Labeling our graphs



| | | |
|:-------------------------:|:-------------------------:|:-------------------------:|
|<img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="https://github.com/WiroonB/Sales-Analysis-Python/blob/main/Images/Q1BestMonth.png?raw=true"> Best Month for Sales |  <img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="https://github.com/WiroonB/Sales-Analysis-Python/blob/main/Images/Q2CityMostSold.png?raw=true"> The City Sold the Most Product | <img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="https://github.com/WiroonB/Sales-Analysis-Python/blob/main/Images/Q3BestTime.png?raw=true"> Best Time to Display Ads |
|<img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="https://github.com/WiroonB/Sales-Analysis-Python/blob/main/Images/Q4ProductSoldTogether.png?raw=true"> Most often Sold Together Products  |  <img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="https://github.com/WiroonB/Sales-Analysis-Python/blob/main/Images/Q5MostProductSold.png?raw=true"> Most Sold Product ||



