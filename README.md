 Python Expense Tracker Application

## Overview
This is a simple command-line expense tracker application in Python. It allows users to add expenses, view all recorded expenses, and get a summary of spending by category. All expense data is stored in a `expenses.csv` file.

## Features
-   **Add Expense**: Record new expenses with date, category, amount, and an optional note.
-   **View All Expenses**: Display a list of all recorded expenses and a running total.
-   **Category Summary**: Get a breakdown of spending by category.
-   **CSV Storage**: Data is saved to and loaded from `expenses.csv` for persistence.
-   **Input Validation**: Basic validation for amount and category.

## How to Use

### Prerequisites
-   Python 3.x

### Running the Application
1.  **Save the Code**: Combine all Python code into a single `.py` file (e.g., `expense_tracker.py`).
2.  **Run from Terminal**: Execute `python expense_tracker.py` in your terminal.

### Interactive Menu
The application provides a menu:

```
--- Expense Tracker Menu ---
1. Add New Expense
2. View All Expenses
3. View Category Summary
4. Exit
```

-   **Add New Expense (1)**: Enter details for a new expense.
-   **View All Expenses (2)**: See all recorded expenses and the total amount spent.
-   **View Category Summary (3)**: Get a summary of spending per category.
-   **Exit (4)**: Close the application.

## File Structure
-   `expenses.csv`: Automatically created to store all expense data.

## Example Usage

1.  **Add an expense:**
    ```
    Enter your choice (1-4): 1
    Enter date (YYYY-MM-DD, leave blank for today): 
    Enter category: Groceries
    Enter amount: 55.75
    Enter note (optional): Weekly shopping
    Expense added successfully!
    ```

2.  **View expenses:**
    ```
    Enter your choice (1-4): 2

    --- All Expenses ---
    Date         Category        Amount     Note                     
    -----------------------------------------------------------------
    2023-10-27   Groceries       55.75      Weekly shopping          
    -----------------------------------------------------------------
    Total spent: 55.75
    ```

3.  **View category summary:**
    ```
    Enter your choice (1-4): 3

    --- Category-wise Spending Summary ---
    Groceries: 55.75
    ```
```
