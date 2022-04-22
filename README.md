# Election_Analysis

## Overview of Election Audit
A colorado elections commission has requested the following data to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.
6. Get a complete list of counties in the precint.
7. Calculate the total number of votes and percentage of the total votes each county received.
8. Determine the county with the largest turnout.

## Resources
* Data Source: election_analysis.csv
* Software Python 3.7.3, Visula Studio Code 1.66

## Election-Audit Results
Please refer to the image below for the Election-Audit Results.  

![election_results](https://github.com/MarcoFernandez14/Election_Analysis/blob/main/Resources/Election%20Results.png)

* There were 369,711 votes cast in the election.

* Votes and percentage of total votes breakdown by county in the precinct:  
 ***Jefferson***: 10.5% (38,855)  
 ***Denver***: 82.8% (306,055)  
 ***Arapahoe***: 6.7% (24,801)

* Largest County Turnout: ***Denver***

* Votes and percentage of the total votes breakdown by candidate:  
 ***Charles Casper Stockham***: 23.0% (85,213)  
 ***Diana DeGette***: 73.8% (272,892)  
 ***Raymon Anthony Doane***: 3.1% (11,606)

* Winner: ***Diana DeGette***  
 Winning Vote Count: 272,892   
 Winning Percentage: 73.8%


## Election-Audit Summary
This scrip can definitely be used used - with minor adaptations - for any other election. As the code works with variables that are added from the raw data (using tools such as list and dictionaries), ***it can be used to audit any other precint election***.
This code ***can also be adapted to differemt election rules*** such as: a) candidates that have more than a cetain percentage of votes advance to a second voting round, or, b) a candidate has to win in all the counties to be elected, or, c) other rules variations.   
The code will requiere, of course, minor changes adapt to the raw data *file name, location/path and format*. However, the code can work with more or less lines or with different candidates or counties names.







