# An Analysis of Kickstarter Campaigns
#Performing analysis on Kickstarter data to uncover trends

#The purpose of this analysis is to help out a up and coming playwright Louise.
#She wants to start a crowd funding campaign to be able to fund her play _Fever_
#She has an estimate budget of a bit over 10 grand.

#The goal of this project is to help Louise determine whether there are specific factors that make a project's campaign successful.
#We will use excel to analyze current cite data to help her understand her own campaign fund better in order to mirror other
#successful campaign funds (within the same category).


#First I organized the data so that it could be more easily understood and, therefore, generate insights that help Louise's project. I acommplished this task by using filters and formatting, and by freezing specific columns and rows.

#Next I added a Percentage Funded column in order to refine refine the visual presentation of the data in the worksheet to provide Louise with #information at a glance along with using value shading to customize the worksheet for the same reasons.
#For example:
![EX1](path/to/EX1.png)
#As you can see in the photo, the green colors the "successful" outcomes, which means they reached their pledge goal or exceeded it. 
#Red means failed, yellow is cancelled and blue is live.

#I next helpped Louise by setting up her incentives by first determining how much money people have pledged to campaigns historically. So I #added a "Average Donation" Column. And because there was some error with the divison of 0 in some of the averages, I had to create an "if" #statement so that the average would show up as 0.

#Because I know she would benefit from additional visualization of the data, in order to see the outcomes of all the categories, I created #summary tables, charts, and graphs.

#To do this, I first created 2 cloumns that spearates the subcategories from the categories. Then I placed the entire Kickstarter data into 
#its own table. 

#Next I charted the subcategories. By doing this and filtering the chart a certain way, I was able to discover that there were only 604 #Kickstarter campaigns for plays in Great Britain, but the "theater" category was the most successful.

#To make the data easier to understand, I next converted the Unix Timestamps to readable format and then created a new Pivot Chart.
#With this I was able to find out that the month that launched the most successful Kickstarter campaigns was May, but January, June, July and #October all had about the same number of failed campaigns launched.



