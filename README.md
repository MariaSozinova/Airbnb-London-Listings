# Airbnb-London-Listings
Analysis of real estate object for rent in London using Airbnb dataset.

## Link to the dashboard
https://public.tableau.com/app/profile/maria5911/viz/analitics_listings/Dashboard1

## Project Overview
Company A worked in the area of short-term lease. The business pattern is based on long-term renting of objects through Airbnb and further renting them out for short-term periods. The project’s aim is to analyse the real estate market of London and prepare a dashboard for management showing the most suitable/profitable options on the market. 

## Data Source
https://www.kaggle.com/labdmitriy/airbnb

## Dataset Description
Dataset includes the following files:
- listings.csv — detailed information on each object
- listings_summary.csv — summary information on each oobject (there are less columns than in the first table)
- calendar.csv — availability calendar 
- neighbourhoods.csv — list of neighbourhoods
- neighbourhoods.geojson — geo-shape
- reviews.csv — list of reviews for the objects
- reviews_summary.csv — summary of reviews for the object

## Tools
The whole project was done in Tableau

## Connecting and Manipulating Data
Data sets were loaded directly to Tableau Public. In the analysis I used only 2 files with data: listings.csv and neighbourhoods.geojson.

Before working on the analysis and dashboard I hid the unnecessary columns, checked the types of data and created a relationship between the 2 files.

## Creating Visualization and Constructing Dashboard
The following KPIs were calculated during the analysis:
-	Average Load overall and per neighbourhood 
-	Total Number of Listings overall and per neighbourhood 
-	Median Price overall and per neighbourhood 

All KPI cards are dynamic and show corresponding metrics depending on the selection of other parameters including neighbourhood, type of property, number of bedrooms etc. 

The listings were analysed by:
- Rating
- Type of property
- Number of bedrooms

For easier comprehension I added an interactive map of the districts allowing to click on any neighbourhood to see its details dynamically.

The dashboard includes a section with Top Listings (by load and rating) with their details. There is a map with the objects and the table with the details of each object. A click on any object within the table will forward a user directly to Airbnb web-site. The table contains a pagination so that the user can see upto 1000 top objects.

The dashboard also contains a filter on price to select the desired price range. The action filters make the dashboard dynamic. 

