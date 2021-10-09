# PyPoll with Python

## Overview of Election Audit

A Colorado Board of Elections employee has given the following tasks to complete the election audit of a recent congressional elections.

 	1. Calculate the total number of votes cast.
 	2. Get a complete list of candidates who received votes.
 	3. Calculate the total number of votes each candidate received.
 	4. Calculate the percentage of votes each candidate won.
 	5. Determine the winner of the election based on popular vote.

The Board of Elections added additional deliverables to analyze the results for each County.

	1. The voter turnout for each county.
	2. The percentage of votes from each county out of the total count.
	3. The county with the highest turnout.

## Election-Audit Results



![This is an image](election_results.png)


- How many votes were cast in this congressional election?
  - Total votes cast in this election: 369,711
- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
  - Breakdown of Votes Cast by County with Percentage of votes.
    - County Votes:
      - Jefferson: 10.5% (38,855)
      - Denver: 82.8% (306,055)
      - Arapahoe: 6.7% (24,801)
- Which county had the largest number of votes?
  - County with largest turnout: Denver
- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
  - Breakdown of Votes Cast by Candidate with Percentage of Votes
    - Charles Casper Stockham: 23.0% (85,213)
    - Diana DeGette: 73.8% (272,892)
    - Raymon Anthony Doane: 3.1% (11,606)
- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  - The Following Candidate Won the election:
    - Diana DeGette
    - Vote Count: 272,892
    - Percentage of Vote: 73.8%

## Election-Audit Summary

The script completed can be repurposed on perform analysis on other elections. With modifications to the script an analysis could be run for city or county elections by the addition of precinct or district data. The same analysis can also be run to drill down to votes received by district and by city. Additional data points will need to be included in the files being analyzed in order to add additional functionality to the script.
