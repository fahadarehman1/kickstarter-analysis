# Kickstarting with Excel

## Overview of Project

Louis a play writer was able to get funding for her play called ‘Fever’ thru crowd funding. This report will give her additional insights on “how different campaigns performed in relation to their launch dates and the funding goals”. 

## Analysis and Challenges

Selection Criteria:

- We will be using the crowdfunding data to complete this analysis.

- The Data is based from 2010-2017

- Data is filtered on ‘Theater’ Category for Analysis One and later sub-filtered on ‘Plays’ category for Analysis Two

- The outcomes we selected were ‘Successful’, ‘Failed’ and ‘Cancelled’

### Analysis of Outcomes Based on Launch Date

The first analysis we performed was based on Launch Date(aggregated by months) and the Outcome i.e. successful, failed or canceled

![Theater Outcomes vs Launch](/resources/Theater_Outcomes_vs_Launch.PNG)

From the picture above we can see that no. of cancellations were relatively low throughout the year. There's an uptick of successful projects starting spring. The failed percentages in most of the months were close to 30%. At the end of the year the year the Theater projects success goes down but one will think that its the holiday season and people are attending more theater shows but the data doesn't show that. We can see in summer there's more success and in the colder months the success goes down.

### Analysis of Outcomes Based on Goals

The second analysis was based on no. of successful/failed/canceled outcome and their respective percentages.

![Outcomes vs Goal](/resources/Outcomes_vs_Goals.PNG)

The most obvious point here is that none of the plays got cancelled regardless of asking goal amount. We can also see that the lower the goal amount the higher the success rate. The sweet spot is a goal less than $15,000. There are some anomalies though and we did saw some success at higher goal rate i.e. range of 35-45K but those projects are less than a percentage point as shown below:

![Outcomes based on no. of Projects](/resources/Outcome_Based_on_Projects.PNG)



### Challenges and Difficulties Encountered

- The first observation is the currency, based on the currency the pledge amount or goal amount can vary. We also don’t know if the Pledged and Goal amount are in US Dollars or local currency that is Mexican Peso or Canadian dollars. Also currency fluctuate from day-to-day, the conversion rate of US Dollars to Canadian dollars was 1: 1.5 in 2011(1 US Dollar equals to 1.5 Canadian Dollars) as of today its 1: 1.20

- Inflation is also something to look into, maybe in 2010 a play cost was 5,000 US Dollars but in 2021 it will be 6,500 or more

## Results

Analysis 1: Theater Outcomes by Launch Date

- The first obvious trend is that no. of cancellations are low and consistent throughout the year with the exception of January(no. seems to be a tidbit high) and no cancellations in the month of October
- Most of the successful launches were in the warmer months of April-August
- Data is skewed by years, we only have few data points for the years of 2010-2013 and 2017. For accurate analysis we should only use data from 2014-2016.

Analysis 2: Outcomes Based on Goals

- The lower the goal amount the higher are the chances of being successful in funding(with some exceptions)
- None of the plays got cancelled
- There’s a correlation going on between the Goal and Percentage of Success till amount($25,000 to $29,999). The higher the goal amount the lower its chances of success. The outliers are the 9projects which need higher goal amount($35,000 to $44,999) but at the same time the success rate also increases which is around 67%

**Recommendations:**

- Bring in currency historical data and the conversion rate. Not all the currencies are the same 
- The data criteria should be based on years 2014-2016 for accurate analysis
