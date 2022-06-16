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
The purpose of this election audit analysis is to breakdown Colorado's election and review whether the votes were counted accurately (a results audit) and to uncover further analysis. We want to complete the additonal data requests from the election commission to so that they can tell a complete story of the results of the election. This is done for quality management, but also to protect the official election results from undetected fraud and error. We want to see what the data tells us when we complete and analyze the results. For example, determing the county with the highest turnout can tells us which area was most active in the vote when the election results are declared final. This can lead to more analysis and can provide us with more context as to why that specific county had the highest turnout. 


## Election Audit Results 
With the election_results.txt file located in the resources folder, which is also shown in the next header, we answer the following points and questions:

- How many votes were cast in this congressional election?
  - Total Votes: 369,711
- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
   - County Votes:
    - Jefferson: 10.5% (38,855)
    Had the second smallest/largest number of votes and percentage of votes
    - Denver: 82.8% (306,055) 
    Had the largest number and highest percentage of votes
    - Arapahoe: 6.7% (24,801)
    Had the smaller number and smallest percentage of votes
 - Which county had the largest number of votes?
    - Denver
- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
  - Charles Casper Stockham: 23.0% (85,213)
  Had the second smallest/largest number of votes and percentage of votes; 2nd Place
  - Diana DeGette: 73.8% (272,892)
  Had the largest number and highest percentage of votes; 1st Place
  - Raymon Anthony Doane: 3.1% (11,606)
  Had the smaller number and smallest percentage of votes; 3rd Place
- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  - Winner: Diana DeGette
  - Winning Vote Count: 272,892
  - Winning Percentage: 73.8%

There were three counties in Colorado: Jefferson, Denver, and Arapahoe,  whose votes totaled 369,711 votes. Denver had the biggest voter turnout with 82.8%. There were 3 candidates that each had votes: Charles, Diana, and Raymon. Diana DeGette had 73.8% of the votes which is 272,892 of the 369,711 total votes.


## OutPut File
Below is an image of the output election_results.txt file after running the code


<img width="472" alt="Screen Shot 2022-06-15 at 5 02 51 PM" src="https://user-images.githubusercontent.com/102444078/173961824-a41e26a2-b0c9-47a2-b369-85791627e20a.png">


## Election Audit Summary 
In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.

In an election, it is pivotal that the data that is being gathered is accounted for with accuracy and integrity. To avoid any mishaps or mistakes when tallying the voting count, this code can precisely determine information such as voter turnout, voting percentages, and electoin winner, just to name a few. There are various ways in which the integrity of elections can be affected or manipulated. Election results may be improperly tallied or reported, however, with the way this code is scripted, it is able to get rid of any inaccuracies that may be introduced by human error or because of a lack of proper oversight. This is code is structured in a way to allow for multiple modifications for any elections. For exmaple, one example is changing the script of the code so it can read and extract data from CSV files. As of right now, it is only extracting data from one specific file "election_results.csv", but this can be changed so the code can load and read data from multiples files. That way, if there is more than one file that the election commission needs to extarct data from, this code can refactored to do so. 


