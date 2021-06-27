# Analysis of Election Results

## Overview of Project

Here we have a Election Results file([**election_results.csv**](https://github.com/nidhipandya/Election_Analysis/blob/main/Resources/election_results.csv)). This project is for analysis of Election Results([**election_results.csv**](https://github.com/nidhipandya/Election_Analysis/blob/main/Resources/election_results.csv)) in Colorado. Using this analysis we generate a report([**election_analysis.txt**](https://github.com/nidhipandya/Election_Analysis/blob/main/analysis/election_analysis.txt)) that shows voting turnouts and election results.

## Election Audit Results
when we run the code(in [**Command Prompt**](https://github.com/nidhipandya/Election_Analysis/blob/main/Resources/cmd_Election_analysis.PNG)) and generate the final Report([**election_analysis.txt**](https://github.com/nidhipandya/Election_Analysis/blob/main/analysis/election_analysis.txt)), we can give the answers of the followings questions:

#### How many votes were cast in this congressional election?
In this Election there were 369,711 votes cast. This was calculated by reading each row using a 'for loop' in the election_data.csv file.  The code for this can be found on line 46 in [**PyPoll_Challenge.py**](https://github.com/nidhipandya/Election_Analysis/blob/main/PyPoll_Challenge.py).

#### Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
The breakdown of the number of votes and percentage of total votes for each county in the precinct was calculated using a 'for loop' and a 'if statement' on line 69 in [**PyPoll_Challenge.py**](https://github.com/nidhipandya/Election_Analysis/blob/main/PyPoll_Challenge.py).
The results are as follows:
|  county  | votes |
| ---------------| --------------- |
| Jefferson | 10.5% (38,855) |
| Denver | 82.8% (306,055) |
| Arapahoe | 6.7% (24,801) |

#### Which county had the largest number of votes?
After calculating each county's vote, it was determined that Denver County had the largest vote turnout.
Denver: 82.8% (306,055)

#### Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
Again, The breakdown of the number of votes and percentage of total votes for each candidate was calculated using a 'for loop' and a 'if statement' on line 56 in [**PyPoll_Challenge.py**](https://github.com/nidhipandya/Election_Analysis/blob/main/PyPoll_Challenge.py).  
The results are as follows:
|  cadidate  | votes |
| ---------------| --------------- |
| Charles Casper Stockham | 85,213 (23.0%) |
| Diana DeGette | 272,892 (73.8%) |
| Raymon Anthony Doane | 11,606 (3.1%) |

#### Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
As seen from the results, Diana DeGette was the winner of the election with a vote count of 272,892 which accounted for 73.8% of the votes.

## Election-Audit Summary: 
The Election commision can alter this script to provide the average of voters that voted in a county and also the margin of vitory between each of the candidates. If the data in the csv file is updated with different candidates's data, the script could audit the results of any future election.
