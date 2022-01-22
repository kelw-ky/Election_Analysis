# Election_Analysis

## Overview of Election Audit
A Colorado Board of Election employee have given you the following tasks to complete the election audit of a recent local congressional election. 

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes. 
3. Calculate the total number votes each candidate received. 
4. Cal culate the percentage of votes each candidate won. 
5. Determine the winner of the election based on popular vote. 

## Resources 
- Data Source: election_results.csv
- Software: Python 3.10.1, Visual Studio Code, 1.63.2

## Election Audit Results
The anaylsis of the election show that: 

- There were 369,711 votes cast in the election. 
- Each counties turnout were as following: 
    - Jefferson has 38,855 votes, which is 10.5%
    - Denver has 306,055 votes, which is 82.8%
    - Arapahoe has 24,801 votes, which is 6.7%
-The largest county turnout was in Denver.

- The Candidates were: 
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The candidate results were: 
    - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
    - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
-The winner of the election was Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

![Election_Results](/Resources/Election_Results.png)

## Election Audit Summary
With sight changes to this python code, this code could be used for other elections as well. Adjustments that might need to happen to the code for different elections would be if the CSV file name was changed then the path will have to be updated to reflect that name. "file_to_load = os.path.join("Resources", "election_results.csv")". "Resources" and "election_results.csv" would have to be change to appropiate folder name and to the correct file name respectively. If where the column number was changed, then that would have to updated in the code as well. " candidate_name = row[2]" and "county_name = row[1]" The [2] and [1] would have to be changed to the new column number minus 1. 
