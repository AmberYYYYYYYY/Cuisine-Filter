#  Restaurant diversity funnel :shallow_pan_of_food:
## Introduction
Restaurant diversity funnel is a grasshopper tool that can classify the restaurant in a region by nation and count the type of restaurants in every 900 square meters to indicate the density and proportion of cuisines from different nations. This tool could be a good approach for foodies to lead them into the delicious discoveries in a different way. 
It could help food lover to visualize and check the proportion of a nation of restaurant they want to choose within 1km of their location. Meanwhile, people could bring dishes options into their consideration while choosing place to hangout since this tool give a opportunity to see restaurant density of any nations. eg: you could choose a area where occupy by French restaurant or any other nations.
## Site *Tokyo + Paris*
Michelin star originate from French, so Paris was the city has most Michelin starred restaurants in worlds. However from past decade, Tokyo take over this position, and now， Tokyo and Paris are top 1 and 2 city that have the most Michelin Starred restaurants in worlds. And this Michelin Restaurant selection indicate the food quality and richness of a city，which is my reason choose these two city. To develop a tool for foodie
## Project feature：
- Main functionality is show the proportion of Japanese cuisine & French cuisine in total cuisine per unit area（900㎡）
- Secondary functionality is show the coverage of general cuisine in a city
- You can also choose the nation you want to show it proportion/density
## Techiniques
There are 2 techniques in this tool, first one is parametric rectangular and second is Grid Field.
- point to region-rectaugular: 
  import the point data of different cuisine and draw foursqure around to show the coverage of cuisine and also provide curves for grid field.
- Grid Field: import 3 sets of curves (all/French/Japanese）separately from last step and transfer to density based grids.
![Tokyo](https://user-images.githubusercontent.com/88841215/130212946-34214782-d444-4af9-bab7-34f02eee5b09.png)
imagine1.Tokyo
![Paris](https://user-images.githubusercontent.com/88841215/130212965-369947e7-b426-41cd-80ef-6b2216221111.png)
imagine2.Paris
## Installation + 
-step1：Download the realease here：https://github.com/AmberYYYYYYYY/Test-mappingtool/releases/tag/0.1
-step2：open rhino and open file in your grasshopper
-step3: set a overpass API file for the **file path** compenment
## Development
- working on： -- How to show the proportion of a nation more accurate
               -- classify the traffic convenience of these area by add another techinique.



