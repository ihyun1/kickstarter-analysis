# Kickstarting with Excel

## Overview of Project
In order to assist our client, who launched a Kickstarter campaign for a theatrical play, we have gathered data on over 4,000 Kickstarter campaigns for a vast range of ventures. Our main interest in the dataset was the campaigns for theatrical plays and the relationship of successful campaigns to their launch date and fundraising goals.
### Purpose

## Analysis and Challenges


### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch.png](Columbia Data Analyst Bootcamp/Analysis Projects/Kickstarter/Resources/Theater_Outcomes_vs_Launch.png)

As shown above, this graph charts the number of successful, failed, and canceled theater campaigns by the month that the campaign was launched. From our dataset, we filtered for all theater campaigns then dividing them into the three outcome categories as well as by when the campaign was started.

### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals.png](Columbia Data Analyst Bootcamp/Analysis Projects/Kickstarter/Resources/Outcomes_vs_Goals.png)

The chart above illustrates the percentage of successful, failed and canceled campaigns for theatrical plays, as opposed to simply theater campaigns, by month. The chart was created by dividing our data into 12 different fundraising tiers, starting from less than 1000 to greater than 500000. Then, we utilized the COUNTIFS function to pull the number of successful, failed and canceled projects in each category to calculate the percentage of successful, failed and canceled outcomes.

![COUNTIFS_function.png](Columbia Data Analyst Bootcamp/Analysis Projects/Kickstarter/Resources/COUNTIFS_function.png)

### Challenges and Difficulties Encountered
Given our dataset, it was hard to isolate and determine relational factors for successful campaigns as there were 15 columns of data that were not all analyzed. Additionally some of our data was not formatted for immediate use, both the start dates and deadlines were in Unix timestamps, so those values had to be converted in order to properly read, chart, and analyze them.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Our data showed a stark increase in campAaigns launched beginning in May, then steadily decreasing over the course the summer through August. June 2016 had the worst ratio of successful to failed campaigns than any other June recorded in the dataset.

![Outcomes_vs_Goals_2016.png](Columbia Data Analyst Bootcamp/Analysis Projects/Kickstarter/Resources/Outcomes_vs_Goals_2016.png)

- What can you conclude about the Outcomes based on Goals?
![Outcomes_vs_Goals_Table.png](Columbia Data Analyst Bootcamp/Analysis Projects/Kickstarter/Resources/Outcomes_vs_Goals_Table.png)

Given the amount of data for campaigns with a goal of less than 1000 and 1000 to 4999, and the success rates of roughly 75% for each, we can reasonably assume that most campaigns with goals under 5000 have a strong chance to succeed, whereas campaigns with a goal of 5000 to 24999, the success rates dropped to around 50 percent.

- What are some limitations of this dataset?
As mentioned in the difficulties of this project, there are many factors included in this dataset that made it hard to determine the strongest relational factors. Additionally in the initial gathering of data, there is a skew toward smaller campaigns for theatrical plays as revealed in our Outcomes based on Goals table.

- What are some other possible tables and/or graphs that we could create?
Given the number of variables in our dataset, there are many relationships that we could plot and analyze to further understand the factors on a successful campaign. We could chart to observe if there is a correlation between the number of backers and the success of a campaign, specifically campaigns with more donors and a lower average or less donors and a higher average. Additionally, the effect of the length of fundraising period, or the effect of staff picks on success.
