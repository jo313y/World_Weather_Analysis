# World_Weather_Analysis

## For Reference
This was the first API call using google maps. 

### Mapping Data
It is important to know how to properly parse .json files to grab valuable information from them. Whenever you use an API, you'll need to be able to parse and clean the data. To create these maps, the user pulled data from google into a .json file. Using the specific locations within a .json file the data was grabbed and placed into a dataframe. That information in the dataframe was then used to build into Google's APIs through Maps, to build a heat map, marker map, and travel map. 

### Key Scripts

- Random Location Generator
  - Used a random number generator to generate random latitudes and longitudes
  - Used citypy in order to determine the closest cities to the random latitude and longitudes
- API Call
  - API Call to pull data from Google into a .json file
- Google Maps
  - Heat Layer Map
  - Marker Layer Map
  - Travel Mode Map
