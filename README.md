# Shopping Sales Analysis

![](/images/title_image.jpg)

## Problem Statement
The marketing department of a store aims to launch a campaign in the second quarter of 2024. However, they require a dashboard to monitor business activity during the waiting period. This will provide insights into where to channel the campaign efforts. The Marketing lead would like to track various metrics over time, including product performance, changes in customers' choice of color, location, and seasonality patterns in relation to orders. Additionally, any other metric(s) deemed necessary should be incorporated into the dashboard.

## Data Source
The dataset used for this analaysis is the 'Shopping_data.csv'. It contains all the information related to purhcase that were made by each customer

## Aim
The aim of this project is to build a dashboard that will track various metrics over time in order to help in campaign decision making. 

## Objectives
-	To determine the highest selling products
-	To identify the order pattern due to changes in seasons
-	To determine which locations are ordering most products
-	To determine the taste of customers in terms of colours
-	To build a dashboard that will include summarise the metrics

## Tools Utilized
- Microsoft Excel 
  - Data cleaning – for cleaning the data and making it ready for analysis. 
  - Analysis – using pivot tables to summarise key results
  - Report – creating dashboard for key metrics

## Data Cleaning
This phase was crucial for the project's success. Data cleaning ensures that the data is free of errors, duplicates, outliers, and other issues that could affect the analysis. The following data cleaning steps were carried out:
-	Applied filters to easily help in inspecting the data for any spelling errors etc..
-	Duplicates were removed
-	Missing values in the colour column were filled with “Unknown.” This was the best way to handle the missing value because the colours were supposed to be there, but due to supposed errors in data entry, they were not entered. In order to solve this, the data analyst can ask the store for the values then the correct colours can be inputted in the data.
-	Two outliers were found and eliminated. The outliers were in the age column (Ages of 280 and 3100). These ages are unrealistic in the real world. Perhaps it was due to errors/mistake while entering the data. They were eliminated because the two outliers are insignificant in a large dataset of 3911 values. 
-	Wrong characters were found and replaced.

## Results and Discussion
|Figure 1: A Bar chat showing 10 most ordered products|Figure 2: A column chart showing customers colour preferences|
|------------------------------------------------------|-------------------------------------------------------------|
![](/images/top_products.png) | ![](/images/customer_colour.png)
The most products that are being ordered are Jewellery, blouse, and pants which all had a total of 171 orders.|Customers prefer olive colour most, 175 people ordered olive coloured products. 

|Figure 3: A line chart showing seasonality changes in orders|Figure 4: A bar chart showing the locations that ordered most|
|------------------------------------------------------|-------------------------------------------------------------|
![](/images/order_pattern.png) | ![](/images/location.png)
There is a decreasing general trend in changes in orders due to changes in seasons. However, customers order most during spring season.|Most orders are coming from customers based in Montana and California, having a total orders of 96 and 95 respectively.

## Recommendation
From the findings, the following actions are recommended to the marketing department so that they can channel their campaign efforts to in order to maximise sales:
* The marketing department should sell more of a  mixture of jewellery, blouse, and pants because they had the most sales. These products should be in olive colour since it is the most prefered colour by both gender on average. Morever, these products should be sold during the spring season because they have most sales and preferably shoulf channel more campaign efforts in Montana and California because they are the two locations that are generating  most sales. 

## Limitations
The following were the limitations of the  project:
* There were missing data in the colour column hence they had to be filled with "Unknown"
* There were duplicates and outliers that had to be elimiated.

## References
* The visual used for the title was taken from [https://www.skillsyouneed.com/rhubarb/save-money-clothing.html]
