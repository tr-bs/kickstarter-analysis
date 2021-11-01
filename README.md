# Kickstarting with Excel

## Overview of Project
International datasets of a variety of kickstarter campaigns are analyzed to take a deeper examination for a client interested in future project planning of theater production.

### Purpose
With an understanding of kickstarter trends for theater production, the client can plan the budget and time of the kickstarter that needs to be created. 

## Analysis and Challenges

Despite a wide variety of data sets, the themes of the theater production were not explored and could benefit the organizer to know which genres are most financially supported. Since the data set includes international statistics, a closer look within respectives countries were not accounted for.


### Analysis of Outcomes Based on Launch Date
May was the most successful month of the year to launch campaigns with 111 successful campaigns within a total of 166 campaigns. With 100 successful campaigns, June was the second best month to launch a campaign. Despite May also having the highest amount of failed campaigns, the month also had the most amount of campaigns launched. The most relatively high amount of failed campaigns occured during the month of October. December had similar amounts of successful and failed campaigns, respectively at 37 and 35. 

### Analysis of Outcomes Based on Goals
A goal of less than $1000 was the most successful. However, most projected goals were within the $1000 to $4999 range. This range was also the second most successful. The least successful goal was at $45,000 to $49,999 with a 100% fail rate, however, there was only one project that attempted that goal. At the range of $15000 to $19999, the success rate falls down to 50% and steadily decreases as the goal increases in price range. 

### Challenges and Difficulties Encountered
Initially, during the creation of the sheet for Outcomes Based on Goals, I was manually filtering the Kickstarter worksheet and then obtaining those values. This created a data set dissimilar to the graph that was provided with the correct values. I removed all the filters and typed in the the proper COUNTIFS() functions to create the correct data set. With that resolved, the graph became the same as the example. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date? 
- The highest peak of launch for theater kickstarters was during May, while June follows closely. Due to these, high numbers, it would be best to launch a kickstarter during those two months. May also includes the most failed campaigns, but the contrast in comparison to the successful campaigns are stark. 
- July and October tie in the second highest months that have failed campaigns so those two months are the least desirable to start a campaign.
---
- What can you conclude about the Outcomes based on Goals?
- At 76%, the most succesful goal amount was less than $1000. The range of $1000 to $4999 was also relatively successful at 73%. So the ideal goal range for success is less than $4999. While the total number of projects decreases for higher range goals, there is a higher percentage of failed campaigns. The highest percent of failed campaigns are ones with goals of 25 k to 29k and 45 k to beyond.
---
- What are some limitations of this dataset?
- The dataset could provide more information about the kickstarters such as which genres were the most popular and other values such as attendance rate of the actual event. Another value that can be understood is the duration of these campaigns and if length can be a contributing factor to success or failure.
---
- What are some other possible tables and/or graphs that we could create?
- Another table that could be created can show how the data changes throughout the years rather than looking at the cumulative data of all the years. A graph can also be made for the outcome based on goals for a visual aid of the statistics.
