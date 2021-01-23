# IBM Applied Data Science Professional Certificate Capstone project at Coursera
### By Jens Greve
### January 23

## Opening a Mexcian restaurant in New York city

## Business problem description
The objective of this Capston project is to retrie local based data and analyze it in order to select the best locations in New York city to open a Mexican resturant. The project will use data science retriveing, analyzing and visualizatring methodolgies tought in the Course course.

Questions aimed to be answered im the report:
- In which jurisdictions of New York do people of hispanic origin live?
- Which neighbourhoods or boroughs have the largest number of Mexican resturants and/or the hights ratings / most likes?
- What is / are the best location(s) to open a Mexican restaurant in New York City? 

### Introduction
New York City is the largest city in US with 8.4 million people according to Wikipedia and with a wide and diverse range of ethnicities. It also has a large history of immigration and 48.6% of NY citizens are speakers of a non-English language according to https://datausa.io/. And New York Times has claimed that New York is the most diverse city in the world with 800 languages spoken in New York. So it has a long tradition of different ethnical restaurants.

This final project aims to analyze the availability of Mexican restaurants in New York and make some discussions of how the data could be used to find the best location for a Mexican in the area of New York city. Mexiacn restautants. The Mexican cuisine has been raising in popularity in USA for many years and US consumers for several years, while it has always been popular with people of hispanic origin.

So this project aims to analyze the ethnical demographics of the New York jurisdictions or boroughs and the availability and ranking of Mexican in boroughs to understand the competion and opportunity to open a Mexican resturant in New York.

### Data Required
In order to answer the above questions, data on New York City is required

- List of neighborhoods and boroughs of New York city
- Latitude and longitude of the neighbourhoods and boroughs
- Venue data of the restaurants
- Demographic data of ethnical origin by neighbourhood

### Data Sources
- New York City data ethnical orgin of New York will be obtained at this web site: https://en.wikipedia.org/wiki/Demographics_of_New_York_City

- New York City data containing the neighborhoods and boroughs, latitudes, and longitudes will be obtained from the data source: https://cocl.us/new_york_dataset

- All data related to locations and quality of Mexican restaurants will be obtained via the FourSquare API utilized via the Request library in Python.

### Methodology
• Data will be scraped from a table from https://en.wikipedia.org/wiki/Demographics_of_New_York_Cit and cleaned, sorted and put into a dataframe

• Data will be collected from https://cocl.us/new_york_dataset and cleaned, sorted and processed into a dataframe.

• The data will be enriched with GPS corrdinates using the Python geocoder package

• FourSquare APIs will be used to locate all venues and then filtered by Mexican restaurants incl. their ratings, likes and tips and added to the dataframe.

• Venue data will be sorted based on sum, ranking and borough.

• Finally, the data will be visually assessed using graphing from Python libraries.
