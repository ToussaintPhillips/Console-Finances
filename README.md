# Console Finances

## Overview

Console Finances is a JavaScript project focused on analyzing financial records of a company. Utilizing fundamental JavaScript concepts, this project parses a dataset of financial records and computes key financial metrics. This tool is designed to provide quick insights into a company's financial health over a given period.

## Purpose

The purpose of Console Finances is to enable users, especially financial analysts and business owners, to quickly assess the financial performance of a company. By automating the analysis of financial records, this tool saves time and reduces the potential for manual calculation errors.

## Features

The JavaScript code in this project performs the following analyses on the provided financial dataset:

1. **Total Number of Months**: Calculates the total number of months included in the dataset.
2. **Net Total of Profit/Losses**: Computes the net total amount of Profit/Losses over the entire period.
3. **Average Change in Profit/Losses**: Determines the average change in Profit/Losses month-to-month.
4. **Greatest Increase in Profit/Losses**: Identifies the month with the highest increase in profits and the corresponding amount.
5. **Greatest Decrease in Profit/Losses**: Identifies the month with the largest decrease in losses and the corresponding amount.

## How It Works

The JavaScript code reads the financial dataset, which is composed of arrays containing two fields: Date and Profit/Losses. The code then performs calculations to find the required financial metrics. Key steps include:

- Iterating through the dataset to calculate the cumulative totals and changes.
- Tracking month-to-month changes to compute the average change.
- Identifying the months with the greatest increase and decrease in profits/losses.
- Formatting the results and printing them to the console for easy review.

## Usage

To use Console Finances, follow these steps:

1. **Clone the Repository**: Clone the 'Console-Finances' repository to your local machine.
2. **Data Preparation**: Ensure your financial dataset is in the starter/index.js file.
3. **Run the Code**: Open the project in your browser or JavaScript runtime environment to execute the code.
4. **View Results**: Review the financial analysis printed in the console.

## Output Format

The output of the financial analysis will be displayed in the console in the following format:

```
Financial Analysis 
----------------
Total Months: [Total Months]
Total: $[Net Total]
Average Change: $[Average Change]
Greatest Increase in Profits/Losses: [Month-Year] ($[Amount])
Greatest Decrease in Profits/Losses: [Month-Year] ($[Amount])
```
