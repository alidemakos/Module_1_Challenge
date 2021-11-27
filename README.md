# Module_1_Challenge
## Overview of the Project
### In this project, I am helping my client Louise whose play fever nearly reached its fundraising goal. Using data on how different campaigned performed considering their launch dates and fundraising goals, we will be able to give Louise more perspective on what makes a project more likely to be successful. 
## Deliverable 1
### First, I analyze the outcomes based on launch date. To create this “Outcomes Based on Launch Date” chart, I created a pivot table that filtered by Parent Category and Years. Parent Category was given in the original data set, and Years was found using the Years function and Date Created Conversion. The Rows of the Pivot Table list the months of the year and the columns show the possible outcomes: successful, failed, and canceled. The pivot table values reveal a total count of each outcome. By filtering the Pivot Table by theatre, we get information that is more relevant to Louise’s campaign.
![Theatre_Outcomes_vs_Launch](https://user-images.githubusercontent.com/93489055/143720840-5ac895c4-dfe8-4855-992c-0a10c2998393.png)
## Deliverable 1: Analysis
### Deliverable 1 shows that May is the historically most successful month to launch a theatre campaign, followed by June, then July. This is partly due to more campaigns being launched in these summer months, in general. The worst month to historically launch a theatre campaign shows to be December, as there is almost the same number of successful and failed campaigns launched in this month. All projects have over a 50% chance of succeeding historically, other than December, which cancelled and failed projects total is greater than the number of successful projects. The chart shows that most months have a similar number of canceled projects, other than January which has around twice as many as the others. The Year filter was not required specifically in the analysis, but it can be used to look at more current data by excluding more ancient years. 
## Deliverable 2: Challenges
### This analysis of considering the number of successful, failed, and cancelled theatre campaigns based on months has some limitations. Like previously mentioned, analyzing the number of successful projects does not consider the total number of projects launched in that month in comparison. For example, the month of August has 1 more successful campaign than the month of, but August has 7 more failed and 2 more cancelled than April. In this sense, it seems that April is a better month to launch a campaign, despite August having more success stories. To enhance this analysis, I would consider the rate of successful projects within each month, instead of a mere count. I would also consider the failure rate and cancelation rate. To visualize this, I would order months from most successful rate to least successful rate to demonstrate to Louise which month there is a greatest chance of success. 
## Deliverable 2
### Next, I analyzed the outcomes based on goal. In this case, the goal is a fundraiser goal, in other words, the amount of money each campaign aimed to raise. To create the “Outcomes Based on Goal” line chart, I used the Count If function for certain ranges of goals to find a count of the number of successful, failed, and canceled based on each goal. Then, I found the total number of projects for each goal using the Sum function. Unlike the previous analysis, we took the analysis a step further by finding the percentage successful, percentage failed, and percentage canceled based on ratios.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/93489055/143720859-c3e0d4c8-f502-473c-b315-4f9cf80b8fdd.png)
## Deliverable 2: Analysis
### This deliverable shows that projects with a goal of less than $15,000 were more likely to be successful than not. With a goal of exactly $15,000, there is an equal chance. Projects with goals greater than $15,000 and less than about $32,500 are more likely to fail than succeed. The data shows that projects with goals greater than about $32,500 and less than about $40,000 are more likely to succeed than fail. Projects with goals greater than $45,000 are much more likely to fail than succeed. Most of this analysis is intuitive: the smaller than goal the more likely it will be able to be reached. The deviation in this goal is likely because there were many less projects with goals between about $32,500 and $40,000, so the analysis here is less meaningful. Based on the chart, it seems that the most unsuccessful goal range is between $45,000 and $49,000, showing a 0% success rate and a 100% failure rate, but it must be noted that this was based on the failure of only 1 project. In general, it seems that the lower a theatre projects goal is, the more likely its chance of succeeding will be. Also, there are no canceled theatre projects of any goal, which is an interesting statistic.
## Deliverable 2: Challenges
### This analysis clearly has some limitations. To enhance the analysis, I would suggest highlighting a count of projects for each respective goal, so someone viewing the data would not be misled by the success rate of projects with higher goals. I could do this using a data table or clustered colunmn.
