# Election_Analysis

## Overview of Project
A Colorado Board of Elections employee has given us the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the pecentage of total votes each candidate received.
5. Determine the winner of the election based on popular vote.

## Resources
* Data Source: election_analysis.csv
* Software: Python 3.8.8, Visual Studio Code 1.62.3

## Election Audit Results
* A total of 369,711 votes were cast in the 3 counties that we audited.
* County by County breakdown of votes cast
	1. Jefferson County - 38,855 votes - 10.5% of total votes cast
	2. Denver County - 306,055 votes - 82.8% of total votes cast
	3. Arapahoe County - 24,801 votes - 6.7% of total votes cast
* Denver County had the largest voter turnout, with 82.8% of the total votes cast
* Results of election for each candidate
	1. Charles Casper Stockham received 82,213 votes, 23% of the total votes cast
	2. Diana Degette received 272,892 votes, 73.8% of the total votes cast
	3. Raymon Anthony Doane received 11,606 votes, 3.1% of the total votes cast
* The winner of the election is Diana Degette, with 272,892 votes, 73.8% of the total votes cast


## Challenge Summary
The code that has been created for this election audit is flexible and usable for many different types of elections.  The program can accommodate any number of candidates and any number of regions.
In this particular example we used counties in a congressional election, but it could also be used for school districts or other geographic areas with a few simple changes to the text output.
The program - with some modifications - could also be used for multiple races. For example - congressional seats and judges. An additional data field would have to be included to differentiate the races.
A different candidate list would have to be created for each race.
A second option would be to modify the code to accommodate multiple geographic areas.  For instance - congressional seats in multiple districts.
If--And statements could be added for the additional data fields, for example:
~~~~
If race = "Judge" and region = "district 4":
	candidate_votes[candidate_name] += 1
~~~~

