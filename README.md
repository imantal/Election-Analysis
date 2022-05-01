# Election-Analysis
## Overview of Election Audit

The purpose of this challenge was to help Seth and Tom perform an election audit and submit the corresponding results to the election commission. 
For this task, the final Python script will need to be able to deliver the following information: 
* Total number of votes cast
* A complete list of candidates who received votes
* Total number of votes each candidate received 
* Percentage of votes each candidate won 
* The winner of the election based on popular vote
* The voter turnout for each county
* The percentage of votes from each county out of the total count
* The county with the highest turnout


## Election-Audit Results

The results of the Election Audit are shown in the following screenshot taken after running the Python script. 

<div align="center"> 
  
![image](https://user-images.githubusercontent.com/103223944/166127759-acb6aaab-f1c8-4622-8306-63ad30ee55ab.png)
  
<div align="left"> 

It is noted that:
* A total of 369,711 votes were cast. 
* The breakdown of the number of votes and the percentage of total votes for each county in the precinct is as follows:

<div align="center"> 
  
County	|Percentage of total vote|Votes casted
----|----|----
|Jefferson|10.5%|38,855
|Denver|82.8%|306,055
|Arapahoe|6.7%| 24,801
  
 <div align="left"> 

* Denver county had the largest turnout with 306,055 votes
* The breakdown of the number of votes and the percentage of the total votes each candidate received is as follows:

<div align="center"> 
   
|Candidate	|Percentage of total vote	|Votes casted
---|---|---
|Charles Casper Stockham|	23.0%|	85,213
|Diana DeGette|		73.8%	|272,892
|Raymon Anthony Doane	|3.1%	|11,606

<div align="left"> 

* Diana DeGrette won the election with 272, 892 votes which was 73.8% of the total votes cast. 
## Election-Audit Summary
* The script prepared for the election audit works properly and can be used—with some modifications—for any election. The following modifications can be made to use the script:

* For an election with a minimum vote percentage of 50%, an if statement can be added to check if the winning candidate has secured the 50% vote, if not identify the top two candidates and show a message that election goes to the second round.

* The script can be used for “ballot measures”, where there are only two options for voter “yes” and “No”. It will be like an election with two candidates. The code can for loop the ballots (rows) and count Number of “yes” votes and divide total number of votes. If “yes” percentage is > 50% the ballot measures passes by voters. 
