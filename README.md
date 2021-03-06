# Election_Analysis

# Overview of Election Audit: 
The purpose of this election audit analysis is to obtain addtional data to the election commision. This analysis and audit are conducted using Python 3.7.6 on a CSV filed called "election_results".  The following data was requested by the election commission.

County and Candidate Vote Analysis:
- The total number of votes received
- The voter turnout for each county
- The percentage of votes from each county out of the total count
- The county with the largest turnout
- The voter count for each candidate
- The percentages of votes for each candidate out of the total count
- The winning candidate, winning vote count, and winning percentage


# Election-Audit Results: 
Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.
- How many votes were cast in this congressional election?
  - There were a total of 369,711 votes casted in this congressional election.
  
- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
  - Jefferson County had a total of 38,855 votes or 10.5% of the total votes.
  - Denver County had a total of 306,055 votes or 82.8% of the total votes.
  - Arapahoe had a total of 24,801 votes or 6.7% of the total votes.
  
- Which county had the largest number of votes?
  - The county with the largest number of votes is Denver County.

- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
  - Charles Casper Stockham had a total of 85,213 votes or 23% of the total votes.
  - Diana DeGette had a total of 272,892 votes or 73.8% of the total votes.
  - Raymon Anthony Doane had a total of 11,606 votes or 3.1% of the total votes.

- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  - Diana DeGette won the election and had a total of 272,892 votes or 73.8% of the total votes.

To obtain this analysis, the script (PyPoll_Challenge.py) was executed on Python. Below is a screenshot of the terminal when the script is runned. The output of the execution is also written to Analysis/election_results.txt.

![](Resources/Terminal_screenshot.PNG)


# Election-Audit Summary:
With this written Python script, the election commission can use this for any election, if they seek to obtain the same data parameters and if the CSV file is arranged in the same format. If any additional data parameters is needed to be analyzed, the Python script can be modified or updated to fit the need of the data analysis.

Two potential examples of how the script can be modified in future elections are:
- The script can break down the candidate votes in each county along with additional data on number of votes that each candidate received and their percentage of total votes received in the county.
- The county with the least amount of votes.
