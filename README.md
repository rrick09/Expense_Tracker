# Expense Tracker

## Overview
The Expense Tracker is a simple command-line application that helps users manage their personal finances by tracking expenses, adding money to their budget, and exporting transactions to a CSV file. The program also provides summaries of spending and available funds.

## Features
- *Add Expenses*: Record expenses with date, category, amount, and description.
- *Add Money*: Increase available budget by adding income.
- *View Bank Statement*: Displays all recorded transactions.
- *Check Total Spending*: View total expenses and income.
- *Check Spending on a Specific Day*: Get total expenses for a specific date.
- *Check Remaining Budget*: View the balance after income and expenses.
- *Export Transactions to CSV*: Save transactions for further analysis.

## Requirements
- Python 3.x

## Usage
Run the script in a terminal:
sh
python expense_tracker.py


### Menu Options
1. *Add Expense*: Enter expense details such as date, category, description, and amount.
2. *Add Money*: Add funds to your budget.
3. *View Bank Statement*: See a list of all transactions.
4. *Check Total Spending*: View total money spent and total income.
5. *Check Spending on a Specific Day*: Enter a date to see expenses for that day.
6. *Check Remaining Budget*: Display the balance after accounting for expenses.
7. *Export Transactions to CSV*: Save transactions in transactions.csv.
8. *Exit*: Quit the program.

## Data Storage
- Transactions and budget data are stored in bank_statement.txt as JSON.
- Transactions can be exported to transactions.csv.

## Error Handling
- Ensures valid input types (e.g., numeric values for money).
- Prevents spending beyond available budget.
- Handles missing or corrupted data files gracefully.

