# Bank-Transaction-Analysis-Python

This project focuses on analyzing bank transaction data using Python. It includes data loading, cleaning, processing, trend identification, and generating useful financial insights. The goal is to convert raw transactional data into an organized, meaningful, and decision-friendly format.

# 1. Import Required Libraries

## Used essential Python libraries for data handling and visualization:

  * **pandas for data cleaning and analysis**

  * **numpy for numerical operations**

  * **matplotlib / seaborn for visual insights**

  * **csv for reading transaction files**


# 2. Load the Dataset

  * Loaded the bank transaction CSV file using pandas.read_csv().

  * Displayed first few rows using df.head() to understand the structure.

  * Checked column names, missing values, and data types.


# 3. Data Cleaning & Preprocessing

## Performed necessary cleaning steps:

  * Removed duplicate records.

  * Filled or handled missing values.

  * Converted date columns to datetime format.

  * Converted amount and balance columns to numeric values.

  * Sorted the dataset by date/time.


## 4. Checking Balance Status

### Evaluated the final balance using:

    df['Balance'].iloc[-1]


    Identified if the account ended with zero balance, positive, or negative balance.

    Highlighted unusual or unexpected ending balances.


## 5. Identify High-Value Transactions

### Filtered transactions above a fixed threshold (e.g., ₹10,000):

    df[df['Amount'] > 10000]


### Categorized them into:

    * High-value debits

    * High-value credits


### Useful for detecting major spending or incoming funds.


# 6. Transaction Categorization

### Grouped transactions based on type, such as:

    * Cash withdrawal

    * UPI/Online payments

    * EMI/Loan

    * Salary/Income

    * ATM transactions

### Helps in understanding spending patterns.


# 7. Monthly / Weekly Trend Analysis

## Generated insights such as:

    * Total spending per month

    * Total credits (income) per month

    * Highest spending category

    * Top spending dates

    * Recurring expenses


# 8. Detect Unusual Patterns

    * Identified duplicate transactions

    * Spikes in daily expenditure

    * Large sudden debits

    * Unexpected balance drops

This helps in fraud detection and financial review.


# 9. Data Visualization

## Created visual reports using:

    * Bar charts (monthly spending)

    * Line charts (balance movement)

    * Pie charts (category-wise expenses)

These visuals make the data easy to understand.


# 10. Summary Report Generation

## Created a final summary including:

    * Total debits & credits

    * Highest debit & highest credit

    * Number of high-value transactions

    * Monthly expense comparison

    * Ending balance

This becomes the final deliverable of the analysis.


# 🛠️ Tech Stack

    * **Python 3**

    * **Pandas**

    * **NumPy**

    * **Matplotlib / Seaborn**

    * **Jupyter Notebook / VS Code**


# 🎯 Project Outcome

## By the end of this project, the bank transaction data is fully cleaned, analyzed, and visualized. The analysis highlights:

    * Spending behavior

    * Income trends

    * Potential issues or anomalies

    * High-value transactions

Final financial summary

This project is ideal for financial analysis, personal budgeting, or identifying transaction irregularities.
