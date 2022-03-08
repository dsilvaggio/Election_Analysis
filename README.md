# Election_Analysis

## Project Overview
  A Colorado Board of Elections employee has requested assistance in auditing the recent congressional election. Assistance was needed in:
   1. Calculating the total number of votes
   2. Compiling a  list of the candidates who recieved at least 1 vote
   3. Calculating the total number of votes for these candidates
   4. Calculating the percent of total votes that these candidates recieved
   5. Determing the winner of the election

## Resources
  Data Source: election_results.csv
  Softward: Python 3.7, Visual Studio Code 1.65
  
## Summary
The analysis of the election results showed that:
  * The total number of votes was 369,711
  * The candidates who recieved votes were:
    *  Charles Casper Stockham
    *  Diana DeGette
    *  Raymon Anthony Doane
  *  The total number of votes these candidates recieved were:
    * Charles Casper Stockham recieved 23% of the vote and 85,213 total votes.
    * Diana DeGetter recieved 73.8% of the vote and 272,892 total votes.
    * Raymon Anthony Doana recieved 3.1% of the vote and 11, 606 total votes.
  * The winner of the election was Diana DeGette who recieved 73.8% of the vote and a total of 272,892 votes.  

## Challenge Overview
  After auditing the results to declare the winning candidate, the election commission has requested assistance in additional data in order to complete the audit. Assistance was needed in:
  1. Determing the voter turnout for each county
  2. Determing the percentage of total votes that came from each county
  3. Determing the county with the largest turnout

## Challenge Summary
The results of the audit showed the following:
  * The voter turnout for each county was:
      * Jefferson county made up 10.5% of the vote with 38,855 total votes.
      * Denver county made up 82.8% of the vote with 306,055 total votes.
      * Arapahoe county made up 6.7% of the vote with 24, 801 total votes.
  * The county with the largest voter turnout was Denver county with 82.8% of the vote and 306,055 total votes.

This python script can be used for any further election by simply changing the data that this script is pulling from. In order to modify the script for any election, you would need to change the original path that we are loading from to the updated election data that you want to use, instead of "election_results.csv" file that we used here. I would also create a new election_analysis.txt file to write your updated election results too, instead of the "election_analysis.txt" file that we used in this script. Overall, you would need to modify both the path that we are loading from and the path that we are saving to. 
