# kickstarter-analysis

Perform analysis on Kickstarted data to help your client Louise make her kickstarted campaing successful. 

### Challenge
- Outcome based on goals countifies campaigns in different goal brackets. Furthermore, we use those results to determine what       percentage each campaign, based on the outcome, takes from a total number of campaigns.

  The data is presented in ![outcome_based_on_goal_chart](./outcome_based_on_goal_chart.png).

  Based on the chart we can conclude that campaign with goals less than $2000 has a higher rate of success. Even if the success rate seems to go up in the $3000 - $5000 bracket if we look at total projects for that period we see a significant decrease in the data points, that makes it hard to determine if those are actual trends or we are dealing with outliers. 

- Outcome based on launch date analyzes the correlation between the launch time and the outcome of the campaign.

  The information is vizualized in chart: ![outcome_based_on_launch_date_theater](./outcome_based_on_launch_date_theater.png) .
  
  We can see a peak in successful campaigns during the April - July period and a significant drop in the winter months. Since the number of successful campaigns unevenly oscillates during the time of the year we can assume that the start time affects the success of the outcome.

  The number of failed and cancelled campaign are more consistent throughout the year. Probably there are other factors that influence the failure of a campaign as much as the time it started. Although there is a slight increase in failures during the April - July period we observe an increase in the total campaigns started during this period. Most campaigns start during the early summer season.

  Adding the pledged amounts to this analysis could bring extra insight into the factors that influence the outcomes of the campaigns based on the time it was launched.