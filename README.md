# An Analysis of Kickstarter Campaigns
Kickstarter Data Analysis for Project Funding 

### Module 1 Excel Challenge Analysis

From the visualizations created from the Kickstarter data, there are several conclusions that we can come to. 

![Outcomes Based on Goals](Waking-Dreamer/kickstarter-analysis/Module 1 Challenge.xlsx/Outcomes Based on Goals.png)

1) Plays that have lower fundraising goals are far more successful than others: Kickstarter Plays have the highest chance of reaching their funding goal when the goal is less than $1,000 (75.8% success rate). Funding goals of $1,000 to $4,999 (72.7% success rate) and $35,000 to $44,999 (66.7% success rate) also have a higher success rate when compared to the other goal thresholds. From the Outcomes based on Goals chart, we can conclude that plays have the highest chance of reaching their fundraising goal if the goal amount is low (less than $1,000).

2) Plays with very high fundraising goals have a far greater chance of failing: The fundraising goal thresholds of $25,000 to $29,999 (20% success rate), $45,000 to $49,999 (0% success rate), and Greater than $50,000 (12.5% success rate) had the lowest success rates of reaching their fundraising goals. From the Outcomes based on Goals chart, we can conclude that plays have a high chance of not reaching their fundraising goal if the goal amount is high.

Limitation of Dataset: 

The Data used for the Outcomes Based on Goals visualization is small. In general, we see an inverse correlation with Fundraising Goal and Success rate. The higher the Goal threshold, the lower the success rate, but we see the success rate triple for the $35,000 to $39,999 and $40,000 to $44,999 goal categories because there is such a small sample size for these categories. For example, the Less than $1,000 goal category has a total of 186 projects. For the $40,000 to $44,999 goal category, there is only 3. Because there are so few data points for the $35,000 to $39,999 and $40,000 to $44,999 goal categories, their success rate appears to be a lot higher than it probably would be if we were working with a larger data set. With a much larger data set, I hypothesize that the Outcomes Based on Goals chart would show an even greater inverse correlation and we would not see the massive spike in success rate for the $35,000 to $39,999 and $40,000 to $44,999 goal categories.

![Outcome Based on Launch Date](kickstarter-analysis/Module 1 Challenge.xlsx/Outcome Based on Launch Date.png)

3) Theater Kickstarter projects that are launched in the summer months are far more successful. The most successful month to launch a Kickstarter Theater Project is May, followed by June and July. From the Outcomes based on Launch Date chart, we can conclude that Theater Kickstarter projects have the highest chance of success when launched in the summer months and a lesser chance of success in the winter months.

Limitation of Dataset: 

Challenge 1 requested that we create the Outcomes based on Goals chart using filtered Kickstarter data that only shows the Plays subcategory. Challenge 1 requested that we create the Outcomes based on Launch Date chart using Filtered Kickstarter data that shows the Parent Category of Theater. Technically, we are not using the same data set for both charts. For a more accurate comparison, we should filter the Outcomes based on Launch Date chart using filtered Kickstarter data that only shows the Plays subcategory.

*Challenge 1 limitation & Observation:

On the Module 1 Challenge page, it says “Louise’s play Fever came close to its fundraising goal in a short amount of time. How many other Kickstarter campaigns were able to do this as well? In this challenge, you’ll conduct a data analysis to answer this question and determine whether the length of a campaign contributes to its ultimate success or failure.” On the same Module 1 Challenge page, as an objective, it says “Interpret the summary data provided from the visualizations” as a part of your analysis. I feel as though we cannot accurately answer the question “How many Kickstarter campaigns were able to came close to its fundraising goal in a short amount of time? (Determine whether the length of a campaign contributes to its ultimate success or failure)” using the summary data provided from the visualizations, because they are not detailed enough.

In order to really look at “How many Kickstarter campaigns were able to came close to its fundraising goal in a short amount of time”, we would need to know how many days passed from the start date of the project (launch date) to the day that the project met its fundraising goal. It appears that we do not have this information. It seems like the deadline (date ended) is when the fundraising time window ended, regardless of if the project was successful or not. To really answer this question, we would need to compare amount of days passed from the start of the funding time window to the day the funding goal was reached to determine how quickly a project met its fundraising goal.

Also, challenge 1 does not have us create a chart to compare the success rate to the duration of the project funding time window. This means looking at the time passed from the launch date to deadline (date created to date ended). Comparing this time duration to if a project was successful or had failed would more accurately help us address the question “Does the length of a campaign contribute to its ultimate success or failure?” The challenge just had us chart the start date of the funding campaigns.
