# An analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends

## Overview of Project
In this project, I utilized Microsoft Excel to analyze kickstarter campaigns across various project categories to inform my client Louise, who is planning a fundraising campaign for a play. 

### Purpose
As my client, Louise's play, Fever, approaches it's fundraising goal, she wants to know how fundraising campaigns for other theatre productions fared in relation to their launch dates and goals. Using data collected from various Kickstarter campaigns, I created visualizations to help Louise project the success of her own campaign based on variables such as campaign launch date and goal amounts. 

## Analysis and Challenges
To assist Louise in her decision-making about launch timing, I created an analysis of the success of all kickstarter campaigns launched for theatre productions, sorted by the month of their launch date. 

![Outcomes Based on Launch Date](https://github.com/scallina/kickstarter-analysis/blob/main/Outcomes%20By%20Launch%20Date.png)

To provide guidance to Louise when considering the dollar amount of their launch goal, I also created a line chart analyzing the differing degrees of success between kickstarte campaigns for plays, respective to the dollar amount of their goal. 

![Outcomes Based on Goal](https://github.com/scallina/kickstarter-analysis/blob/main/Outcomes%20Based%20on%20Goal.png)

### Analysis of Outcomes Based on Launch Date
According to this dataset, the months May and June have the highest numbers of reported success for theatre campaigns (111 and 100, respectively). Additionally, the gap between successful and failed theatre campaigns is most narrow (indicating the highest chance of failure) during the months of October and December (5 and 2, respectively).

### Analysis of Outcomes Based on Goals
The analysis of outcomes based on goal amounts indicates that smaller campaigns for plays favor success if the goal amount is less than $10,000. The possibility of success tends to decrease heavily between goal amounts of $5000 and $10000, with a rate of success decreasing by 35%. 

For larger fundraising campaigns for plays, success only outweighs failure when goal amounts lie between $35,000 and $45,000. Kickstarter campaigns for plays with a goal of $20,000 or more favored failure if the goal did not fall between those two amounts. 

### Challenges and Difficulties Encountered
When completing this challenge, my greatest challenge was ensuring my 'countifs' formula was correct across all cells of my 'Outcones Based on Goals' table. Multiple proofreads were necessary to eliminate all errors due to copying the formula across an array of cells. Additionally, it took multiple attempts to find a reliable tutorial for creating line graphs for Excel 2016. 

## Results

### Conclusions based on Launch Date
-Based on the dataset, it would be most advantageous for Louise to launch a campiagn during the Summer, between the months of May and June. 

-Based on the data, it would be the least advantageous for Louise to launch a campaign during the Winterm between October and December. 

### Conclusions Based on Goals
-If Louise desires to launch a smaller Kickstarter campaign for Fever, she would be most likely to find success if her goal is less than $5000. A campaign with a goal between $500 and $9999 would still favor success, but only by 10%. 

-If Louise desires to launch a larger fundraising campaign, she is most likely to be successful if the goal amount lies between $35,000 and $44,900. 

### Limitations of the Dataset
-The dataset is 5 years outdated, with the most recent kickstarter campaign being lunched in the year 2017. 

-The dataset also greatly favors kickstarter campaigns for plays within the United States and Great Britain. If Louise was interested in bringing the campaign to another country, this data would not be reilable. 

### Possibilites for other tables and graphs
-We could create a line graph analyzing the success of campaigns for plays depending on how long the campaign lasts. That way, Louise would be able to best predict when to end her campaign due to diminished returns in money raised. 
