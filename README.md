<div align="center">#Performance of Kickstarter Funding Campaigns 2009-2017, by Launch and Goal

##Purpose:
This report examines the link between success of Kickstarter campaigns for plays in meeting their fundraising goals based on launch dates and goals, as an initial assessment of the performance of the campaign for the play “Fever,” that came close, but failed, to meet its fundraising goal.

** Bottom Line Up Front (BLUF): Most Kickstarter campaigns for Theatre projects succeed. However one should carefully consider whether to launch one during I meant the December or January. Ambition should also be restrained if our preliminary analysis is to be believed.  It is probably not that the rate of success generally diminishes with the amount of funding sought.  Micro-projects under $1000 are most likely to succeed. **

**Analysis and Challenges **
## Data
We were able to look at 4114 Kickstarter campaigns conducted between 2009 and 2017.  For each campaign the data included, __ inter alia__, the:
- category of project,
- subcategory of project,
- funding goal,
- funds pledged,
- an outcome code,
- launch date.

The outcome code included four categories:
- successful—if funds pledged were greater than funds sought,
- failure—if funds pledged were less than funds sought,
- cancelled—presumably the campaign was dropped and any funds pledged were not collected,
- live—that is ongoing campaigns.

The campaigns fell in nine categories:
- film & video
- food
- games
- journalism
- music
- photography
- publishing
- technology
- theater

The theater category was broken down in three subcategories:
- musical,
- plays,
- spaces.

For reference, the campaign that motivated this analysis was for the play “Fever” and the relevant data above were:
      category: |theater
      subcategory: |plays
      funding goal: |$2,885
      funds pledged:|$2,485
      outcome code:|failed
      launch date: |June 16, 2016

## Process

As this was an initial assessment with a short deadline we followed a failure tightly scripted methodology to assess the link between the outcome variable and data on launch date and funding goal, as follows:
- We filtered the data to look only at the theater campaigns.  As this included “Fever,” it appears a valid reference group.  There were 1369 theater related campaigns we examined, this did not include the 24 ongoing campaigns.
- Looking at all the data from all years and countries, we constructed a table showing the number of campaigns that either succeeded, failed, or were canceled by month.
- To make the relationship with time more apparent, we created a chart to look for trends, if any over time.  (Both the table and chart are displayed under findings below.)
- We used the same data to construct another chart showing the number of successful, failed, or canceled campaigns against initial funding goal.  As funding is a continuous variable, we established $5,000 ranges as groups of comparison.  We also broke up the a group of micro-campaigns under seeking less than $1,000, and stopped looking at discrete ranges of $5,000 for any goal over $50,000.
- Finally, to again see if a visualization of the chart would suggest any relationships we created a chart reflecting the table (also below).

##Outcomes Based on Launch Date

Successful |failed| canceled| Grand Total
Jan|54|38|3|95
Feb|79|34|2|115
Mar|63|34|3|100
Apr|64|42|2|108
May|108|54|6|168
Jun|93|52|3|148
Jul|90|50|4|144
Aug|77|45|3|125
Sep|57|33|4|94
Oct|64|45|4|113
Nov|54|31|2|87
Dec|36|35|1|72
Grand Total|839|493|37|1369

The table showing outcomes against the month in which the campaigns were launched requires some close readings to tell one much about the relationship between launch month and odds of success, most of the information here is more easily picked up in the chart below.  Two lessons do stand out about the data set as a whole, as opposed to relationship between success and timing, though.
- Good news!  Most kickstarter campaigns succeed!  Over 60% of them.  And it is true that regardless of month launched your odds of success are greater than your odds of failure, though those odds do vary considerably by month.
- There is wide variation of how many campaigns are launched each month.  The holiday season probably explains why December has the lowest number of launches at 72 (and fewest successes at 36).  Whereas May is the height of the busy season, with 168 of the campaigns in our data set being launched in that month.

!("C:\Users\newho\OneDrive\_GW DATA BOOTCAMP\Module 1\MODULE ONE CHALLENGE\resources (PNG charts)\Theater_Outcomes_vs_Launch.png")
Visualizing this data allows us to recognize other qualities of the relationship of success and launch month.
- The fact that most campaigns succeed can be seen in the fact that the blue line representing successes is above the orange line of failures across the full year.

