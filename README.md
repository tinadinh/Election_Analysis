# Election_Analysis

## Project Overview 
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election 

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received. 
4. Calculate the percentage of votes each candidates won. 
5. Determine the winner of the election based on popular vote. 

## Resources 
- Data Source: election_results.csv 
- Software: Python 3.6.1, Visual Studio Code, 1.38.1 

## Summary 
The analysis of the election show that: 
- There were "x" votes cast in the election. 
- The candidates were:
    - Candidate 1
    - Candidate 2 
    - Candidate 3
- The candidate results were:
    - Candidate 1 received "x%" of the vote and "y" number of votes. 
    - Candidate 2 received "x%" of the vote and "y" number of votes. 
    - Candidate 3 received "x%" of the vote and "y" number of votes. 
 - The winner of the election was:
    - Candidate (1, 2, or 3), who received "x%" of the vote and "y" number of votes. 
 
## Challenge Overview 
### Overview of Election Audit: 
The purpose of this election audit analysis is to find out which county is the largest based off of votes. In module 3 we learned how to read csv files in python and begin to run the data with our coding skills. The data file has 4 columns, we had to search through the one that had all of the candidates and figure out how many votes each candidate recieved. Once we figure out the total votes and percentage of the total that they had we wrote the results to a text file with a winner. In the module 3 challenge we are doing something similar but different. This time we will search through the counties column to figure out the total votes and percentage of each county to find which county is the largest.
### Election-Audit Results: 
- A total votes were cast in this congressional election:
    - 369,711 votes 
- The number of votes and the percentage of total votes for each county in the precinct:
    - Jefferson county had 10.5% of the vote with 38,855 total votes 
    - Denver had 82.8% of the vote with 306,055 total ballots submitted 
    - Arapahoe had 6.7% of the total vote with 24,801 ballots submitted 
- The county with the largest number of votes:
    -  Denver had the most amount of votes in the county by commiting 82.8% of the ballots
- The number of votes and the percentage of the total votes each candidate received:
    - Charles Casper Stockham (85,213/23%) 
    - Diana DeGette(272,892/73.8%) 
    - Raymon Anthony Doane(11,606/3.1%) 
- The candidate that won the election:
    - Diana DeGette won the election recieving 272,892 total votes which was 73.8% of the total votes submitted.

![election_analysis](https://user-images.githubusercontent.com/33900637/144755471-11215fb1-c909-4f9b-9bfb-b4db90f29325.png)

## Challenge Summary 
### Election-Audit Summary: In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.
This script can be easily modified to fit any type of election seeing how our script is able to effectively find votes counts, percentage of votes won by each county and candidate it is safe to assume that we can even figure out what the percentages of each county voted for each candidate. One example this script can be modified to be used for other elections, we can do something like this by adding another if statement to under line 76 that will give us a breakdown showing what counties voted for who. This can be used for any future election because it gives us a great breakdown of counties or even states if the data was different.
For example, if you wanted to analysis a federal congressional election, all you need to do is change the counties to states. Another example, if you had a local initiative election, all you need to do is change candidates to in favor or against.
