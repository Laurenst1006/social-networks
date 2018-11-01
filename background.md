# social-networks
Investigations Social Interactions at a Public School

## Overview
To get an overview, see the pdf version. The R code is contained in the .Rmd file.

## Background

Over the summer, I worked on a project at an Epidemiology lab at the University of Utah that investigated how social interactions in elementary schools, middle schools, and high schools affected the transmission of viruses. This project identified the social networks of a highschool in Salt Lake City, Utah. Students wore sensors that recorded the length and time of each interaction, enabling me to analyze these variables. This data will help epidimeologists better determine the spread of viruses through schools. 

There were four datasets downloaded in the project. The first two were the node attributes for Day 1 and Day 2. The third file was the highschool schedule enabling determination of the class period the interaction occured. The last interaction was the edgelist for both Day 1 and Day 2. 

I used R packages igraph, dplyr, chron, and lubridate and displayed my code for Day 1. Codes for Day 2 were very similar to Day 1. 
