# GEOG 485 Lab 3: Web Map Application

In this lab, we will design a web map application. We will be designing two differnt
types of map. One choropleth map and one proportional map.

## Map 1: Choropleth Map

### Thought Process

For the choropleth map I wanted to create something similar to the GEOG 328 Class
with the differnt color for each state based on the cases of COVID in 2020. And having
a legend that showcase the different color that is on the map.

### Coding

I ran into multiple errors while trying to code this one up. I some how couldn't display
the choropleth map. The map showed and the legend too. But the map is left blank with no
color on each state. I'm not sure if my geojson file was loaded correctly. But it's in the
respository. So I not sure why the data is not getting extracted on to the map. Here are the steps
I took to try and fix the issue.

- i tried messing around the legend
- tried reloading the dataset and see if that work
- copy the relative path and paste into the map.source()
- make sure that the geojson file is in the correct format

Wiith all of these steps I took to load the data onto the map. None of them worked. The choropleth
map isn't displayed and some how the legend isnn't either.

### Results

I added up with a blank map with no data. I tried everything but the datast woudlnn't display
on the map. I'm not sure what has happened. I did research on the issue too, but nothing
to my specific issue.

## Map 2: Proportional Map

### Thought Process

For the proportional map I wanted to do something similar to the Earthquakes in Japan.
But with the total cases of COVID in US. With the circles representing the sizes of cases.

### Coding

Like the same as the map 1: choropleth map. I ran into the same issues where the map is not
being displayed. I'm sure this time it's because of the file because i tested it and the file
wasn't working. But the relative path was copy and paste into the code. And the format
of the geojson/ json file is formated correctly. So I'm not sure why it's not being displayed.

### Results

Like map 1: choropleth map I ended with a blank map. Not sure why the code is correctly
done and the file is correctly formated. But I think it can be a small error that
caused the map to not appear.