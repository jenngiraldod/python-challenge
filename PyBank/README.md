# python-challenge
# PyBank Financial Analysis

## Overview
This project is part of a Python challenge to analyze financial records for a company. The dataset provided, `budget_data.csv`, contains two columns: `Date` and `Profit/Losses`. The goal is to write a Python script that processes this dataset and calculates key financial metrics.

## Objectives
The Python script analyzes the records to calculate the following:

1. **Total number of months** in the dataset.
2. **Net total amount** of "Profit/Losses" over the entire period.
3. **Average change** in "Profit/Losses" over the entire period.
4. **Greatest increase** in profits (date and amount) over the entire period.
5. **Greatest decrease** in profits (date and amount) over the entire period.

## File Descriptions
- `budget_data.csv`: The dataset containing the financial records.
- `PyBank_Skeleton.py`: The Python script that reads the dataset, performs the analysis, and outputs the results.
- `README.md`: This file provides an overview of the project.

## How to Use

### Prerequisites
To run the Python script, you'll need:
- The `budget_data.csv` file located in the `Resources` folder.

## Code Explanation
The Python script uses the csv module to read the data and performs the following steps:

- Reading the dataset: The script opens and processes the budget_data.csv file.
- Calculating total months: It counts how many rows are in the dataset (each row represents a month).
- Summing the total "Profit/Losses": The script calculates the net total of all profit/losses.
- Calculating the changes in "Profit/Losses": It computes the month-to-month changes and stores them in a list to find the average.
- Finding the greatest increase/decrease: The script tracks the largest monthly increase and decrease in profits.

## Output
Financial Analysis
----------------------------
Total Months: 86
Total: $38382578
Average Change: $-2315.12
Greatest Increase in Profits: Feb-2012 ($1926159)
Greatest Decrease in Profits: Sep-2013 ($-2196167)
