# An Analysis of Kickstarter Campaigns

## Overview of Project


### Purpose
Provide an analysis of [Kickstarter](www.kickstarter.com) campaigns to determine campaign outcomes in relation to launch dates and funding goals. Visualizations and results are shared to understand similar Kickstarter campaigns and to inform Louise of the highest likelihood her campaign would be funded.

## Analysis and Challenges
Analysis was performed on Kickstarter campaign data provided via Excel to help Louise investigate outcomes of campaigns similar to hers. Data for a wide variety of campaign categories is presented, creating a large and challenging dataset. I focused on subsets of the data in an effort to provide the best comparison to Louise's Kickstarter for her play *Fever*. Length of campaign, launch date and geographic location were some of the considerations investigated to observe success rates. One challenge that arose was the "Deadline" and "Launched At" columns presented in the Excel sheet were listed in Unix Timestamps. I used the following formula in Excel to convert the Unix Timestamps to a readable date format (where J2 is the "Launched At" date for the entry): 

![Launched at Column](https://user-images.githubusercontent.com/95710184/147415048-e19c70a8-3052-4108-a953-9acb2ef4acd5.png)

![Unix Date Conversion Excel Formula](https://user-images.githubusercontent.com/95710184/147415413-4f803f7d-a042-412e-810d-74515e421d38.png)

This formula made it possible to present data in the calendar date format, rather than the Unix Timestamp. From the formula conversion, I could easily extrapoloate the month and year of the campaign.

### Analysis of Outcomes Based on Launch Date
The number of successful, failed and canceled campaigns based on launch month was investigated. Results are shown in the chart below:
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/95710184/147135311-ab3633ac-2ed7-4ea4-aa40-880a03d42748.png)

### Analysis of Outcomes Based on Goals
Percentage of successful, failed and canceled campaigns based on initial funding goals are presented below:
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/95710184/147135320-cb6f4bd1-32ac-4cac-bd07-4b63993a5217.png)

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date? 
     - The highest number of successful theater campaigns on Kickstarter were launched in May, June and July.
     - A similar number of theater campaigns fail each month.

- What can you conclude about the Outcomes based on Goals? 
     -The campaign goal does not appear to be predictive of the outcome. However, the campaigns with the highest percentage of successful outcomes had goals of less than $1,000. 

- What are some limitations of this dataset?
     -This dataset has a limiation of including several outliers. If the outliers are not identified and taking into consideration in the analysis, the analysis may be skewed. As seen below, only a small number of projects compared to the total had goals over 20,000. These data points may not be important for Louise's comparison and potentially shoule be omitted.

![Goal summary](https://user-images.githubusercontent.com/95710184/147415391-aa67c5b0-a250-4cbd-82ca-28a90a6d228b.png)

- What are some other possible tables and/or graphs that we could create?

