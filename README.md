# Election_Analysis
## Overview of Election Audit: 
The purpose of this election audit analysis is to read through the election data set and write and save the results to a seperate text file. To use python to sum the total and percentages of votes corresponding to each county and candidates thus finding which county obtained the largest number of votes and the winner of the election based on popular vote.

A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election 
    1. Calculate the total number of votes cast.
    2. Get a complete list of candidates who received votes.
    3. Calculate the total number of votes each candidate received. 
    4. Calculate the percentage of votes each candidates won. 
    5. Determine the winner of the election based on popular vote. 

### Resources 
- Data Source: election_results.csv 
- Software: Python 3.6.1, Visual Studio Code, 1.38.1 

## Election-Audit Results: 
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

## Election-Audit Summary: 
This script can be easily modified to fit any type of elections or different future purposes seeing how our script is able to effectively find votes counts, percentage of votes won by each county and candidate, and also figure out what the percentages of each county voted for each candidate. One example this script can be modified to analyze future congressional election by changing the data to be different such as the counties to states. We can also add another if statement to give us a breakdown showing which counties voted for who. This can be used for any future elections because it gives us a great breakdown of counties or states even if data is different.
