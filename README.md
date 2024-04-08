# EXCEL-Bank-Transaction-Analysis
Excel analytical Dashboarding done by using Power Pivot and Data Modelling

# Bank Transaction Analysis

**[DataSet](https://drive.google.com/drive/folders/1n6wzLIw42Fr7xC5_-MehyQXrXsKI7eU4?usp=sharing)**

### **Customers Table:**

This table holds information about the bank's clients, detailing their personal and contact details alongside their associated accounts.

- **`CustomerID`**: The unique identifier for the customer (Primary Key).
- **`Name`**: The customer's full name.
- **`Age`**: The customer's age.
- **`Gender`**: The customer's gender.
- **`Email`**: The customer's email address.
- **`Address`**: The customer's residential address.
- **`Phone Number`**: The customer's telephone number.
- **`Account Type`**: The type of bank account the customer holds (e.g., Savings, Investment).
- **`Account Balance`**: The current balance in the customer's account.
- **`Joining Date`**: The date when the customer joined the bank.
- **`Country`**: The country of the customer's residence.
- **`Region`**: The regional area of the customer's residence, like West or North.

### **Transactions Table:**

Records all transactions processed by the bank, each linked to a customer account and potentially a bank branch.

- **`TransactionID`**: The unique identifier for the transaction (Primary Key).
- **`CustomerID`**: The ID of the customer who made the transaction (Foreign Key).
- **`Date`**: The date when the transaction was made.
- **`Amount`**: The financial amount of the transaction.
- **`TransactionType`**: The nature of the transaction (e.g., Transfer, Withdrawal).
- **`TransactionStatus`**: The current status of the transaction (e.g., Pending, Cancelled).
- **`Currency`**: The currency in which the transaction was made.
- **`Location`**: The place where the transaction was initiated.
- **`Device`**: The medium through which the transaction was conducted (e.g., Online, ATM, Branch).
- **`Reference Number`**: A unique reference code for the transaction.

### **TransactionDetails Table:**

Provides finer details on each transaction, including fees and authorization information.

- **`DetailID`**: The unique identifier for the transaction detail record (Primary Key).
- **`TransactionID`**: The ID of the transaction to which these details pertain (Foreign Key).
- **`Fee`**: Any additional charges applied to the transaction.
- **`PaymentMode`**: The method used for the transaction (e.g., Cash, Cheque, Credit Card).
- **`Note`**: Extra notes or comments about the transaction.
- **`AuthorizedBy`**: The person or entity that authorized the transaction.
- **`Timestamp`**: The exact date and time when the transaction detail was recorded.

## **General Instructions for Excel Data Analysis Mini Project -** Bank Transaction Analysis

1. **Download the data set from the above-given link and open the data into Excel.**
2. **Data Cleaning:**
    - Inspect and clean the dataset for any missing, duplicate, or inconsistent data. Remove them for the better accuracy of your analysis.
3. **Use of Formulas:**
    - Leverage Excel formulas to calculate derived metrics or perform necessary computations. Common functions include SUM, AVERAGE, COUNT, and others.
4. **Chart Types:**
    - Create various types of charts (e.g., bar charts, line charts, scatter plots) to visually represent relationships, distributions, or trends within the data.
5. **Chart Titles and Labels:**
    - Ensure each chart has appropriate titles, axis labels, and legends for clarity. Make the charts visually appealing and easy to understand.

### Problem Statements: -

1. Create a Schema Diagram Using any tool that you prefer and you can refer you Basic SQL Assignment 1 to recall as well C.P. Platform E-commerce Schema 
    
    NOTE:  you have to explore the things on your own.
    
2. **`Customer Engagement**:` Which demographic segment (age, gender, region) has the highest transaction frequency, indicating higher engagement with banking services?
3. **`Transaction Types Distribution**:` What is the distribution of different transaction types (Deposit, Withdrawal, Payment, Transfer) across various account types?
4. **`Transaction Volume and Value**:` Which branches have the highest volume and value of transactions? How does this correlate with the location and size of each branch?
5. **`Payment Mode Preferences**:` What are the preferred payment modes (Cash, Cheque, Credit Card) among customers of different age groups and regions?
6. **`Fee Analysis**:` What is the average fee charged per transaction type, and which transaction types generate the most revenue from fees?
7. **`Customer Loyalty and Account Balance**:` Is there a correlation between the length of customer relationship (as indicated by the Joining Date) and their account balance or type of account they hold?
8. **`High-Value Customer Identification**:` Who are the top 10 customers by transaction amount, and what are their characteristics in terms of demographics and account types?
9. **`Transaction Status Insights**:` What percentage of transactions are cancelled or pending, and what might be the common factors leading to these statuses? Can we identify any trends based on time of day, transaction type, or branch location?
10. Develop an interactive and visually appealing `dashboard` that integrates the
above insights derived from the e-commerce dataset. The dashboard should
provide user-friendly controls and interactive elements, allowing stakeholders to
explore and analyze the insights in a comprehensive and intuitive manner.
11. Bonus Point: `Additionally`, include other `insightful visualization` that highlights the
other insights.
