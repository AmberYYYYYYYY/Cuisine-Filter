#  Cuisine filter :shallow_pan_of_food:
## Introduction
Cuisine filter is a grasshopper tool design for food-eater to help them understanding city food culture and discover meishi differently.

It can classify the restaurant in a region by any nation and visualize each kind's spatial distribution in every 900 square meters (L-city scale). Identify a series of food courts with accurate locations for users to choose and explore (M-choose an area and zoom in). This tool can also indicate the amount and proportion of cuisines from different nations in annotation (pan charts+bar charts). This tool could be a promising approach for food eaters to lead them into delicious discoveries in another way and compare food-culture diversity in different cities. 

It could also be used in a time-based method. e.g., see the cuisine distribution changes in a day to find out the best time to enjoy Japanese food, or check the Italian restaurant distribution anytime you want to eat and find the nearest food court from your current location.  In this way, people could bring dishes options into their consideration while choosing a place to hang out since this tool allow seeing the restaurant density of any nation. 
## Site_*Tokyo + Paris*
Michelin stars originate from French, so Paris was the city that has the most Michelin-starred restaurants in the world. However from the past decade, Tokyo takes over this position, and now， Tokyo and Paris are the top 1 and 2 cities that have the most Michelin Starred restaurants in the world. And this Michelin Restaurant selection indicates the food quality, richness and diversity of a city，which is my reason choose these two cities. 
## Project feature
- L scale: Show the spatial distribution of 3 kind of cuisines (choose by user) ![未标题-1](https://user-images.githubusercontent.com/88841215/135042293-e28d1e8a-b143-4d45-81b9-edabc74b76f9.gif)

  imagine 1: Change of Spatial distribution in Paris [10:00-24:00/every 1 hour]
- M scale: Display accurate location of food courts ( classify base on nations) + navigate user to the cloest one![zoom in](https://user-images.githubusercontent.com/88841215/134680086-ef708a9a-f6af-46c3-873c-671d37faa287.png)

- Annotation: Proportion and amount of cuisines + total area of different food courts + distance to food court
  
  **all feature above could be apply in both general and a particular moment**
- transportation convenience level: feature
## Techiniques
There are 4 techniques in this tool, **Grid Field**/ **convex hull**/ **metaball**/**cloest point**
- **Point to region-rectaugular**: 
  import the point data of different cuisine and draw foursquare around to show the coverage of cuisine and also provide curves for grid field.
- **Grid Field**:
  import 3 sets of curves (all/French/Japanese）separately from the last step and transfer them to density-based grids.
- **Convex hull**:
  identify a series food courts which contain a minimise amount of restaurants
- **metaball**: 
  visualize the transportation convenience for reference
- **closet point**:
  implementing the navigation function
## Installation + Usage
- step1：Download the release here：https://github.com/AmberYYYYYYYY/Test-mappingtool/releases/tag/V0.7
- step2：Open rhino and open file in your grasshopper
- step3: Set a overpass API file for the **file path** componment
- step4: Set Rhino workplace to white background
- step5: Explore functions you interested :)
## Advanced function
apply on other data set (in process)



