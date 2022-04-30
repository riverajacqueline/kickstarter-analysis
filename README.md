# Kickstarting with Excel

## Overview of Project
Kickstarter is a crowdfunding platform that raises money from large groups of people via the internet to fund creative projects all over the world.

We will be looking at trends for specifically plays in the years of 2009 to 2017.

### Purpose
For this project, our client Louise is looking to create a campaign for her upcoming play, "Fever", where we are to provide her data on the outcomes of successful versus failed play campaigns based on their launch dates and funding goals.

## Analysis and Challenges
Upon getting the data, we needed to further organize it to put "categry" and "subcategory" into separate columns. This helped fully organize the data more so we could look at the trends for specifically theater and plays. 

### Analysis of Outcomes Based on Launch Date
To create an analysis of Theater Outcomes Based on Launch Date, a pivot table needed to be created outlining the dates of launched kickstarters campaigns, months of the year, outcomes of successful, failed and canceled, and lastly filtering the parent category to "theater" only.

![Pivot_Table](https://user-images.githubusercontent.com/103764279/166123528-5dbb2830-9f05-493b-9e7a-c5731382f940.png)

In order to visualize this data from the pivot table, a line chart can be created to represent the launch month of theater kickstarter campaigns and their outcomes.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/103764279/166123700-1940f460-0363-482a-9771-b6dccc1cab9d.png)

Based on this data, it can also be inferred that most of the successful kickstarter campaigns were launched between the months of April and May. The line chart also shows that launch dates between the months of November to January, led to a decrease in successful kickstarter campaigns. It can deduced that during the Holiday season, there are less successful kickstarter campaigns.

### Analysis of Outcomes Based on Goals
To create an analysis of Outcomes Based on Goals, we had to create an analysis of the percentage of successful, failed, and canceled plays based on the kickstarter campaign funding goals. In a new worksheet, a table needed to be created with ranges from less than $1,000 to more than $50,000. From there, the countifs fuction helped pull data with the specific goal ranges and with the subcategory of only "plays" for the outcomes of successful, failed, and canceled campaigns. With this data, the number of total projects for each goal range could be determined, which then helped calculate the percentage of each goal range and outcome. To visualize this data, a line chart can be created to show the relationship between the percentage of each outcome based on their goals.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/103764279/166124378-03ffb19d-d556-45d0-8f0e-7a44a5986251.png)

### Challenges and Difficulties Encountered

One challenge that occured was being able to create pivot tables and charts in order to examine the data. Without any prior knowledge in Excel, trying to figure out which data went to what parts of the pivot table and charts was a bit of a challenge.

The countifs statements were also challenging. It was hard at first getting the statement to produce what I had intended, but after a bit of trial and error, I finally got it.

Lastly, GitHub was very confusing to use at first, especially when I saw that we had to write our results on here. It was definitely intimidating but after reading some documents, doing some research and going over some of the markdowns, it became easier.

## Results

#### What are two conclusions you can draw about the Outcomes based on Launch Date?

1. The data shows that the best time to launch a successful campaign would be in May or June. May showed to the the highest number of successful campaigns at 111, whereas December had the least amount at 37.
2. Starting in October, the data shows a steady decline until December. This shows that kickstarter campaigns were least successful in the winter months. This could be due to the Holiday season.

#### What can you conclude about the Outcomes based on Goals?

- The analysis concludes that kickstarter campaigns with funding goals of $5,000 or less have a higer success rate. Kickerstarter campaigns with funding goals of $10,000 and more had a higher failing rate. 

#### What are some limitations of this dataset?

- I think it would be interesting to see if gender or age of backers was a factor. If a target audience could be acquired, then maybe higher funding goals would be more successful.

- How were these kickstarter campaigns being advertised? Were the successful kickstarter campaigns using better stategies to help market their campaign vesus the failed ones? It would also be interesting to see how that could effect the outcomes.

#### What are some other possible tables and/or graphs that we could create?

- Other tables and graphs that can be created to compare other countries Theater/Play outcomes to the US. This would give a better idea how successful campaigns like this are around the world and what their funding goals are.
