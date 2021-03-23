# Election_Analysis
---
## Project Overview
---
A Colorado Board of Elections employee has been assigned the following tasks to be completed for the election audit of a recent local congressional election:

  1. Calculate the total number of votes cast.
  2. Get a complete list of candidates who received votes.
  3. Calculate the total number of votes each candidate receieved.
  4. Calculate the percentage of votes each candidate won.
  5. Determine the winner of the election based on popular vote.
  
## Resources
---
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code 1.49.3

## Summary
---
The analysis of the election shows that:
- There were 369,711 votes cast in the election.
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote or 85,213 votes.
  - Diana DeGette received 73.8% of the vote or 272,892 votes.
  - Raymon Anthony Doane received 3.1% of the vote or 11,606 votes.
- The winner of the election was:
  - Diana DeGette who received 73.8% of the vote or 272,892 votes.
  
  ## Challenge Overview
  ---
  The election commission has also requested additional data to complete the audit:
  - The voter turnout for each county
  - The percentage of votes from each county
  - The county with the highest turnout
  
  ## Election Audit Results
  ---
  As evidenced by the screenshots exported to the terminal and to a text file, one can see that the additional requests have been addressed:
  
  Output to Terminal
  
  <img width="234" alt="OutputToTerminal" src="https://user-images.githubusercontent.com/70344787/96182531-9be92b00-0f03-11eb-9fec-a0087ae8864b.PNG">
  
  Output to Text
  
  <img width="288" alt="OutputToText" src="https://user-images.githubusercontent.com/70344787/96182807-fc786800-0f03-11eb-808d-709438065cf8.PNG">
  
  ## Election Audit Summary
  ---
  The script used to produce this analysis was successful for achieving the results desired by the election commission. With some modifications, this script can be adapted for use in just about any election. Some examples of modifications necessary include:
  - Modifying the row number (if necessary) used in the script that corresponds with the data file for the candidate name and/or county name to be summarized.
  - Modifying the code to allow for source data (other than csv) to be analyzed.
  
