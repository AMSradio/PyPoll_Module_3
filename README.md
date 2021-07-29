# PyPoll_Module_3_Challenge
U of O Analytics Bootcamp Module 3

# Overview of Election Audit
### Purpose of election audit analysis well defined
The purpose of this analysis was to provide a geographic breakdown by county of the election results, turnout, and proportioned activity within each applicable county. In this particular election, there was information available from 3 different counties: 


# Election Audit Results
### Bulleted list where each election outcome is addressed
## Denver county results
* Total turnout for Denver was 306,055 total votes
* Diana DeGette was a clear cut winner yeilding 239,282 votes, beating the second place candidate (Charles Casper Stockham) by four times the vote. Yielding 78 percent of the total votes cast in that county

## Jefferson county results
* Total turnout for Jefferson county was 38,855 total votes
* Charles Casper Stockham obtained a victory by a narrow margin in this county by 1,760 votes beating the runner up, Diana DeGette.
* Stockham received approximately 51% of the total votes

## Arapahoe county results
* Total turnout for Arapahoe county was 24,801 total votes
* Diana DeGette once again obtained a victory by a strong margin. Beating the runner up (Charles Casper Stockham) by a margin of 7,345
* Diana DeGette yeilded 63% of the total vote

## General result analytics
* Total votes of all 3 counties combined was 369,711
* There was a third candidate, Raymond Anthony Doane, that obtained an amount of votes of statistical significance at a macro level, however, failed to yeild more than 3.5% of the total vote in Denver, Jefferson, or Arapahoe county (3.1%, 3%, and 3.4% respectively)
* Denver county was the most engaged out of the three counties having approx 8 times more voter turnout than the next highest county (Jefferson). This could be due to how proportionate the overall population is in each county, however, more analysis is needed



# Election Audit Summary
### statement to the election commission that explores how this script can be used for any election, with two exaples for modying the script.

The most exciting part about this script is that it is built to grow with the expand with population and district lines. As the information is brought in, as new counties, or candidates are presented, the routine will add them, aggregate the statisitcs, and produce the results accordingly. 

Because of this flexibility, we can expand the scope of this script to assess not only these counties again, but the results of any election in which the same data is available with minimal modification. One modification I would recommend is to add a variable for county population, perhaps from another external data source, so that we can further assess voter turnout at a per capita level. 
