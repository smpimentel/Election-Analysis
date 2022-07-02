# Election_Analysis

## Project overview
The purpose of this script is to provide an automation process for an election audit of a
recent election.

1. The total number of votes cast
2. Which counties were these votes taken from.
3. Then total number of voters each county had turnout and their percentages compared to the overall turnout.
4. Which county had the larges turnout.
5. A complete list of candidates who received votes.
6. The percentage of votes each candidate won.
7. The total number of votes each candidate won.
8. The winner of the election based on popular vote.

##  Resources
- Data Source: election_results.csv
- Software: Python 3.8, PyCharm

## Summary
The analysis of the election shows:
- That there was a total of 369,711 votes.
- We saw data from three different counties: Jefferson (38,855 votes), Denver (306,855), Arapahoe (24,801).
- From this we saw that Denver had the largest turnout
- There were three candidates in this election race: Charles Casper Stockham (85,213), Diana DeGette (272,892), Raymon Anthony Doane (11,606).
- From this we saw that Diana DeGette won the election after receiving 73.8% of the vote.

## Election-Audit Summary

This script can serve as a great automation tool for counties to run through their local election data and tally up quick results rather than manually counting.
Although this script is tailored to a specific CSV file, it can be easily modified to be an input dependent script that way it can read many different files with the same data but in a different layout. In addition to this,
modifications can be made to suit the specific needs of each election. For example, differentiating between local and state elections. Also, based on the 
data that we receive in the CSV file we can provide further analysis into the election that could better serve campaign strangest teams.
