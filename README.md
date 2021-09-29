# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends

# Overview of Project
The objective of the project is to know how different campaigns went in relation to the launch date and the fund goal of each play. This analysis will show the outcomes based on the launch date and fund goals.

# Analysis and Challenges
The first part of the analysis is to show the outcomes based on the launch date of the campaign. These outcomes are: successful, failed, and canceled.
A dynamic table was made to show all the campaigns for theater that were launched each month according to the final result, then I did a graph (line char) to show the relationship between outcomes and launch date
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/90527537/135199852-be47b0b7-b646-454e-acc0-463b0805c5b5.png)

For the second part of the analysis it was requested to count the number of success, canceled, and failed plays based on the funding goal. And this is were I encountered with a challenge using the formula 'COUNTIFS()' in Excel. This formula helps to count the number of cells specified using a set of conditions. So the first condition is if the play is successful, canceled or failed, the second condition is if the campaign is only for plays, and the third condition is based on a dollar amount ranges.
My problem was when I wanted to determine the dollar amount ranges, so I dit it manually. See figure 2
![Screen Shot 2021-09-28 at 22 57 02](https://user-images.githubusercontent.com/90527537/135200888-f07c5bad-28b6-442d-8328-586765e767f7.png)

But twe outcome was the expected. After all the analysis using the countifs formula I made a line chart to visualize the relationship between the goal amount ranges and the percentage of successful, failed, or canceled plays.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/90527537/135201097-63166ea2-cff8-44d6-b0b2-fe8c7af6f779.png)

# Questions
## >What are two conclusions you can draw about the Theater Outcomes by Launch Date?
May is the month with the most successful plays. So if Louise is looking to launch a new play, she needs to launch on May in order to have a better successul rate.
Also, since July the successful amount of plays went down and the failed went up, maybe is because of the season. When it's holiday season successfull plays tends to descend, like in December.

## > 2. What can you conclude about the Outcomes based on Goals?
When the funding goal amount is a lot higher, the percentage failed is higher too. That means that when the goal is lower or the play needs a lower budget the percentage of being successful is better.

## > 3. What are some limitations of this dataset?
Maybe not limitations, but the way it was captured was not the best because some adjustments had to be made.

## > 4. What are some other possible tables and/or graphs that we could create?
It would be helpful to Louise if she can get the type of play (musical, comedy, etc.) in order to see which play has the better successful rate.
