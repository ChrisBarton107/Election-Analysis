# Election-Analysis

## Project Overview
A Colorado Board of Elections employee has given the following tasks to complete the election audit of a recent local congressional election
1. Calculate total number of votes cast.
2. Get a complete list of candidates that received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data source: election_results.csv
- Software: Python 3.7.6, VS Code 1.50.1

## Summary
The analysis of the election show that:
- There were 369,711 total votes cast
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23.0& of the vote and 85,213 number of votes.
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
- The winner of the election was:
  - Diana DeGette who received 73.8% of the vote and 272,892 number of votes.


## Challenge Overview 
The purpose of the election audit was to provide a data driven summary of the election based on county data. Desired outcomes included counties represented, percentage of vote, and total votes for each county in the election.

## Challenge Summary 
The analysis of the election show:
- There were 369,711 total votes cast
- The counties represented in the election were :
    - Arapahoe
    - Denver
    - Jefferson
 - The county results were:
    - Arapahoe received 6.7% of the vote with 24,601 total votes
    - Denver received 82.8% of the vote with 306,055 total votes
    - Jefferson received 10.5% of the vote with 38,855 total votes
 - The county with the largest voter turnout:
    - Denver
**Image summary of candidate and county outcomes**<br> 
<img src= "https://github.com/ChrisBarton107/Election-Analysis/blob/main/Resources/PyPoll_Challenge_Terminal.png?raw=true" width="1000">
 
### Additional
The code used to conduct the analysis is reusable for future elections but requires modifications if it is to be used properly. Future election data must be assessed prior to the execution of code so modifications can be made. Understanding election data format, including number of columns, information type, and position within the heading require the user to modify the script. Additional modifications are necessary if the user desires results not gathered from the current script.
