# python-challenge
# PyPoll Election Analysis

## Overview
This project is part of a Python challenge to help a small rural town modernize its vote-counting process. The dataset provided, `election_data.csv`, contains voting data, including Voter ID, County, and Candidate. The goal is to write a Python script that processes this dataset and provides a comprehensive election result analysis.

## Objectives
The Python script analyzes the election data to calculate the following:

1. **Total number of votes cast**.
2. **List of candidates** who received votes.
3. **Percentage of votes** each candidate won.
4. **Total number of votes** each candidate won.
5. **The winner** of the election based on the popular vote.

## File Descriptions
- `election_data.csv`: The dataset containing the election data.
- `PyPoll_Skeleton.py`: The Python script that reads the dataset, performs the analysis, and outputs the election results.
- `README.md`: This file, providing an overview of the project and how to run it.

## How to Use

### Prerequisites
To run the Python script, you'll need:
- Python 3.x installed on your machine.
- The `election_data.csv` file in the appropriate directory.

##Code Explanation
The Python script uses the csv module to read the data and performs the following steps:

- Reading the dataset: The script opens and processes the election_data.csv file.
- Counting total votes: Each row in the dataset represents a vote, and the script counts the total number of rows to determine the total votes cast.
- Tallying votes for each candidate: A dictionary is used to store each candidate's total votes.
- Calculating the percentage of votes: For each candidate, the percentage of the total vote is calculated.
- Determining the winner: The candidate with the highest number of votes is declared the winner.
##Output
Election Results
-------------------------
Total Votes: 3521001
-------------------------
Khan: 63.000% (2218231)
Correy: 20.000% (704200)
Li: 14.000% (492940)
O'Tooley: 3.000% (105630)
-------------------------
Winner: Khan
-------------------------

