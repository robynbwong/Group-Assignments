# Project Update
Link 

## Status
Based on the advice from Yoh and Bo, as well as my own difficulties trying to use the Farmland dataset, I will be changing course a little bit. The CCED data is easy to use so I will keep using that. I also found a good census dataset that has how much of the county's population is urban versus rural, which I think is an interesting connection to land conservation.

This past week, I tried to research how to rasterize vector data in an attempt to do something with the Farmland dataset but I did not understand any of the guides. I tried to do it in QGIS but did not understand how people know what pixel size or scale to do. I tried to open the shapefile with geopandas in jupyter hub just to take a look at the data and it was too big for the notebook memory. So I looked at it a bit as a csv file with pandas, but after doing the basic data exploration I didn't know what else to do with it. 
## Data

## Major Concerns
### 1 
First, not being able to use the data I originally wanted to. But, the census dataset I got should be fine for me to use.
### 2
Second, I don't really understand how to make maps with categorical data. All the examples we have from class are interval-ratio and all the examples of folium are chloropleth maps. Honestly, I think this is a bigger issue for me than changing my scope a little bit. I tried to make a map to show different categories of the easement holders from my CCED but the code I tried to copy had all this stuff about making a custom legend and colors first and it made me confused. I would really like to see an example of this in class. I also am a little unsure of how to make a visualization that shows two different things overlayed, rather than just one chloropleth (like the percent black population one in class). For instance, to overlay the polygons of the easements with the chloropleth of percent urban population
