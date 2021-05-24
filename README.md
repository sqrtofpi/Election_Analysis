# Election Audit with Python

Click here to view the Python file: [Election Audit Program](https://github.com/sqrtofpi/Election_Analysis/blob/0194da80732d344b12393b29415be6bd4ad920d4/PyPoll_Challenge.py)

## Project Overview

Having successfully submitted an analysis for a recent local congressional election to the Colorado Board of Elections, the election commision has requested additional information to complete its audit of the results. To aide the audit process, the following additional information has been requested:

1. The voter turnout for each county
2. The percentage of votes from each county out of the total count
3. The county with the highest turnout

#### This will supplement the following previously supplied information

4. The total number of votes cast in the election
5. A complete list of candidates who received votes
6. The total number of votes each candidate received
7. The percentage of votes each candidate won
8. The winner of the election based on popular vote

## Resources
- Data Source: election_results.csv
- Software: Python 3.8.5, Visual Studio Code, 1.56.2

## Election Audit Results
Upon auditing the results of the election; the following information is confirmed:
- There were 369,711 votes cast in the election
- The votes were obtained from the following counties and subsequent contribution to the total vote count
    - Jefferson County with 38,855 votes totaling 10.5% of the vote
    - Denver County with 306,055 votes totaling 82.8% of the vote
    - Arapahoe County with 24,801 votes totaling 6.7% of the vote
- The county with the largest voter turnout was Denver
- The candidates and their results were:
    - Charles Casper Stockham received 85,213 votes totaling 23.0% of the vote
    - Diana DeGette received 272,892 votes totaling 73.8% of the vote
    - Raymon Anthony Doane received 11,606 votes totaling 3.1% of the vote
- The winner of the election was:
    - Diana DeGette, who received 73.8% of the vote (272,892 votes)

## Election Result Verification

As with any election, vote count integrity is integral to the process and provides confidence in the fairness of the system. The following screenshots are being submitted as proof the resultant text file created contains the same information from the code when the program is output to a computer's terminal.

#### Output to Terminal when Running Election Audit Program 

![](https://github.com/sqrtofpi/Election_Analysis/blob/0194da80732d344b12393b29415be6bd4ad920d4/Resources/Election%20Results%20from%20Terminal.png)

#### Output to Text File when Running Election Audit Program 

![](https://github.com/sqrtofpi/Election_Analysis/blob/0194da80732d344b12393b29415be6bd4ad920d4/Resources/Election%20Results%20from%20Text%20File.png)

## Election Audit Summary

Thank you for the opportunity to provide the Colorado Board of Elections this audit information. It is our recommendation that this script be secured and used for future election cycles. The following code can be updated to analyze future elections in the following manner:

**First Example:** Analyzing a different election by placing a new datafile in the resources folder where the program is running.

![](https://github.com/sqrtofpi/Election_Analysis/blob/5d44a9772cbb0d2e573b56cd2f5b5946f169f212/Resources/Replacing%20the%20election_results.csv%20file%20for%20different%20elections.png)

This will allow for analysis of previous or future elections with the same .csv formatting, 1st column: Ballot ID, 2nd column: County, and the 3rd column is Candidate. If the data is structured as a .csv file with data arranged in these columns, this program will work when the program is updated to point to that file located in the resources folder.

**Second Example:** Analyzing a local (district) election instead of a county election

![](https://github.com/sqrtofpi/Election_Analysis/blob/5d44a9772cbb0d2e573b56cd2f5b5946f169f212/Resources/Using%20Replace%20to%20change%20County%20to%20City%20for%20local%20elections.png)

By editing the code using the replace function in Visual Studio Code editor (or similar), you will be able to change instances of county to district level elections as long as the .csv file contains the appropriate district level information in the 2nd column of the data file.



