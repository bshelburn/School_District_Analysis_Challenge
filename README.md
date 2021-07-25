# School District Analysis Challenge
---
## Overview of Election Audit
Performed an electtion audit for Seth, Tom and the Colorado Board of Elections.   Results were housed within a .csv file containing the Ballot ID, County, and Candidate names.   Python was utilized to parse out and calculate the needed metrics held within the large imported .csv file as well as create the outputs shown in both the computer terminal and a .txt file.

### Purpose
This audit was needed by the Colorado Board of Elections to determine the total number of votes cast, all candidates who received votes, total number of votes received per candidate, percentage of total votes each candidate received, which county the votes were cast in, total votes for each county, percentage of total votes per county, whouch county had the highest turnout for the election, and the winner based on the popular vote with percentage of total votes.

## Election Audit Results

**Total Votes: 369,711**
  * Votes and Percentage By County
  * Jefferson: 10.5% (38,855)
  * Denver: 82.8% (306,055)
  * Arapahoe: 6.7% (24,801)

**Largest County Turnout Denver**

**Votes and Percentage by Candidate**
  * Charles Casper Stockham: 23.0% (85,213)
  * Diana DeGette: 73.8% (272,892)
  * Raymon Anthony Doane: 3.1% (11,606)

**Election Winner Summary**
  * Winner: Diana DeGette
  * Winning Vote Count: 272,892
  * Winning Percentage: 73.8%

## Election Audit Summary
Should the election comission want to repurpose this script it could be used for both national and larger state elections by changing the references of counties to the appropriate name.   For instance change county_names = [] (list) to state_names = [] in the case of a national election. 

Another interesting repurposing for the election commision would be to do a deeper dive on not only how many and what percentage of votes were cast per county but also which candidate those votes were cast for.   Although Raymon Anthony Doane only received 11,606 total votes all could have been from Arapahoe county which would count for almost 50% of total votes cast.   This could provide insight as to where time is better spent campaigning in the future for candidates and who has the strongest support in each county.
