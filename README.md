#  Cuisine filter V 1.0 :shallow_pan_of_food: 
## README GUIDE
This repository contains a guide for creating README.md files for new and existing repositories. The sections below include suggestions for different areas that can be covered in a README file where appropriate.
## Project Discription(V1.0)
Cuisine filter is a grasshopper tool design for food-eater to help them understanding city food culture and discover meishi differently.

It can classify the restaurant in a region by any nation and visualize each kind's spatial distribution in every 900 square meters (L-city scale). Identify a series of food courts with accurate locations for users to choose and explore (M-choose an area and zoom in). This tool can also indicate the amount and proportion of cuisines from different nations in annotation (pan charts+bar charts). This tool could be a promising approach for food eaters to lead them into delicious discoveries in another way and compare food-culture diversity in different cities. 

It could also be used in a time-based method. e.g., see the cuisine distribution changes in a day to find out the best time to enjoy Japanese food, or check the Italian restaurant distribution anytime you want to eat and find the nearest food court from your current location.  In this way, people could bring dishes options into their consideration while choosing a place to hang out since this tool allow seeing the restaurant density of any nation. 
## Site_*Tokyo + Paris*
Michelin stars originate from French, so Paris was the city that has the most Michelin-starred restaurants in the world. However from the past decade, Tokyo takes over this position, and now， Tokyo and Paris are the top 1 and 2 cities that have the most Michelin Starred restaurants in the world. And this Michelin Restaurant selection indicates the food quality, richness and diversity of a city，which is my reason choose these two cities. 
## Project Features
The main functions of this tool are: 
**- L scale: Show the spatial distribution of 3 kind of cuisines (choose by user) in general/ at X:00**
![Ani Paris](https://user-images.githubusercontent.com/88841215/136791624-5e3de770-d4af-4609-a421-5044464c0e98.gif)
  imagine 1: Change of Spatial distribution of cuisines in Paris [10:00-24:00/every 1 hour] click imagine to view 
  ![Tokyo general1](https://user-images.githubusercontent.com/88841215/136806543-46cc3796-34da-4d7a-ad41-3b7a99d6b176.jpg)
  imagine 2: Spatial distribution of Cuisines in Tokyo
**- M scale: Display accurate location of food courts ( classify base on nations) + navigate users to the cloest food court by shortest distance and shortest walk path[advance]!!**
![Ani paris Ss](https://user-images.githubusercontent.com/88841215/136791688-ecda1c35-4fb4-4dd9-b11f-25d652c1d46d.gif)
  imagine 3: shortest distance & shortest path to cloeset food court-click imagine to view
**- Annotation: Proportion and amount of cuisines + total area of different food courts + shortest distance to food court**
  **all feature above could be apply in both general and a particular moment**
  ![Diagram paris GIF file2](https://user-images.githubusercontent.com/88841215/136800840-d4a58ce5-fc47-4ba1-82b9-70597e2365ff.gif)
  imagine 4: infomation of Paris cuisine with time changed 
  ![Paris+Tokyo General](https://user-images.githubusercontent.com/88841215/136795036-7f8ab1b2-6c2a-4a52-94e0-1778a16d89b4.jpg)
  imagine 5: Diagram Paris+Tokyo  
## Project Structure
![struture_画板 1](https://user-images.githubusercontent.com/88841215/136876122-22286e1c-8203-4dee-872a-97b5b03db671.png)
## Installation + Usage
- step1：Download the release here：https://github.com/AmberYYYYYYYY/Cuisine-Filter/releases/tag/V1.0
- step2：Open rhino and open file in your grasshopper,download all grasshopper plugins required
- step3: Set a overpass API file for the **file path** componment
- step4: Set Rhino workplace to white background
- step5: Follow the project structure and instruction at right hand side of grasshopper work place. Explore functions you interested :)
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
- **cloeset point**:
  implementing the navigation function
## Seondary Usage
- Apply on other data set (in process)
![greenspace Paris](https://user-images.githubusercontent.com/88841215/136799505-6504ebdb-2bef-409d-a374-f53bc06d8c43.jpg)
![greenspace Tokyo](https://user-images.githubusercontent.com/88841215/136799543-54db1b74-0250-4664-bd94-4253ef08056f.jpg)




