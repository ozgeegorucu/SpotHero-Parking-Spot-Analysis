# Web-Scraping-SpotHero
SpotHero has been paving the way for millions of drivers to easily find affordable parking at more than 7,500 garages, and lots in over 300 major North American cities. Aim: Analyzing parking spots and classifying them to their locations, amenities, prices, and efficiencies facilitate the selection of suitable parking spots.

# SpotHero Parking Spot Analysis
This project is a Python script that uses the BeautifulSoup and Selenium libraries to scrape data from the SpotHero website and analyze parking spots based on their locations, amenities, prices, and efficiencies.
Motivation
The website provides a search bar to find parking spots according to their address and cities across North America. The project extracts addresses, reviews, amenities, access hours, and prices of parking spots from this website. The following steps were taken to achieve the objective:

Addresses and garage names, stars, hourly prices, and spot IDs were extracted separately.

Spot IDs were used to create details links for each parking spot.

Web scraping was applied for all detail links to extract amenities and access hours data.

Geocode processing was applied to find coordinates of parking spots by using address information for showing on the map.

Neighborhood shapefile data was intersected with the parking spot data to extract neighborhood information of spots by using GeoPandas.
# Conclusions
The following conclusions were drawn from the analysis:

Yonge-Bay Corridor has the maximum average price, and Annex has the minimum average price for a one-hour parking spot.

Church-Wellesley has the maximum number of parking spots, and Annex has the minimum number of parking spots.

According to reviews, 72% of parking spots have an Excellent score, 22% have a Great score, and 7% have a Good score.

When prices and reviews are compared, low prices have more reviews, and generally, low prices have more excellent scores.

According to open hours, 95% of parking spots are open 24/7.

# Usage
To use the project, you can clone the repository and run the Python script. You will need to have the necessary Python libraries installed to run the script.

# Installation
To run this script, you will need to have Python 3 installed on your machine. You can download it from the official Python website: https://www.python.org/downloads/

You will also need to install the following libraries:

BeautifulSoup
Selenium
pandas
numpy

You will also need to download a web driver for Selenium to use. You can download the Chrome web driver here: https://sites.google.com/a/chromium.org/chromedriver/downloads
