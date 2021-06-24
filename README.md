
# An Analysis of Kickstarter Campaigns
#Performing analysis on Kickstarter data to uncover trends

#The purpose of this analysis is to help out a up and coming playwright Louise.
#She wants to start a crowd funding campaign to be able to fund her play _Fever_
#She has an estimate budget of a bit over 10 grand.

#The goal of this project was to help Louise determine whether there were specific factors that make a project's campaign successful.
#I used excel to analyze current cite data to help her understand her own campaign fund better so she could to mirror other
#successful campaign funds (within the same category).

#First I organized the data so that it could be more easily understood and, therefore, generate insights that help Louise's project. I acommplished this by using filters and formatting, and by freezing specific columns and rows.

#Next I added a Percentage Funded column in order to refine the visual presentation of the data in the worksheet and to provide Louise with #information at a glance along with using value shading to customize the worksheet for the same reasons.
#For example:
<img width="866" alt="EX1" src="https://user-images.githubusercontent.com/85847344/123174140-846c2580-d434-11eb-9545-4bd9aaa32169.png">

#As you can see in the photo, the green colors the "successful" outcomes, which means they reached their pledge goal or exceeded it. 
#Red means failed, yellow is cancelled and blue is live.

#I next helpped Louise by setting up her incentives by first determining how much money people have pledged to campaigns historically. So I #added a "Average Donation" Column. And because there was some error with the divison of 0 in some of the averages, I had to create an "if" #statement so that the average would show up as 0.

#I know she would benefit from additional visualization of the data so, in order to see the outcomes of all the categories, I created summary #tables, charts, and graphs.

#To do this, I first created 2 cloumns that spearates the subcategories from the categories. Then I placed the entire Kickstarter data into 
#its own table. 

#Next I charted the subcategories. By doing this, and filtering the chart a certain way, I was able to discover that there were only 604 #Kickstarter campaigns for plays in Great Britain, but the "theater" category was the most successful.

#To make the data easier to understand, I next converted the Unix Timestamps to readable format and then created a new Pivot Chart.
#With this I was able to find out that the month that launched the most successful Kickstarter campaigns was May, although January, June, July #and October all had about the same number of failed campaigns launched.

<img width="185" alt="DATES" src="https://user-images.githubusercontent.com/85847344/123174087-6dc5ce80-d434-11eb-9223-9381d1afa430.png">

#To continue to help Louise plan her campaign, I updated my charts, using filters, to view data for only theater and plays.
#I also searched for a unique campaign, and, by doing so, I was be able to find the ones most similar to Louise's vision. This helped me #better understand the my project by researching projects similar in scope and type. Their specific data will help Louise's project be #successful.

#I used VLOOKUP so Louise could learn about the five plays that she was inspired by at the Edinburgh Festival Fringe, and so I could see how #they were funded.

<img width="859" alt="VLOOKUP" src="https://user-images.githubusercontent.com/85847344/123174116-79b19080-d434-11eb-8166-525b9b3777a4.png">


#I also made sure to add statistical components in order to provide an unbiased view of the data. This is so I could make further conclusions based on actual calculations. I started with finding the measures of central tendency: mean, median, and mode.

#I then needed to consider Kickstarter campaigns for plays in the U.S. and compare failed versus successful campaigns.

<img width="302" alt="SvsF" src="https://user-images.githubusercontent.com/85847344/123206280-442a9880-d470-11eb-8c45-cf6c65309e51.png">

#Looking at just the mean, median and mode in the table above, it was clear that the failed Kickstarter campaigns had much higher fundraising #goals than successful Kickstarter campaigns. Louise wanted over two times the average successful Kickstarter goal, so this meant bad news for #her. Also, the mean and median pledged amounts were lower than the successful pledges, so, basically, the failed Kickstarter campaigns were #unsuccessful for reasons other than asking for too much money. It was possible that the "failed" just asked for too high of a price. The #median was much lower, so there had to be something else keeping people pledging to those failed projects. 

#To do this, I helped Louise measure the spread of the dataset by looking at the range as well as adding standard deviation and variance (more #statistics to our analysis).

#Based on these statistics, I determined that the mean of each distribution was around the 3rd quartile, which meant that the data followed #similar distributions in each subset.
#The standard deviations were larger than the mean, which meant that everything below the mean is considered "close" to the center.
#The standard deviations were all about 2 times the IQR in each distribution, except for in the failed Kickstarters. The standard deviation #for failed was closer to three times the IQR. This indicated that there had to be some failed Kickstarters with very high goals.

#One of the last pieces I helped Louise with was finding the outliers of the dataset so we couls eliminate extreme data points that are not #representative of the data we want in order to better her campaign. 

#Louise was also interested in Great Britain's theater, especially musicals, market. She did commit to creating a play in the U.S., but was #also interested in researching musicals in Great Britain. This information wasw for her future projects with an estimated budget of £4,000. #To present this information I created a boxplot.

#Based on these findings, Louise will definetly want to launch her campaign in early June and since Louise wanted over two times the average #successful Kickstarter goal, I would reccommend to potentially lower her goal.


