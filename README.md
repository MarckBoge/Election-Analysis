# Election-Analysis


## Project Overview

A Colorado Board of Elections employee asked for our assist with completing an audit of a recent local congressional election. We are task with reporting the following:

      1. The total number of votes casted.
      2. Get a complete list of candidates who received votes.
      3. The total number of votes for each candidate.
      4. The percentage number of votes for each candidate.
      5. The winner of the election based on the popular vote.
   
## Resources
  
* Data Source: election_results.csv
  
* Software: Python 3.9.12, Visual Studio Code 
  
## Summary
  
The analysis of the election show that:
* There were 369,711 votes cast in the election.
* The candidates were:
    	- Charles Casper Stockham
	- Diana DeGette
	- Raymon Anthony Doane
* The candidate results were:
	- Charles Casper Stockham received **_23.0%_** of the vote and _85,213_ number of votes.
	- Diana DeGette received **_73.8%_** of the vote and _272,892_ number of votes.
	- Raymon Anthony Doane received **_3.1%_** of the vote and _11,606_ number of votes.
  
* The **winner** of the election was:
	- **Diana DeGette**, who received **272,892** number of votes, and **73.8%** of the total number of votes cast in the election.
	
	
## Overview of Election Audit:
  
  WE helped Seth and Tom complete an audit on the results of a recent local congressional election.
  
  	* How many votes were cast in this congressional election?
	
		- Total Votes: 369,711
		
	* Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.	
		
		##County Votes:
		
		- Jefferson: 10.5% (38,855)
		- Denver: 82.8% (306,055)
		- Arapahoe: 6.7% (24,801)
		
	* Which county had the largest number of votes?
	
		- Largest County Turnout: Denver
  
	* Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
	
		##Candidate Votes:
		
		- Charles Casper Stockham: 23.0% (85,213)
		- Diana DeGette: 73.8% (272,892)
		- aymon Anthony Doane: 3.1% (11,606)
	
	* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
		
		- Winner: Diana DeGette
		- Winning Vote Count: 272,892
		- Winning Percentage: 73.8%
	

	

## Election-Audit Summary:

   The purpose of this project was to build a robust code using Python to creating a program. 
   That performs complex calculation, and repetitive operations for any dataset that will provide detailed results.
   
   This program can be applied to other elections with simple modification can be made to the program code to fit any dataset.
   
   For example:
   
   This script can be modify to show more or less additional information on the election_results.txt 
   file by updating the syntax command lines in the script.
   
   Example 1 
   
   Add Largest County Vote Count and Largest County Vote Percentage below the Largest County Turnout command line.
   
   		f"Largest County Turnout: {largest_county_name}\n"
      		f"Largest County Vote Count: {largest_county_name:,}\n"
      		f"Largest County Vote Percentage: {vote_percentage:.1f}%\n")


   Example 2
   
   Changing Variables to fit any election dataset.
   
   		# Initialize a total vote counter.
		total_votes = 0

		# Candidate Options and candidate votes.
		candidate_options = []
		candidate_votes = {}

		# 1: Create a county list and county votes dictionary.
		county_list = []
		county_votes = {}


		# Track the winning candidate, vote count and percentage
		winning_candidate = ""
		winning_count = 0
		winning_percentage = 0

		# 2: Track the largest county and county voter turnout.
		largest_county_turnout = ""
		largest_county_votes = 0

