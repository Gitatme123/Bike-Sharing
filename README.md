# Bike-Sharing
In order to propose our Bike-Sharing program to investors, we must prepare an analysis for one of our key stakeholders. In this challenge we analyze the vizualizations we've created in order to uncover significance and to answer key questions.

## Purpose
####
The purpose of this assignment is to analyze data from NYC Citibikes in order to ascertain the feasibility of opening a bike sharing program in Des Moines, Iowa. We need to use our data to create vizualizations in Tableau that contribute to our analysis and our pitch to the investors.

## Results
#### The following graphs and charts contribute

1. The first graphic we see here is the total number of unique bikes being used in NYC currently. This number represents every unique Bike ID with at least one data point for "Starting Time". This is quite a few bikes, but without supporting data, it doesn't mean much more than just the total bikes used in circulation during the time period the dataset was taken from.
><img width="247" alt="Screen Shot 2022-04-02 at 4 45 32 PM" src="https://user-images.githubusercontent.com/95602006/161662300-6bccc96c-cb21-42c6-87f5-830b6c9c43a3.png">

2. The 2nd graph we are looking at is a breakdown of users by gender, listing the total as well as the % of total. It is clear that males make up the majority of the users, at 65%. This chart can be used in comparison to the average time a user uses a bike for by gender to determine significance.
><img width="274" alt="Screen Shot 2022-04-02 at 4 42 49 PM" src="https://user-images.githubusercontent.com/95602006/161662306-5db8826b-9490-4b48-aa3d-f99fcf7f7dd1.png">

3. The 3rd graph shows us the number of trips a single bike is taken on average during this window of time. It looks like quite a few bikes aren't used at all. It also looks like a large number of bikes are used quite a bit, but not too many times. It looks like on average a bike is used about 300 times, but we would need more supporting data to draw significance from this.
><img width="1131" alt="Screen Shot 2022-04-02 at 4 45 22 PM" src="https://user-images.githubusercontent.com/95602006/161662361-62ecf0bd-8a17-4a31-b2b5-4344ceead2ac.png">

4. The 4th graph shows us check out times for subscribers vs. non-subscribers. The immediate value I see here is that at its peak, there are about 830% more subscribers using the bike at once than non-subscribers. The business must be working well to have that many subscribers, signalling to me that the system is used for more than just tourists. The locals would therefore make up the majority of users. The average time a subscriber uses a bike is between 5 and 25 minutes. Most subscribers use the bike for only 10 minutes which makes me think this is a consistent trip the individual makes.
><img width="1133" alt="Screen Shot 2022-04-02 at 4 43 25 PM" src="https://user-images.githubusercontent.com/95602006/161662313-ee35a9b0-8214-4c13-abc2-7174878cd592.png">

5. The 5th graph shows us the average trip time broken down by gender. It is clear Men use the bikes for a longer amount of time than women do. Maybe the bike isn't comfortable for women and therefore they use it and quickly disembark from it? There could be many benefits to continuing down this rabbit hole.
><img width="1131" alt="Screen Shot 2022-04-02 at 4 43 35 PM" src="https://user-images.githubusercontent.com/95602006/161662325-3e4f1688-41b2-41bd-9f3b-9349ee60b3b5.png">

6. The 6th graph shows us trips by weekday by hour. It is clear that bikes need to be available at 5am because there is an incredible rush from 6am until 9am. After that the bikes can be serviced during the week if needed. Service should happen between 1am and 4am on weekdays to avoid the strongest times of day.
><img width="598" alt="Screen Shot 2022-04-02 at 4 43 43 PM" src="https://user-images.githubusercontent.com/95602006/161662337-39596c75-69fa-4568-ab13-ca063affc32a.png">

7. The 7th graph shows us a breakdown of startitmes by gender. It is clear that men and women ride during the same times. They ride between 6am and 9am, and then between 3/4pm to 8pm. It is very odd to me that the only break in the week is on Wednesday evenings where the traffic is not the same as what it is the other 4 weekdays at this time. This could easily be explained with a little more digging! 
><img width="1455" alt="Screen Shot 2022-04-02 at 4 45 10 PM" src="https://user-images.githubusercontent.com/95602006/161662347-84859a7c-1ff9-4de4-8cf7-4a8444166ca8.png">

8. The 8th graph shows us user trips by gender by weekday by usertype. It shows me that subscribers must enter in a gender because there is almost no data for unknown subscribers. Men ride the bike the most on Thursdays, and the least on Sundays (because sports are on lol!). 
><img width="387" alt="Screen Shot 2022-04-02 at 4 45 45 PM" src="https://user-images.githubusercontent.com/95602006/161662383-9605c97b-7d02-421c-9930-c00b27dc4cba.png">

9. The 9th graph shows us a cluster map of startimes with circle size and location denoting the concentration of data to that specific point. The obvious takeaway here is that the big hubs are by other transportation sources. Without putting more layers onto this map, its hard to tell the significance, especailly because Des Moines is nothing like NYC lol!
><img width="1297" alt="Screen Shot 2022-04-02 at 4 46 03 PM" src="https://user-images.githubusercontent.com/95602006/161662472-0da183dc-06c2-44ad-8e7a-eb1258bf6ae5.png">


## High Level Summary
* My conclusion is that this is not a good analysis to determine the feasibility of opening a bike sharing program in Iowa. The data that we presented in graphs is extremely surface level, and must be explained with multiple other variables. The best way to do this analysis would have been to make a dashboard with all of the necessary filters on each chart, in order to cross examine the significance of certain variables. NYC is nothing like Des Moines geographically or diversly, and income in NYC is a great topic of conversation, and we know nothing about Des Moines income data. This could greatly contribute to the success of the bike sharing program in NYC, and could completely undermine the program in Iowa. More data needs to be analyzed in order to properly analyze this opportunity.


#### 2 additional visualizations I would like for further analysis
    1. A chart that shows the lifecylce of a bike. The average number of people that touch it a day, and how long it is ridden until its serial number no longer records rides.
    2. I would want to see the subscriber repeat ratio. How many times an individual rides in a given month, quarter and year.
    3. I would want to see a visualization for the different months of the year that bikes are utilized. As this analysis required us to create breakdowns by weekday, I think bringing in an analysis by month would be equally as important.
