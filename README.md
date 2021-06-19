# Kickstarting with Excel

Performed analysis of Kickstarter data to uncover trends.
Utilized data set of 4114 crowd funding projects delineated by categories such as:
- Goal amount
- Pledged amount
- Outcome
- Country
- Launch Date
- Type of project

## Overview of Project

Analyzed crowdfunding data to determine if there are specific factors that make a campaign successful.
Attempted to uncover any hidden trends in order support the crowdfunding effort of the play, **_Fever_**, in order to obtain the budget of $10,000.

### Purpose

To determine how other Theater projects fared in relation to launch date and funding goals in order to tailor the crowdfunding efforts for **_Fever_** to increase the odds of success.

## Analysis and Challenges

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/85590155/122634079-6d76ad80-d099-11eb-809c-afd3e028e277.png)

Analyzed crowdfunding campaigns for **Theaters** to determine the if the likelihood of success is dependent of the month the campaign was launched.
For the **Theater** campaigns, categorized the outcomes into "successful", "failed", and "canceled" utilizing a pivot table.
For the pivot table, months were utilized in the rows and outcomes were utilized in the columns.  A filter was placed to only analyze **Theater** campaigns.
Created a line chart to visualize any trends according to the month the campaign was started.

-------

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/85590155/122634624-68672d80-d09c-11eb-8ac8-0531a112de18.png)

Analyzed the outcomes ("successful", "failed", and "canceled") for **Plays** by the goal amount.
The goal amount was placed into 12 buckets to determine if a certain range had a better chance of success.
There were a total of 1047 campaigns for **Plays**, none of which were "canceled".
Utilized Countifs function to delineate the different outcomes into the appropriate goal buckets.
Created a line chart to visualize the percentage of outcomes based on goal amount.

### Challenges and Difficulties Encountered

There weren't any challenges encountered but considerations needed to ensure accurate data were:
- Successfully converting the Unix timestamps.
- Ensuring there weren't any outliers that would corrupt the data.
- Ensuring the data was robust enough to be able to draw accurate conclusions.

### Analysis of Outcomes Based on Launch Date
Conclusions
- To increase the probability of completing a "successful" **Theater** campaign it should be started during the summer months.
- Starting a **Theater** campaign during the month of December gives the lowest probability of completing a "successful" campaign.

### Analysis of Outcomes Based on Goals
Conclusions
- The budget should be kept under $10,000 in order increase the probability of having a "successful" campaign for **Plays**.
- The probability of a **Play** campaign being "canceled" is low.

### Considerations
Limitations of this data set:
- While there is enough data to understand the average donation, there isn't a method to understand the distribution of donations among backers for the campaigns.
- Would be helpful to understand if there are regional differences within the countries with respect to crowdfunding.
- Data set does not include the method in which the crowdfunding was conducted.
-------------
Other possible tables and/or graphs:
- Visualize if there is a correlation between success rate of campaigns and duration of campaigns.
- Visualize if there are any subcategories in which outcomes is highly correlated.
- Visualize if there are certain countries which have a higher probability of achieving a "successful" outcome. 
