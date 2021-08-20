#  Cuisine filter :shallow_pan_of_food:
## Introduction
Cuisine filter is a grasshopper tool that can classify the restaurant in a region by nations and count the number of restaurants in every 900 square meters to indicate the density and proportion of cuisines from different nations. This tool could be a good approach for foodies to lead them into delicious discoveries in a different way. 
It could help food lovers to visualize and check the proportion of a nation of restaurants they want to choose within 1km of their location. Meanwhile, people could bring dishes options into their consideration while choosing a place to hang out since this tool give an opportunity to see the restaurant density of any nation. eg: you could choose an area where occupy by  French restaurants or any other nations.
## Site *Tokyo + Paris*
Michelin stars originate from French, so Paris was the city that has the most Michelin-starred restaurants in the world. However from the past decade, Tokyo takes over this position, and now， Tokyo and Paris are the top 1 and 2 cities that have the most Michelin Starred restaurants in the world. And this Michelin Restaurant selection indicates the food quality and richness of a city，which is my reason choose these two cities. 
## Project feature：
- Main functionality is to show the proportion of Japanese cuisine & French cuisine in total cuisine per unit area（900㎡）
- Secondary functionality is to show the coverage of general cuisine in a city
- You can also choose the nation you want to show its proportion/density
## Techiniques
There are 2 techniques in this tool, the first one is **parametric rectangular** and the second one is **Grid Field**.
- **Point to region-rectaugular**: 
  import the point data of different cuisine and draw foursquare around to show the coverage of cuisine and also provide curves for grid field.
- **Grid Field**:
  import 3 sets of curves (all/French/Japanese）separately from the last step and transfer them to density-based grids.
![Tokyo](https://user-images.githubusercontent.com/88841215/130212946-34214782-d444-4af9-bab7-34f02eee5b09.png)
imagine1.Tokyo
![Paris](https://user-images.githubusercontent.com/88841215/130212965-369947e7-b426-41cd-80ef-6b2216221111.png)
imagine2.Paris
## Installation + Usage
-step1：Download the release here：https://github.com/AmberYYYYYYYY/Test-mappingtool/releases/tag/0.1
-step2：open rhino and open file in your grasshopper
-step3: set a overpass API file for the **file path** componment
## Development
- Works in future： 
- How to show the proportion of a nation more accurate
- How to classify the traffic convenience of these area by adding another techinique.



