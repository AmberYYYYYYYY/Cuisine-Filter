#  Restaurant diversity funnel :shallow_pan_of_food:
## Introduction
Restaurant diversity funnel is a grasshopper tool that can classify the restaurant in a region by nation and count the type of restaurants in every 900 square meters to indicate the density and proportion of cuisines from different nations. This tool could be a good approach for foodies to lead them into the delicious discoveries in a different way.
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
- Grid Field: import 3 sets of curves (all/French/Japanese）separately from last step and transfer to density based grids.【show in imagine 1 and 2】
![Tokyo](https://user-images.githubusercontent.com/88841215/130212946-34214782-d444-4af9-bab7-34f02eee5b09.png)
![Paris](https://user-images.githubusercontent.com/88841215/130212965-369947e7-b426-41cd-80ef-6b2216221111.png)



## Installation

## Development
- working on： -- How to classify the type of cuisine and show the top 5 nations on map.
               -- How to design a grid field can show the amount of different cuisine per unit area

for foodie could find 直观反映所在点范围1平方千米内的 餐厅的nation构成 也可以根据自己想吃的菜式 来选择对应餐厅占比高的区域游玩。
