# Election-Analysis

## Project Overview

A Colorado Board of Elections employee, Tom, asked me to use Python to iterate over a CSV file containing election results for a recent U.S. Congressional precinct in Colorado and report on the following:

- The total number of votes cast
- The total number of votes and percentage of total votes for each county in the precinct
- The county with the highest turnout
- The total number of votes and percentage of total votes for each candidate
- The winner of the election based on popular vote

The goal of this project is to audit the results and certify the winner of the election. 

## Resources
Data Source: [election_results.csv](https://github.com/kylebrumbaugh9/Election-Analysis/files/9947402/election_results.csv)

Software: Python 3.7, Visual Studio Code

## Election Audit Results



![TotalVotesCountCode](https://user-images.githubusercontent.com/114685724/200208755-89f06d12-8b61-4ab5-910d-2d5f944fc1a4.jpg)

_I wrote this code to loop over the entire .csv file to determine the total number of votes cast and attribute those votes to specific candidates and specific counties to look at turnout_

- **The total number of votes cast**
  - 369,711
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
![CountyResultsCode](https://user-images.githubusercontent.com/114685724/200209356-4d6cde02-014e-4091-8b42-36805fbd511c.jpg)

_Here is the code I used to determine the county results_

- **The total number of votes and percentage of total votes for each county in the precinct**
  - Jefferson: 10.5% (38,855)
  - Denver: 82.8% (306,055)
  - Arapahoe: 6.7% (24,801)
- **The county with the highest turnout**
  - Denver 
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
![CandidateResultsCode](https://user-images.githubusercontent.com/114685724/200209527-8a000b1b-ca53-4904-aeb0-0fc29168e465.jpg)

_Here is the code I used to determine the results per each candidate. This was very similar to the code used to calculate the county data_


- T**he total number of votes and percentage of total votes for each candidate**
  - Charles Casper Stockham: 23.0% (85,213)
  - Diana DeGette: 73.8% (272,892)
  - Raymon Anthony Doane: 3.1% (11,606)
- **The winner of the election based on popular vote**
  - Diana DeGette with 272,892 votes, which was 73.8% of the total vote
  
  
## Election Audit Summary




