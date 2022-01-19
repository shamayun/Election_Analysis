# Election_Analysis
## Overview of Election Audit
In this analysis, I assisted Tom, an employee of Colorado Board of Elections.
I assisted him to complete the election audit of a recent local congressional election by calculating the followings:
1. Calculate the total number of votes cast. 
2. Get a complete list of candidates who received votes. 
3. Calculate the total number of votes each candidate received. 
4. Calculate the percentage of votes each candidate won. 
5. Determine the winner of the election based on popular vote. 

Besides the candidate summary, I also assisted Tom to generate a summarized report of The percentage of votes from each county out of the total count and the county with the highest turnout.
### Resources
I have utilized *election_results.csv* as the data source to conduct this audit. Python codes in Visual Studio Code were used to generate output into *election_results.text* files for user's covenience.

## Election Audit Results
Below are the full summary of election results from Colorado Board of Elections: 
- There were 369,711 votes cast in the election.
- The candidates were: 
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The candidate results were: 
    - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
    - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
    - aymon Anthony Doane received 3.1% of the vote and 11,606 number of votes. 
- The winner of the election was: **Diana DeGette**, who received *73.8%* of the vote and *272,892* number of votes. 
- Percentage of total votes and number of votes and  for each county were:
    - Jefferson: 10.5%  (38,855)
    - Denver:    82.8% (306,055)
    - Arapahoe:   6.7%   (24,801)
 
 **Denver** had the largest number of votes out of all counties in Colorado.

## Election Audit Summary
Based on the success and accuracy of the scripts, I can suggest this automation of audits can be used in other local and senatorial districts. All 3 voting methods(*Mail-in Ballot, Punch Cards, Direct Recording on Electronic Medias*) can be successfully captured into CSV format. Once results are captured in CSV format, can be utilized in Python/Visual Studio Code to conduct full automated audit of any elections, and to produce summarized results by Candidate and locations. Below are 2 steps that needs to be updated in the scripts to make this an univeral audit tool for any elections:

1. Provide the correct path to load the correct input file (*file to load*), provide correct path for the output(*file to save*) files in the computer

![input_output_location](https://github.com/shamayun/Election_Analysis/blob/main/Resources/Data_Source%20Input_Output%20locations.png)
2. Ensure the correct position of candiate name and location in the list. In our datasource County was listed in position 1 and Candidate was listed in position 2.

![Candidate_county_position](https://github.com/shamayun/Election_Analysis/blob/main/Resources/Candidate%20and%20County%20in%20Dictionary.png)

This automation process will increase the efficiency of any election audit process. The results could be shown in either text files or Terminal depending on user's preference. The final results will be shown in Terminal as below:
![Summary](https://github.com/shamayun/Election_Analysis/blob/main/Resources/Election_Summary.png)


