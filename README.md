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

## Snap of comparison between 2021-20222(using bar)
<img width="433" alt="Screenshot 2024-05-03 at 4 39 32 PM" src="https://github.com/rahil6218/PowerBI/assets/163023453/9e27b651-676d-478d-af36-134cac00e572">

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Remove all the null values and errors for the columns and to check error use filter option.
- Step 4 : After that make a conditonal column of the column i.e Vehicle type. Which has data that is car of any type which comes under car , all motorcycle above 500 cc and below 500 cc which comes under bikes and all mini bus and bus which come under Bus and all Good carrier of 5 tons or 3.5 tones comes under Good carriers
- Step 5 : Then close and save the filtered data to power bi.
- Step 6 : Then by using the line and stacked column chart represent the comparison between the casualties between 2021-2022 by putting on x-axis the accident_date column and on y-axis the number_of_casulties and on line axis the number of casualties.
- Step 7 : Then by using cards we represents the total number of type of casualties i.e fetal,serious,fatal,slight by placing accident severity in field.
- Step 8 : Then by using stacked bar chart we will compare the accident severity by putting accident severity on y-axis and Road type on x-axis.
- Step 9 : Then by using bar chart we calculated total number of casualties w.r.t to vehicle type by putting vehicle_type on x-axis and Number_of_casualties on y-axis.
- Step 10 : By using funnel chart we found the casualties by road surface condition by putting Road_surface_conditon in category and in value the Number_of_casualties.
- Step 11 : And by using pie chart we analyzed that how many number of accidents occur w.r.t to their road type. Putting Road_type in legend and Number_of_casualties in values. 
