# Kickstarter_Challenge

## Overview of Project

### Purpose
The main purpose of this project was to analyze different fundraising campaigns in realtion to their launch dates and fundraising goals. We were given the informaiton that Louise's play "Fever" came close to its fundraising goal in a short amount of time. With this in mind we will perform an anlaysis of the specific variables as stated before (Launch Date and Goals). 
## Analysis and Challenges
To start, I had to create four new columns to perform more of an indepth analysis. The first two columns were seprating the Category and Subcategory column into a Parent Category column and a Subcategory column. The next two columns were creatd by converting the Unix tmestamps that were provided on this sheet. This was one of my challenges on this sheet because the code to convert the timestamps were brand new to me. The following code was =(((J2/60)/60)/24)+DATE(1970,1,1) J2 was the first data input of the unix timestamps at launched dates of their fundraisers. 

### Analysis of Outcomes Based on Launch Date
  From the line chart and Pivot table that I created to perform my analysis I have determined that May and June are the two months are have the highest number of successful kickstarters. May had a success rate of about 67% (111 successful/ 166 total) with about a failure rate of about 32%.  While December was the worst month to perfom a fundraiser specifically with category of theatre. Going into a bit more depth, we see December had a 46% failure rate (35 failed/ 75 total). It is safe to say to try to avoid a fundraiser around this time of year. It is also key to note that May and June were the two month with the highest amount of total kickstarter campaigns for thee category of theatre. I am not saying the more fundraisers means a higher success and lower failure rate but we should take notice of that there is a more trend of people starting fundraisers around this time. In conclusion, as an analyst I reccomend Louise that she should perform her fundraiser during the either the two months of May or June, perferablly May as there is historical evidence to provide evidence of this finding. As well my other conculsion is to specificaly avoid the month of December as it does not provide the best funding for theatre kickstarters. 
![](https://github.com/bsamimi25/Kickstarter_Challenge/blob/master/Theatre_Outcomes_vs_Launch.png)
### Analysis of Outcomes Based on Goals
  Within this analysis, we are diving into the subcategory of "plays" looking at their goals they set prior to their launch of their kickstarter. From my analysis, I noticed that for the subcategory "plays" we can see that there is a high number of total projects with a goal of 1000 to 4999. Now we can see that there is a steep drop off after the goal of 5000 to 9999 from 169 total project to 72 within the 10000 to 14999 bracket. We can tell with the subcategory "plays" it is common not to pass the 10000 territory based on this data, yet there are still plays who have as so. Now focusing on the percentages I created, the goal of less than 1000 provided the highest success rate of 75.81% therefore leading to the smallest failure rate of 24.19%. What I find interesting is that the 1000 to 4999 bracket had the highest amount of total project, 534, and had a very close success rate to the less than 1000 bracket, with percentage being 72.66%. Moving down the Goal column we can see there is not a lot of total project as for the subcategory "plays" not as much funding is needed and therefore we see that there have been **no canceled** plays within this data set. In conclusion, it is best to set her bracket of fundraising to be between 1000 and about 5000, as we see the highest success within this bracket.The line graph I created show the varibalilty between the different brackets and can see visually what I have already stated. 

![](https://github.com/bsamimi25/Kickstarter_Challenge/blob/master/Outcomes_vs_Goals.png)


## Results 

1. What are two conclusions you can draw about the Outcomes based on Launch Date?

My first conculsion I can draw from the Outcomes based on Launch Date analysis is that May and June are the two months that provide the best funding for the category theatre.My second conclusion is that to specifically avoid the month of Decemeber as it does not provide the best funding for these type of kickstarters. 

2. What can you conclude about the Outcomes based on Goals?

With my analysis of the Outcomes based on Goals variable we can see that the bracket of 1000 to about 5000 has the best rate of success and has the highest amount people performing for fundraisers for their plays, which was the focused subcategory here. Therefore havign a fundrasing goal inbetween 1000 to 5000 can provide the best outcomes and highest chance of meeting ones goal. 

3. What are some limitations of this dataset?

One limitation of this dataset was that we did not see if the play provided had high reviews leading to a high success rate of completing ones goal. it makes sense if the play script is not highly reguarded and does not make the goal since people do not want to watch or even perform this act. 

4. What are some other possible tables and/or graphs that we could create?

We could have made many possible charts as we could have made a linear regression simply by putting the successful varibale as our dependent feature and the number of backers as our independent feature, with other independent varibales tryting to explain what it means to have a successful fundraiser on average. With this approach we are lacking many varibles to try to explain what it means to be successul, thus we would hava lot of "noise" or errors in for regression. But it does not hurt just to see and get a preliminary start. 
