# An Analysis of Election Results



## Project Overview

A Colorado Board of Elections employee has given me the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.
6. Calculate the voter turnout for each county.
7. Calculate the percentage of votes from each county out of the total count.
8. Determine the county with the highest turnout.



## Election-Audit Resources

- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code 1.69.0



## Election-Audit Results

The analysis of the election show that there were **369,711** votes cast in the election.

### Results by County
- Votes were cast in the following counties:
	- Jefferson
	- Denver
	- Arapahoe 
	
- The county results were:
	- 10.5% of votes (or 38,855 votes) were cast Jefferson County
	- 82.8% of votes (or 306,055 votes) were cast Denver County
	- 6.7% of votes (or 24,801 votes) were cast Arapahoe County

<sub>These results have been visualized in the pie chart below.</sub>

<picture>
 <source media="(prefers-color-scheme: light)" srcset="https://github.com/ODaniels852/Election_Analysis/raw/main/Resources/County_Votes_Summary.png">
 <img alt=" Shows a pie chart displaying voting results in each county."/>
</picture> 

**The largest county turnout occurred in the county of Denver, from which 306,055 votes were cast, representing 82.8% of the votes cast in this election.**



### Results by Candidate
- The candidates for which votes were cast include:
	- Charles Casper Stockham
	- Diana DeGette
	- Raymon Anthony Doane
	 
- The candidate results were:
	- Charles Casper Stockham received  23.0% of the vote and 85,213 votes.
	- Diana DeGette received  73.8% of the vote and 272,892 votes.
	- Raymon Anthony Doane received  3.1% of the vote and 11,606 votes.

<sub>These results have been visualized in the pie chart below.</sub>

<picture>
 <source media="(prefers-color-scheme: light)" srcset="https://github.com/ODaniels852/Election_Analysis/raw/main/Resources/Candidate_Votes_Summary.png">
 <img alt=" Shows a pie chart displaying voting results for each candidate."/>
</picture> 

**The winner of the election was Diana DeGette, who received 73.8% of the vote, or 272,892 votes.**

##  Election-Audit Summary
I'd propose that this script be used for any future election, with modifications as necessary. This script will be most useful when the data source of election results is provided in a csv file and with the same column composition (Ballot ID, County, Candidate). However, if different election data is provided, modifications will allow for successful audit of results. 
For example, if the same data is provided but in a different order, like Ballot ID, Candidate, County, then the code can be changes as follows:
<picture>
 <source media="(prefers-color-scheme: light)" srcset=" https://github.com/ODaniels852/Election_Analysis/raw/main/Resources/ScriptModification_Example_1.png ">
 <img alt=" Shows a pie chart displaying voting results for each candidate."/>
</picture>
Additionally, if the same data is provided, but a request was made for candidate results by county this can be achieved by adding the following script
