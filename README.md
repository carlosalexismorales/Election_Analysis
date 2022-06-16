# Election_Analysis
Using Python to help audit and analyze Colorado's election 

## Project Overview
A Colorado Board of Elections employee has given the following tasks to complete the election audit of a recent logal congressional election.

1. Calculate the total number of votes cast. 
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on the popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.10.5, Visual Studio Code 1.68.0

## Summary 
The analysis of the election show that:
- There were 369,711 votes cast in the election
- The candidates were:
  - Charles Casper Stockham 
  - Diana DeGette 
  - Raymon Anthony Doane 
- The candidate results were: 
  - Charles Casper Stockham received 23.0% of the vote and 85.213 number of votes. 
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes. 
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes. 
- The winner of the election was: 
  - Diana DeGette who received 73.8% of the vote and 272,892 number of votes.


## Challenge Overview
To help Seth and Tom submit the election audit results to the election commission and addressing the election commission's additional data request to complete the audit:

-- The voter turnout for each county

-- The percentage of votes from each county out of the total count

-- The county with the highest turnout

1. The data we need to retrieve.
2. Using loops to calculate the total number of votes cast
3. Get a complete list of candidates who received votes.
4. Calculate the total number of votes each candidate received.
5. Calculate the percentage of votes each candidate won.
6. Determine the winner of the election based on popular vote.


## Overview of Election Audit
The purpose of this election audit analysis is to breakdown Colorado's election and review whether the votes were counted accurately (a results audit) and to unconver further analysis. We want to complete the additonal data requests from the election commission to so that they can tell a complete story of the results of the election. This is done for quality management, but also to protect the official election results from undetected fraud and error. We want to see what the data tells us when we complete and analyze the results. For example, determing the county with the highest turnout can tells us which area was most active in the vote when the election results are declared final. This can lead to more analysis and can provide us with more context as to why that specific county had the highest turnout. 


## Election Audit Results 
With the election_results.txt file located in the resources folder, which is also shown in the next header, we answer the following points and questions:

- How many votes were cast in this congressional election?
  - Total Votes: 369,711
- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
   - County Votes:
    - Jefferson: 10.5% (38,855)
    - Denver: 82.8% (306,055)
    - Arapahoe: 6.7% (24,801)
 - Which county had the largest number of votes?
  Denver
- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
  - Charles Casper Stockham: 23.0% (85,213)
  - Diana DeGette: 73.8% (272,892)
  - Raymon Anthony Doane: 3.1% (11,606)
- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  - Winner: Diana DeGette
  - Winning Vote Count: 272,892
  - Winning Percentage: 73.8%

Colorado saw three counties tally up to 369,711 votes. The biggest of the counties with a 82.8% was Denver. We processed the votes for three candidates of Charles, Diana, and Raymon. With 73.8% of the votes towards Diana DeGette, that is 272,892 of the 369,711 total votes.


## OutPut File
Below is an image of the output election_results.txt file after running the code


<img width="472" alt="Screen Shot 2022-06-15 at 5 02 51 PM" src="https://user-images.githubusercontent.com/102444078/173961824-a41e26a2-b0c9-47a2-b369-85791627e20a.png">
