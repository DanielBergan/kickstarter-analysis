# An Analysis of Kickstarter Campaigns

## Overview of Project
Visualizing Kickstarter Campaign Outcomes
### Purpose
In order to better understand the relationship between timing, expectaion, and success of Kickstarter campaigns we look at the kickstarter data at hand and draw conclusions.
## Analysis and Challenges
The first thing we did was filter the information to only include criteria that was pertinent to our task. We were less interested in the success of fundraising campaigns for theater construction than we were for plays themselves. The main challenge of this analysis was the overabundance of data  contained in our [Excel file](kickstarter-analysis/Kickstar-Analysis.xlsx) which we addressed by whittling down the dataset to get to the heart of the matter. We wanted to know *what role campaign timing played*. We also wanted to know *how campaign goals related to success*.
### Analysis of Outcomes Based on Launch Date
To get a better understanding of how the launch date effected the outcome we created a pivot table and [line graph](kickstarter-analysis/resources/Theater_Outcomes_vs_Launch.png) showing how many successful, failed, and canceled campaigns there were throughout the year.
### Analysis of Outcomes Based on Goals
With the outcomes based on goals we took the number of successful, failed, and canceled campaigns and divided them based on goals in ranges of increments of $5,000. We then determined what the percentages of these outcomes were and charted them in [this graph](kickstarter-analysis/resources/Outcomes_vs_Goal) where we can start to see some interesting correlations.
### Challenges and Difficulties Encountered
The main challenge involved with this analysis was that only a limited amount of the data was actually useful to our cause. This was not very difficult to overcome, merely a bit time consuming.
## Results

- Campaigns that are launched in the beginning of summer have a higher success rate.
- Campaigns launched at the end of the year have a low rate of success.
- Setting the goal of a campaign below $20,000 increases the campaigns likelihood for success

- The dataset is limited in its scope of time in that it only goes back 13 years.

- We could also explore creating graphs and tables that highlight outcomes with these parameters filtered by country to find where future campaigns would be best recieved.