Four months stand out, two good, two bad.
      -The Bad: December and January are clearly not good for starting kickstarter campaigns, the gap between those two loans shows there very low success and consequently high failure rates.
      -The Good: February is truly a stand out.  Almost 70% of campaigns launched in February reach their goal.  May, the busiest month is also good, but while the overall number of successful campaigns is higher, the success rate is modestly lower, at 64%, than February.
      -Outside these exceptions, the rate of success doesn’t vary much by month ranging from 56 up to May’s 64.

##Outcomes Based on Goals
Goal|Number Successful|Number Failed|Number Canceled|Total Projects|Percentage Successful|Percentage Failed|Percentage Canceled
<  $1,000|159|53|3|215|74%|25%|1%
$1,000-$4,999|159|176|5|340|47%|52%|1%
$5,000 - $9,999|120|94|4|218|55%|43%|2%
$10,000 - $14,999|50|53|5|108|46%|49%|5%
$15,000 - $19,999|17|18|6|41|41%|44%|15%
$20,000 -  $24,999|13|20|1|34|38%|59%|3%
$25,000 -  $29,999|11|15|2|28|39%|54%|7%
$30,000 -  $34,999|4|9|2|15|27%|60%|13%
$35,000 - $39,999|6|2|0|8|75%|25%|0%
$40,000 - $44,999|4|2|0|6|67%|33%|0%
$45,000 - $49,999|1|2|0|3|33%|67%|0%
> $50,000|8|49|9|66|12%|74%|14%

The immediate standout data point on the table comparing funding goals with success is that only 12% of campaigns seeking more than $50,000 succeed.  In fact, sorting the theater campaigns by funding goal shows that the 23 largest funding campaigns in the data set are all either failures or cancelled. Your odds of success in achieving your goals Are in general quite low if you are asking for a lot of money.

!("C:\Users\newho\OneDrive\_GW DATA BOOTCAMP\Module 1\MODULE ONE CHALLENGE\resources (PNG charts)\Outcomes Based On Goal Chart.png")

The chart, however, graphically illustrates that this relationship does not, however, remain stable throughout the ranges of goals. While very small goals the micro funding campaigns that we examined have the highest rate of success about 3/4 of them get funded odds of success drop down gradually until about $30,000 where they spike up again for the range of $35,000 to $45,000 before falling off.

** Challenges and Cautions**
This is a very preliminary analysis.  A few caveats should be mentioned in considering this report:
- No attempt has been made to examine the data quality.  The data set presented did not come with explanations of manner in which it was gathered, speaking to questions like “Is this a complete of all Kickstarter campaigns from the referenced? Or is it some other subset of available data? One cannot really make a proper inference without knowing how representative this data is.
- Depending on the client's motivation one might wish to have a set of data related to not only Kickstarter campaigns but to other means of finding funding for projects.
- Definitions of the variables were also not provided and were simply inferred.  Some of these might be problematic. For example we have inferred that the category success is defined by funds pledged exceeding funds sought. However it is quite possible that many of the people initiating the campaigns we're putting out a request for a number that was significantly higher than what they actually wanted or needed. A wish if you will not a need. Falling short of this is not necessarily failure.
- A more in depth Look at the data would wish to examine it for outliers and for completeness. I would specifically caution about the odd trend that we see represented in the relationship between funding sought and level of success. If you look at the trendlines outside of the range of 35,000 to $40,000 it looks like a solid trend of decreasing success with increasing ambition.
- There are any number of additional questions that could be asked and ways in which the data could be examined that might inform the main interest of the client. For example the use of month of year in which the campaigns were launched gives some sense of seasonality however it would be important to look at variation by year itself. Given economic cycles, booms and busts almost certainly play a strong role in determining the success of a fund raising campaign. Another example is the fact bad the data are drawn from across national sample. our client probably has a specific location in which she would like to launch her play. It would seem therefore that we would wish to look at data only from this location and not from a broader universe. After all the success of Kickstarter campaigns in Switzerland may be quite a different relationship plan that of the United states. In particular it occurs to me that London and New York City have extremely different theater cultures than most other places.  Of course more granular data is always welcome and helpful. It would be nice to dig into lower levels of aggregation then merely the country that is reported in this data set. Unfortunately the time we have budgeted too this exercise does not allow a more robust exploration of these questions.

