# Kickstarting with Excel

## Overview of Project

This is a short analysis of kickstarter theater based campaign outcomes between 2009 and 2017. The goal is to help understand our kickstarter campain, what goals to set and hopefully gain some insight as to when to launch our campaign.

### Purpose

As part of a bootcamp project for showing competency and understanding of Excel we are submitting a short analysis of this kickstarter data 

## Analysis and Challenges

### Kickstarter as a platform for theater and arts projects.

We can see that out all of the entertaint and arts campaigns launched theater took the plurality of categories. This does suggest that there is a community of target donors target donors we can hope to appeal to.

![](https://raw.githubusercontent.com/zkellsworth/kickstarter-analysis/master/resources/overall_outcomes.png)

### Analysis of Outcomes Based on Launch Date

*Most successful campaigns were in the spring*

Our data shows that most successful campaigns were launched in the spring. This could be because people are planning and looking forward to summer activities, but unfortunantly the information is not in the data and the reason behind it is beyond the scope of this analysis. Suffice it to say we do see more success when campaigns are launched during the spring. 

*Most failed campaigns were launched in december*

Unforutnantly there is insufficient data as to why. I would submit my hypothesis that the increased holiday spending and stress is probably a large contributor to the failed projects.

![](https://github.com/zkellsworth/kickstarter-analysis/blob/master/resources/Theater_Outcomes_vs_Launch.png?raw=true)

### Analysis of Outcomes Based on Goals

#### More theater and play projects succeeded than failed.

This is just an optimistic look at the overall outcomes of campaigns launched in these categories. We can see that more campaigns were succesfully funded than weren't. The first chater is for the primary "Theater" category.

![](https://github.com/zkellsworth/kickstarter-analysis/blob/master/resources/theater_outcomes.png?raw=true)

And specifically for campains for plays

![](https://github.com/zkellsworth/kickstarter-analysis/blob/master/resources/play_outcomes.png?raw=true)

However, there is a goal based consideration to the above. When the goal is between $5000 to $10000 we cross the mark from the majority of projects getting funded to the majority failing their goal.

![](https://github.com/zkellsworth/kickstarter-analysis/blob/master/resources/Outcomes_vs_Goals.png?raw=true)

#### Goal amounts

And here we'll see that the average of most succesful campains were right around the $4000 mark. While there was an outlier well above that at $15,000 the majority of campaigns stayed around that $4000 point. Likewise when asking for pledges the average pledge was $1000 with very few going above that amount. 

![](https://github.com/zkellsworth/kickstarter-analysis/blob/master/resources/goals_and_pledges.png?raw=true)

### Challenges and Difficulties Encountered

Advanced excel can sometimes be a fickle beast. There was a point that our tables were not populating, but turned out to be user error in construction of the tables. Specifically I was dropping the column data in the "column" field in the pivot constructor instead of the values field. 

## Summary

Using the information provided from kickstarter itself we have been able to show that there is a large demographic of potential donors for the play. However, the stated goal of $10,000 does put us in a fundraising category that less than half meet their goals. As stated there is a sharp uptick in successful campaigns in the spring, but the data to conclude why is unavailable. Likewise we can see the majority of failed campaigns happen in December and again there is insufficient data to conclude why. A usefull piece of data would be the donor count or donor amount per month. Doing this would allow us to graph this more fine data per month.




