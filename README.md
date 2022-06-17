# Election_Analysis

## Project Overview
For this project a Colorado Board of Elections employee provided a file containing voting records for a recent congressional election and requested an election analysis with the following tasks:

1. Calculate the total number of votes cast.
2. Create a complete list of counties included in the election.
3. Calculate the number of votes in each county (thereby providing the number of voters).
4. Calculate the percentage of votes each county registered out of the total votes received.
5. Determine the county with the largest number of voters and the percentage election voters in that county.
6. Create a complete list of candidates who received votes.
7. Calculate the total number of votes each candidate received.
8. Calculate the percentage of votes each candidate won.
9. Determine the winner of the election based on popular vote.
10. Save the results in a text file in simple, readable format.

## Resources
- Data Source: election_results.csv
- Software: Python 3.10.5, Visual Studio Code, 1.68.1

## Summary

### Election Results
The analysis of the election shows that:

- There were 369,711 total votes.
- The counties included in the voting record were:
  - Jefferson County, which had 38,855 votes (comprising 10.5% of the total votes). 
  - Denver County, which had 306,055 votes (comprising 82.8% of the total votes).
  - Arapahoe County, which had 24,801 votes (comprising 6.7% of the total votes).
- Denver county had the largest number of votes with 306,055 votes (82.8% of the total votes).
- The election candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the votes, with 85,213 total votes.
  - Diana DeGette received 73.8% of the votes, with 272,892 total votes.
  - Raymon Anthony Doane received 3.1% of the votes, with 11,606 total votes.
- The winner of the election was:
  - Diana DeGette, who received 73.8% of the votes and 272,892 total votes.
 
These results were output to a text file as seen in the image below:

![image](https://user-images.githubusercontent.com/105830645/174212427-3eb63295-ae00-442b-93c1-6eb014e5de20.png)


## Code Summary
The code for this project included several key python functions such as:
- Importing a csv file.
- Writing to a text file.
- Creating dictionaries and lists.
- Using repetition statements such as "for" loops.
- Using "if" statements and logical operators.

Loops are an important coding mechanism of python, allowing the program to run through the data repeatedly until all statements are satisfied. This can be used to sum data based on specific criteria, find unique names, compare values and replace values (such as comparing voter sums for the candidates and identifying the highest value, thereby identifying the candidate with the highest number of votes).

### Further Application
The code for this challenge demonstrates key functions of data analysis using python. The code is adaptable and can be put to further use. Some examples of additional use cases and modifications are:
- Candidate party affiliation:
  - If the voting input were to include party affiliation this could be incorporated into the analysis logic.
  - Party list and party vote dictionaries could be created.
  - Party variables could be defined and similar for loops and if statements could be used to sum the votes for each party and provide a percentage of the votes for each party.
- Voter Demographic inclusion:
  - If the voting input were to include demographic information such as gender, race, or age range the code could be adopted to include this logic.
  - As mentioned above similar steps could be followed to determine the percentages of voters in each demographic and how that relates to each candidate.
The python code is flexible and can be expanded and adapted to meet further analysis needs.


