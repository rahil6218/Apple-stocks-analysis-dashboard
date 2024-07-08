# Apple-stocks-analysis-dashboard 
## Overview

This Power BI Dashboard provides an in-depth analysis of Apple Stocks , used a spectrum of visuals including cards, line charts,stacked column chart,area chart,tables. 📉
This dashboard showing the high, open, low, close and date filter for specific date

## Tools
Microsoft PowerBI [DOWNLOAD](https://www.microsoft.com/en-us/download/details.aspx?id=58494)

## Features

- Stock Metrics: Display key stock data such as high, open, low, and close prices.
- Date Filter: Enable users to filter stock data by specific dates for detailed analysis.
- Interactive Visualizations: Utilize area charts, line charts, tables, and cards to present stock information intuitively.
- Trend Analysis: Analyze the stock's performance over different periods to identify trends and patterns.


## Visualizations

- Cards: Show key metrics such as the latest high, open, low, and close prices.
- Date Filter: Allow users to filter data by selecting specific dates.
- Area Charts: Visualize the stock's performance over time, highlighting the area under the curve.
- Line Charts: Show trends in stock prices over time with precise data points as per quarter and months.
- Tables: Present detailed stock data in a tabular format for easy comparison and analysis.

## Data Sources
The data used in this dashboard is sourced from historical stock records of Apple Inc. Ensure that the data is clean and accurate before uploading it to Power BI using power query editor.

## Snap of total number of open. (using Card)
![applestocks img_page-0001](https://github.com/rahil6218/Apple-stocks-analysis-dashboard/assets/163023453/b9f8b9cd-70de-4325-8e6c-55d25728ac02)
## Snap of sum of high and low by month.(using line chart)
![applestocks img_page-0001-2](https://github.com/rahil6218/Apple-stocks-analysis-dashboard/assets/163023453/c1ee4623-82e2-4d8c-a2d3-80fb162f85ca)

## Snap of table (using table)
![applestocks img_page-0001-2](https://github.com/rahil6218/Apple-stocks-analysis-dashboard/assets/163023453/363de685-8277-46fb-be3d-bb7d04a0c71e)


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Remove all the null values and errors for the columns and to check error use filter option.
- Step 4 : Save and exit back to the power bi in which the visualization is to be done.
- Step 5 : Use cards for representing the sum of open, low, high, and close by putting the open, low , close, and high column in fields in each card.
- Step 6 : Then by using the line chart we represented the sum of high and low by quaters by putting on X-axis the Quaters and on Y-axis and secondary y-axis the sum_of_high and sum_of_low.
- Step 7 : Then by using the stacked column charts we represented the sum of open and close by year by putting year in X-axis and sum of open and close in y-axis.
- Step 8 : Then by using table we represented all the data in tabular form for the quick and specific view in which in column section we put all the column i.e sum of open,close,high ,low 
