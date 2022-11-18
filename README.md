# Airbnb Analysis
### Michael Capparelli

## Problem Statement:

This dataset describes the listing activity of homestays in New York City: https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata

The purpose of this notebook is to demonstrate efficient and accurate data cleaning skills maximizing the amount of data I can use. Once the data is cleaned, exploratory data analysis is performed.

## Background

Airbnb, Inc is an American company that operates an online marketplace for lodging, primarily homestays for vacation rentals, and tourism activities. Based in San Francisco, California, the platform is accessible via website and mobile app. Airbnb does not own any of the listed properties; instead, it profits by receiving commission from each booking. The company was founded in 2008. Airbnb is a shortened version of its original name, AirBedandBreakfast.com.

Since 2008, guests and hosts have used Airbnb to travel in a more unique, personalized way. As part of the Airbnb Inside initiative, this dataset describes the listing activity of homestays in New York City

Data Dictionary of Pre-Cleaned Data: https://docs.google.com/spreadsheets/d/1b_dvmyhb_kAJhUmv81rAxl4KcXn0Pymz


## Data Dictionary

|Feature|Definition of Feature|
|-------|---------------------|
|id|Id associated with listing|
|description|Description/overview of listing|
|host_name|name of host for listing|
|borough-|NYC Borough associated with listing|
|neighbourhood|neighbourhood the listing is in|
|lat|Latitude|
|long|Longitude|
|cancellation_policy|Type of cancelalation policy|
|room_type|type of room associated with listing|
|construction_year|year construction happened/year built|
|price|Rental Price|
|service_fee|fee of stay, Airbnb profits|
|number_of_reviews|number of reviews the listing has|
|review_rate_number|average review of listing|
|availability_365|number of days the property is available in the year|
|verified|whether the host is verified or not|
|instant_bookable| if the listing is instantly bookable|


## Conclusions and Recommendations

There are fewer correlations to the cost of an Airbnb in NYC than I had anticipated, however I find that the data is lacking. I believe there are key demographics missing that could be analyzed further as to why specific neighbourhood's are more expensive than others. Such as events, where I anticipate Manhattan may have more expensive options given they host a variety of venues such as Broadway and Madison Square Garden.

Additionally, according to https://criminaljustice.cityofnewyork.us/individual_charts/violent-crime-rate-by-borough/ the Bronx has the highest crime rate out of any borough. Despite this, the Bronx is the second most expensive borough to stay in according to this data. Again, it is worth mentioning the data is not balanced and Brooklyn/Manhattan make up the bulk of listings in this data.

