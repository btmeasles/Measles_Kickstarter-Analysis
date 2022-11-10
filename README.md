## Module 1 Challenge
# **Measles_Kickstarter-Analysis**

# Kickstarting with Excel

## Overview of Project

### Purpose
    The Purpose of this project was to organize and analyze the data of many different Kickstarter projects in order to find what characeristics  were shared between successful and failed projects. By filtering the data to show at what time of the year Kickstarters for Plays were launched, and how much the Kickstarter projects were asking for, we can begin to see a pattern of the most successful Kickstart campaigns, as well as what to avoid.
## Analysis and Challenges
    Challenges arose from filtering certain characteristics of the data in order to show it in a way that made sense. The data is all there, and once filtered down, it was readily accessible, but communicating that visually via a PivotTable and Charts was difficult.

    The final Line Chart also gave me problems, simply because of the math required. Rather than trying to show the percentage of 'Failed' and 'Successful' projects as part of the each goal bracket, I tried showing them as a part of the Grand Total. The result looked like this: 
![](../../../../../c:/BootCamp/Class%20Projects/Module%201%20-%20Excel%20Dataset/Measles_Kickstarter-Analysis/Resources/Original_OutcomesBasedonGoals_Failed.png)

    Admittedly, it's hard to decipher exactly what's going on, and the data doesn't seem to correlate with anything very well.   


        
### Analysis of Outcomes Based on Launch Date
    Upon reviewing the data of Theater Kickstarters, a total of 111 projects were successfully funded when the launched the campaign in May, as seen here:
   ![Alt text](../../../../../c:/BootCamp/Class%20Projects/Module%201%20-%20Excel%20Dataset/Measles_Kickstarter-Analysis/Resources/Theater_Outcomes_vs_Launch.png)  

   With 111 Successful campaigns started in May, it was the best month by quite a lot. However, the other summer months of June and July were also good to launch in. 
   Easily the worst month to launch would be December. Most likely due to Holiday spending, most people would have little if any extra money at the time to be able to fund a Kickstarter project. Even though 37 campaigns launched in December were successful, 35 launched during that same time failed, with a nearly 50/50 ratio being far too risky.

### Analysis of Outcomes Based on Goals
    When deciding how much money to ask for before a project is fully funded, this data was both revealing and surprising.

![](../../../../../c:/BootCamp/Class%20Projects/Module%201%20-%20Excel%20Dataset/Measles_Kickstarter-Analysis/Resources/Outcomes_vs_Goals.png)

    The goal range with the most success-to-failure ratio was 'Under $1000'. While a project with such a minimal goal would be easily attainable, and certain plays certainly can be produced for that little amount, it seems unlikely that anything of a professional-caliber would be produced for under $1000.
    Looking to higher budgets, the next area we see success in is goals set between $35k and $44,999. With 2/3 of the campaigns launced succeeding, this goal bracket had the next widest success ratio of this chart. Interestingly, goals from $25k to $35k had quite a dramatic trend toward failure. 
    There seems to be quite a risk either way, because the success ratio based on goals takes another very steep decline when asking for "$40k-$45k" and anything above $45k. 100% of the projects that asked for $45 to $44999 failed, with only marginally better success when asking for $45k and more.
### Challenges and Difficulties Encountered
    The challenges I came across were a matter of detail. Making sure every formula was precisely correct made it difficult, and with so much data, it could be daunting to begin troubleshooting where things went wrong. As stated above, the math in order to get the percentages correct was a huge problem in the second chart. 
    I also disovered "Locked Reference" which is specifically an Excel function. Before I knew about it, I would try and copy-paste my formulas from one column to another, and the Cell values therein would incrementally increase. It took quite a bit of research to discover how to stop it from doing that, as I did not know what to call it or how to search for it. However, once I did figure it out, I also discovered that the ability to utilize it is a valuable tool.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
     - A project launced in May will have the highest chance of Success.
     - A project launched in December will have highest chance of Failure.
- What can you conclude about the Outcomes based on Goals?
     - Asking for smaller amounts of money does not guarantee success. The success ratio declines steadily past a goal of $1,000.
     - When asking for a larger sum of money, between $35k and $45k has a slightly higher success rate.
- What are some limitations of this dataset?
     - I believe that the Country from which these projects are originating would make quite an impact on the overall outcome. I believe the city for which the end production will be staged (if the project is a play, for example), would also make an impact. People would be more likely to fund a big budget play in New York City or London than in more rural areas, where smaller budgets would be more attainable.
- What are some other possible tables and/or graphs that we could create?
     - Successful campaigns based on Genre and asking goal.
    - Author/Producer/Director of the successful plays within a given area or time frame (are they well known, or an up-and-comer?)
    - How long the campaign was going before it reached its goal, cancelled, or failed? If a play asks for $100k, but the campaign is only open for two weeks, I doubt it would matter when it was launched, as it would probably not have a chance to recieve much funding during a that short a time.
