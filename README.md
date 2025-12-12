Analyzing squirrel behavior in Central Park
================
by Cate, Dillon, and Tomas

## Summary

The Squirrel Census is a project that was first planned and conducted in October 2018.  The project organized a group of volunteers gathered to collect data on the squirrels of New York City's Central Park. The volunteers made observations about the squirrels' locations, physical characteristics, and behaviors, and then took notes on them by either marking with True or False statements or leaving comments in a notes section.

The dataset contains `r nrow(squirrels)` observations and `r ncol(squirrels)` variables. As we analyze this dataset, we hope to better understand the squirrels of Central Park. Some questions we are interested in answering include:
1. Are some squirrels more likely to be foraging than others?
2. Are the squirrels above ground more often in the morning or evening shift?
3. Is there a variation in the frequency of interaction with humans by the age of the squirrels?

To answer our questions about squirrel behavior, we analyzed data from the 2018 Central Park Squirrel Census. We looked at mapped squirrel sightings, compared frequencies of different behaviors, and examined how activities changed between the AM and PM shifts. We also used graphs to study how often squirrels interacted with humans and whether the time of day affected these interactions. From our analysis, we found that foraging was by far the most common behavior, and squirrels tended to run from humans more often in the afternoon. Overall, the data showed clear patterns in squirrel activity based on both behavior type and time of day. 

While this data contributed to an interesting project and insight into the squirrels of Central Park, it certainly has its limitations. The largest drawback is definitely the heavy reliance on volunteers for data collection. The volunteers were not experts and their responses were not standardized so they were not trained to observe more than an average person and their responses were sometimes formatted incorrectly, or in a way that was difficult to use for this project. For example, several of the squirrels appeared to be in Colombia when we created the map because the coordinate points were not all collected in the same way. Further, the notes section had interesting information about squirrel behavior, but there were too many for us to go through individually and code for this project. Researchers interested in this topic may consider taking the time to analyze each of these comments thoroughly to look for any trends. It would also be interesting to compare the number of visitors in the park during the AM and PM shift to the number of squirrel sightings and how they interacted with humans during these times.


#

## Handout

Our handout can be found [here](handout/handout.pdf).

## Memo

A link to the code and how we created our graphics in our memo can be found [here](memo/memo.md).

## Data
Our data can be found [here](data/2018_Central_Park_Squirrel_Census_-_Squirrel_Data.csv)
City of New York. (2018) (_2018 Central Park Squirrel Census._ (Data Set) <https://catalog.data.gov/dataset/2018-central-park-squirrel-census-squirrel-data>
