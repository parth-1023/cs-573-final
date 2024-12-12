# Data Visualization Project

## Data

The data I propose to visualize for my project is World Cup Data which can be found [here](https://www.kaggle.com/datasets/akshatkjain/icc-world-cup-2007-2023-over-by-over-summary)


## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * How to visualize the winning score/stats for a team
 * How to calculate the run rate for the line graph
 * Is there any interesting relation between Over Number and Wickets Taken?
 * As given to me in a feedback will try to make the landing page more interesting and fun!

## Sketches

[![image](https://github.com/parth-1023/dataviz-project-template-proposal/blob/master/sketches.jpg)]

 * The sketches show how the interaction would work as I have imagined it.
 * First the user woud see a world map and zoom over the regio he clicked on. (This has been changed in the implemented version as now I am showing a globe with zooming and panning)
 * Then he would be presented with different stadiums all over the country, which he would click on and see different matches.
 * After clicking on a match he would be presented with a line graph.


## Prototypes

I’ve created a proof of concept visualization of this data. It's a line graph and it shows relation between Runs and Overs.

[![image](https://github.com/parth-1023/dataviz-project-template-proposal/blob/master/graph.jpeg)](https://vizhub.com/parth-1023/c5cca3103fb344e7a1f38bfd0199f626)


## Open Questions
I am not sure whether I will be able to interact with the world map as I want to. I want to have the outline of the countries where the world cup happened after I hover over them and zoom into them after I click on them.
I will try to implemet this but if not then I might implememt a "poor man's version of this idea".

## Milestones

 * Week 1:
   Try to make the landing page with the world map.(Implemented this)
 * Week 2:
   Will try to add interaction to different maps. Also make the new database
 * Week 3:
   Try to add hover and click events in the visualization.
 * Week 4:
   Implement line graph and its feature.
 * Week 5:
   Final touches

## Week 2 update
Cleaned data as I was working with a temporary data for the globe (https://vizhub.com/parth-1023/9a4270b3efa443178f9b4747848cb729?edit=files&file=map.js&tabs=index.js%7Emap.js)
Added coordinates for each city as they were missing from the dataset (https://vizhub.com/parth-1023/9f2d252745ec4e83b65c697fb8996731)

## Week 3 update 
Tried to play around hiding the point behind the globe when it is rotated but could not properly implement it
(https://vizhub.com/parth-1023/ba2f42459884448180777cf4a6be40ee)
Also made some changes to the data that was being used as it was close to 5Mb and was really slow to load.
(https://vizhub.com/parth-1023/312eebbfee944cc7b5c8a8b49992d918)

## Week 4 update 
Properly implemented the cities on globe feature, where when you hover over a particular city you are presented with a table where you can see the matches and their details played at that city.
(https://vizhub.com/parth-1023/2e6f345d7b304c5ead755144aa27438b)

## Week 5 update
Implemented the line graph chart for each match of each city where you can see runs scored through each over in that particular match.
(https://vizhub.com/parth-1023/9963ba82905847b5bbb21303aba4162e)
Also made some changes to the overall feel of the project.

