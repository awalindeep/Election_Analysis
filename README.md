# Election Analysis

  

### Perform Election Audit for Colorado Board of Elections and automate result using python.

  

## Overview of Election Audit Project

  

### Background of Project

  

Tom from Colorado Board of Elections employee requested help with compiling an election audit of local congressional election. To completed election audit we have been assigned following tasks.

  

* Calculate the total number of votes casted.

* Get a complete list of candidates who received votes.

* Calculate the total number of votes each candidate received.

* Calculate the percentage of votes each candidate won.

* Determine the winner of the election based on popular vote.

* Calculate the voter turnout for each county.

* Calculate the percentage of votes from each county out of the total.

* Determine the county with the highest turnout.

  

## The Project Data

Data Source: [election_results.csv](https://github.com/awalindeep/Election_Analysis/blob/AwalinGHMAIN/Resources/election_results.csv)

  

## Election-Audit Results

  

For the audit of Colorado Board of Elections data the analysis of the election shows that:

  

#### Total Votes Casted :

  

* There were ****369,711**** votes casted in the Colorado Board of Elections.

  

#### The candidates :

  

1. ****Charles Casper Stockham****

2. ****Diana DeGette****

3. ****Raymon Anthony Doane****

  

#### The County Results:

  

Jefferson: ****10.5% (38,855)****

  

Denver: ****82.8% (306,055)****

  

Arapahoe: ****6.7% (24,801)****

  

* County with largest number of votes: ****Denver**** , which produced 82.8% of voters, for a total of 306,055 voters.

#### The candidate results :

  

1. ****Charles Casper Stockham**** received *********_23.0%*_**** of the vote and *********_85,213*_**** number of votes.

  

2. ****Diana DeGette**** received *********_73.8%*_**** of the vote and *********_272,892*_**** number of votes.

  

3. ****Raymon Anthony Doane**** received *********_3.1%*_**** of the vote and *********_11,606*_**** number of votes.

  

#### The winner candidate :

  

* With total of *********_272,892*_**** votes ****Diana DeGette,**** received *********_73.8%*_**** of the total votes casted in the election.

  

![Election Results](https://github.com/awalindeep/Election_Analysis/blob/AwalinGHMAIN/Resources/Election_results.png)

#### [Output of Election Results in Terminal from VS Code](https://github.com/awalindeep/Election_Analysis/blob/AwalinGHMAIN/Resources/Election_results.png)

![Election Results txt](https://github.com/awalindeep/Election_Analysis/blob/AwalinGHMAIN/Resources/Election_Result_txt.png)
  #### [Output of Elections Result from txt file](https://github.com/awalindeep/Election_Analysis/blob/AwalinGHMAIN/analysis/election_results.txt)

## ****Election-Audit Summary****

  

[PyPoll_Challenge.py](https://github.com/awalindeep/Election_Analysis/blob/AwalinGHMAIN/PyPoll_Challenge.py) script has been developed to automate the elections results for Colorado Board of Elections utilizing [elections_results.csv](https://github.com/awalindeep/Election_Analysis/blob/AwalinGHMAIN/Resources/election_results.csv) file. This is a powerful script that can be used to automate other election audits even at federal levels.

  

Utilizing this script will analyze large set of data in seconds and can return the results automatically. With minor tweaks this code can

* Structure much larger data base. For example - Current script find names of candidates and counties, it can be re-used for other counties to find unique sets and return results.

* Can read large data files such as csv files based on other dependencies.

  

To summarize this script in python have many advantages like automating processes, quick and fast execution of codes and reuse of code with minor tweaks. This code can be used on similar projects such as other provincial elections, federal elections or local elections and much more.
