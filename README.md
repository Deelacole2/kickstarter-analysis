## An Analysis ok Kickstarter Campaigns.
### Purpose/Background: This analysis is an overall look at outcomes of various Kickstarter campaigns throughout the years to glean insight into which factors seem to influence the success, failure or cancelation of a campaign. The goal here is to assist Louise with making the best decisions regarding her upcoming kickstarter campaign for her own play.

### Analysis performed:

#### Initial analysis performed
  * New calculated columns were created
  * Conditional formatting was placed on two columns to allow for an at-a-glance understanding of the data.
* A pivot table and chart for Parent category outcomes: On the first chart we are looking at all parent categories of Kickstarters within the U.S. The second chart is specifically for campaigns within the Theater category.

![Parental Category Outcomes - Theater](https://github.com/Deelacole2/kickstarter-analysis/blob/main/Png.Kickstarter/parentalcategoryoutcomes2.png)

![Outcomes of Theater Kickstarters](https://github.com/Deelacole2/kickstarter-analysis/blob/main/Png.Kickstarter/outcomesvstheaterkickstarters.png)

* Outcomes based on launch date. A pivot table was created to group the launch dates by month regardless of year and it includes all countries. The first chart is for all the Categories. The 2nd is only for Theater kickstarters. 

![Outcomes Based on Launch Date - All Categories](https://github.com/Deelacole2/kickstarter-analysis/blob/main/Png.Kickstarter/outcomesbasedonlaunchdate3.png)
![Outcomes Based on Launch Date - All Categories](https://github.com/Deelacole2/kickstarter-analysis/blob/main/Png.Kickstarter/outcomesbasedonlaunchdate2.png)

* Descriptive stats- This section was created to allow Louise to get a specific look about how plays fared within the U.S. The successful and failed outcomes were compared by their goal and pledged funding numbers. Two new tables were created and then a table was created (as seen below) and the measures of central tendency were created.

![Outcomes Based on Launch Date - All Categories](https://github.com/Deelacole2/kickstarter-analysis/blob/main/Png.Kickstarter/stats.png)

### Summary of Findings
  * From the Parental category analysis.
    - The Theater category has the most launched campaigns (900) while only winning 58% of them. But that 58% is 525 successful campaigns.
      - Specifically, about the 'plays' subcategory; they make up 662 of the total campaigns and 412 of the successful outcomes.
    - The Music category had a 79% success rate out of 619.
  
  * From the outcomes based on Launch date there are two definite standouts, May and June are the only months that have 100 or greater successful campaigns (when speaking about Theater campaigns). 
    - It is worth noting that these two months also had the greatest amount campaign launches, which will lend itself to the higher ratio of wins. 
    - On the other end of the spectrum, December should be avoided as a launch month, there is an almost 50% failure rate.
    
  * From our Statistical analysis/ measures of central tendency:
    - The first thing that is noticed is that with the successful campaigns, the mean of the goal and pledged funding amounts are very close, that means that goals that average around $5,000 have a better chance of success. On the failed campaigns, the mean of the funding goal is 95% higher than the funding pledged to those same campaigns.
    - The median on both the successful and failed campaigns demonstrate that even 5,000 might be lofty in some cases and that additional analysis is needed to truly determine what were the true determining factors in why a campaign might have failed.
    - Checking the quartiles, the upper and lower quartiles maintain the same trend, goals around $5,000 and below have a much higher chance of success. It seems if the goal starts too high then people are less likely to donate to it and it fails. The upper quartile of the failed campaigns is 10,000 and the pledged is $501, there must be something about that lofty amount that throws the donators off.

### Recommendations:

Theater is the best performing parental category and plays are the second-best performing subcategory, this is good choice for your kickstarter. In regards to the amount, $8,000 may be a bit lofty. It can be done but smaller amounts make for more successful campaigns, any where from $3,000 to $5,000 have pretty good success rates. I also recommend that you launch your campaign during the Summer, during May or June if possible. The end of the year near the holidays, specifically December, should be avoided as potential launch date.



