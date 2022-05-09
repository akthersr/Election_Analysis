# Election_Analysis
## Overview of Election Audit

The main purpose of this analysis is to generate a vote count report.A colorado Board of Elections employee needs assistance with the following tasks to complete the election audit of a recent local congressional election.

 1. Calculate the total number of votes cast.

 2. Get a complete list of candiates who received votes.

 3. Calculate the total number of votes each candidate received.

 4. Calculate the percentage of votes each candidate won.

 5. Determine the winner of the election based on popular vote.
 6. Get a complete list of counties that had a turnout.
 7. Calculate the voter turnout for each county.
 8. Calculate the percentage of votes each county cast.
 9. Determine the county with the highest turnout.


# Resources

Data Source: election_results.csv

Software: Python 3.7.6, Visual Studio Code

# Election-Audit Results:

The analysis of the election show that:

 1. There were 369,711 votes cast in this election.

 2. The candidates were:

    Charles Casper Stockham

    Diana DeGette

    Raymon Anthony Doane

3. The Candidate results were:

   Charles Casper Stockham received 23.0%  of the vote and 85,213 number of votes.

   Diana DeGette received 73.8%  of the vote and 272,892 number of votes.

   Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.

4. The winner of the election was:

   Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.
   
5. The county results were:
  
   Jefferson received 10.5% vote of the total count and  38,855 number of votes.
   
   Denver recevied 82.8% of the vote of the total count and 306,055 number of votes.
   
   Arapahoe recevied  6.7% of the vote of the total count and 24,801 number of votes.
   
   Denver county had the largest number of votes. 
   
   The output from a command line in VS Code:
   
   ![](https://github.com/akthersr/Election_Analysis/blob/main/Screenshot%20(206).png)
   
# Election-Audit Summary:

I propose that the election commission can use this pypoll_challenge.py script with some modifications—for other elections as well. In this program we analyize the election_results.csv file by iterating through each row and reading the datas from second and third columns,to calculate and find the results.This code quickly returns numerous data for the colorado Board of Elections.

This code can be used on similar projects such as other congressional district elections, senatorial districts, local elections, and more. Python script can find unique names of candidates and counties, we can reuse this code on a much larger dataset with more candidates, more counties or other areas.This script is also useful for files containing more information,like type of ballot or the date the vote was cast by importing dependency datetime.Here the datetime dependency will capture the exact time when the analysis was exceuted, to perform real-time results for election in progress.







