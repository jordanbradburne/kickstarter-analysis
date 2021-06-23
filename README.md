
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
<img width="866" alt="EX1" src="https://user-images.githubusercontent.com/85847344/123174140-846c2580-d434-11eb-9545-4bd9aaa32169.png">

#As you can see in the photo, the green colors the "successful" outcomes, which means they reached their pledge goal or exceeded it. 
#Red means failed, yellow is cancelled and blue is live.

#I next helpped Louise by setting up her incentives by first determining how much money people have pledged to campaigns historically. So I #added a "Average Donation" Column. And because there was some error with the divison of 0 in some of the averages, I had to create an "if" #statement so that the average would show up as 0.

#Because I know she would benefit from additional visualization of the data, in order to see the outcomes of all the categories, I created #summary tables, charts, and graphs.

#To do this, I first created 2 cloumns that spearates the subcategories from the categories. Then I placed the entire Kickstarter data into 
#its own table. 

#Next I charted the subcategories. By doing this and filtering the chart a certain way, I was able to discover that there were only 604 #Kickstarter campaigns for plays in Great Britain, but the "theater" category was the most successful.

#To make the data easier to understand, I next converted the Unix Timestamps to readable format and then created a new Pivot Chart.
#With this I was able to find out that the month that launched the most successful Kickstarter campaigns was May, but January, June, July and #October all had about the same number of failed campaigns launched.
<img width="185" alt="DATES" src="https://user-images.githubusercontent.com/85847344/123174087-6dc5ce80-d434-11eb-9223-9381d1afa430.png">

#To continue to help Louise plan her campaign, I used filters so that I could update my charts to view data for only theater and plays.
#Also searched for a unique campaign and by doing so, I was be able to pinpoint the ones most similar to Louise's vision. This helped me #research projects similar in scope and type. Their specific data will help Louise's project be successful.

#I used VLOOKUP so Louise could learn about the five plays that she was inspired by at the Edinburgh Festival Fringe and so I could see how #they were funded.
<img width="859" alt="VLOOKUP" src="https://user-images.githubusercontent.com/85847344/123174116-79b19080-d434-11eb-8166-525b9b3777a4.png">





