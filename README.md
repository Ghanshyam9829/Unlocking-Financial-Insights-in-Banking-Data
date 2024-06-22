## Banking

### **Case Study: Unlocking Financial Insights in Banking Data**

### **Background**

As a data analyst at FinInsight Group, a consultancy specializing in banking analytics, you are equipped with two comprehensive datasets: 'Banking Transactions' and 'Customer Account Details'. The 'Banking Transactions' dataset records detailed transaction data, including types, amounts, dates, and branch information. The 'Customer Account Details' dataset provides insights into account holders, covering account types, balances, interest rates, credit scores, and loan amounts.

### **Objective**

Employ Power BI to analyze these banking datasets, unraveling intricate patterns and behaviors. This involves data cleaning, modeling, and using DAX for complex analytics. The goal is to create an interactive dashboard illustrating transactional trends, customer profiles, and the banking ecosystem. Analysis should include customer transaction behaviors, relationships between account characteristics and financial health, and factors influencing credit scores and loan management. Insights will guide FinInsight Group in advising banks on optimizing services, enhancing satisfaction, and managing risks.

### **Data Source:**

[BankingDataset1.xlsx](https://docs.google.com/spreadsheets/d/1qm2RrQuwWTJPkmDu3KgpEVxBrm373HWt/edit?usp=sharing&ouid=106912519366189828264&rtpof=true&sd=true)

[BankingDataset2.xlsx](https://docs.google.com/spreadsheets/d/1Id8rth_sWwzrcxxEKJA5UMEA7EbD_5az/edit?usp=sharing&ouid=106912519366189828264&rtpof=true&sd=true)

### **Part 1: Data Cleaning, Modeling, and DAX in Power BI**

1. **Data Importing and Initial Examination**
    - Import datasets into Power BI and perform a preliminary examination.
2. **Merging and Relating Datasets**
    - Merge datasets using a key column and ensure accurate and complete integration.
3. **Data Cleaning and Transformation**
    - Handle missing and irrelevant data, remove duplicates, and normalize data types.
4. **Categorizing and Analyzing Transaction Types**
    - Create broader categories for transactions and analyze account balances, transaction trends, and high-value transactions.
5. **Currency and Branch Analysis**
    - Convert transactions to a standard currency and analyze branch activity.
6. **Interest Rates and Loan Analysis**
    - Examine correlations between interest rates and balances, and analyze loan amounts and credit scores.
7. **Customer and Account Analysis**
    - Analyze customer loyalty, credit score distribution, and account age correlation with balances.
8. **Advanced DAX and Predictive Modeling**
    - Develop risk assessment models, predictive models for account growth, and perform time series forecasting.
9. **Data Transformation and Extracting Information**
    - Identify unusual transactions and extract key information from account holder details.

This structured approach ensures comprehensive analysis and valuable insights for optimizing banking services.


## Banking Analysis Project

### **Introduction**

Welcome to the Banking Analysis Project. This project leverages Power BI to provide insightful analysis of banking datasets, focusing on transactional trends, customer profiles, and the overall banking ecosystem. The analysis is divided into three main sections: Transaction and Amount Analysis, Interest Rates, Credit Scores, and Loan Analysis, and Branch and Customer Analysis. These insights aim to guide FinInsight Group in advising banking institutions on optimizing services, enhancing customer satisfaction, and managing financial risks.

### **Sections**

1. **Transaction and Amount Analysis**
   - This section focuses on examining transaction types, amounts, and patterns over time. The analysis includes categorizing transactions into broader categories, investigating high-value transactions, and understanding trends across different time periods. Additionally, it involves currency conversion to standardize transaction amounts for better comparison.

2. **Interest Rates, Credit Scores, and Loan Analysis**
   - In this section, the relationship between interest rates, account balances, and loan amounts is analyzed. The correlation between credit scores and loan amounts is examined to understand customer credit behavior. This analysis helps in identifying the impact of interest rates on account balances and understanding how credit scores influence loan management.

3. **Branch and Customer Analysis**
   - This section provides insights into branch performance and customer behaviors. It involves analyzing branch activity, identifying the most active branches, and evaluating customer loyalty based on account duration. The section also includes extracting and analyzing customer demographics to understand their influence on transaction behaviors and account characteristics.
   
     ![Power Bi Front page](https://github.com/Ghanshyam9829/Unlocking-Financial-Insights-in-Banking-Data/assets/125486967/c32392c5-f757-4390-9f56-158085664ea3)



---

## Dashboard Insights: Transactions & Balance Analysis

![Dashboard 1](https://github.com/Ghanshyam9829/Unlocking-Financial-Insights-in-Banking-Data/assets/125486967/0b200807-a719-4230-ac3d-1a0d925fd9e0)


### Transaction Trend over Time - Hourly
- **Peak Transaction Volume:** 
  - Highest at 11 AM and 3 PM.
- **Peak Transaction Amounts:**
  - Highest at 2 AM and 11 AM.

### Transaction Trend over Time - Quarterly
- **Volume Stability:**
  - No significant fluctuations over time.
- **Credit vs. Debit Trends:**
  - Opposite trends in credit and debit transactions.

### Historical Trend in Transaction Volume and Forecast for Next Quarter
- **Peak Volume Period:**
  - Highest in the second half of the year (July to September).
- **Volume Consistency:**
  - Minimal fluctuations overall.
- **Future Forecast:**
  - Slight reduction in volume predicted for the next quarter.

### Average Account Balance
- **Highest Balance:**
  - "Savings" account type holds the highest average balance.

### High Value Transactions
- **Definition:**
  - Transactions > USD 5000.
- **Unusual Transactions:**
  - 2.5% of transactions are flagged as unusual or potentially fraudulent.
- **Comparison:**
  - Fewer high-value transactions compared to regular transactions.

### Rare Transaction Types
- **Definition:**
  - Transactions other than Transfer, Withdrawal, Deposit, and Payment.
- **Characteristics:**
  - Unusual transactions are mostly under the "Payment" category, with generally low values.
 
---

## Dashboard Insights: Interest Rate, Loan & Credit Score Analysis

![Screenshot (184)](https://github.com/Ghanshyam9829/Unlocking-Financial-Insights-in-Banking-Data/assets/125486967/84c8bf36-7c97-49f5-a092-ba251f55e744)


### Interest Rate and Balance Correlation
- **Observation:**
  - No correlation between interest rate and USD balance.

### Credit Score and Loan Amount Correlation
- **Observation:**
  - No correlation between credit score and loan amount.

### Account Age and Balance Correlation
- **Observation:**
  - No correlation between account age and balance amount in USD.

### Distribution of Credit Score Among Account Holders by Account Type
- **Credit Score Ranges and Predominant Account Types:**
  - **300-400:** Highest number of Checking account holders.
  - **800-900:** Highest number of Loan account holders.
  - **Others:** Highest number of Savings account holders.

#### Insight:
  - Customers with high credit scores tend to get more loans, though their count is relatively small.
  - Savings account holders have a wide range of credit scores, while the lowest credit scores belong to Checking account holders.

### Distribution of Interest Rate Among Account Holders by Account Type
- **Observation:**
  - Most account holders have an interest rate between 1% and 3%.

### Loan Amount by City and Sector
- **City Observation:**
  - London has the highest loan amounts, followed by Berlin, Sydney, and other cities.
- **Sector Observation:**
  - The technology sector has the highest loan amounts, followed by Education, Healthcare, and other sectors.


## Dashboard Insights: Branch & Customer Analysis

![Uploading Screenshot (185).png…]()


### Branch Analysis
- **Top Performing Branch:**
  - Branch 479 has the highest number of transactions with a total of 8.

### Customer Risk Assessment
- **High-Risk Customers:**
  - 9 customers with a risk score > 10.
- **Low-Risk Customers:**
  - 680 customers with a risk score < 1.

### Sector Transaction Behavior
- **Technology Sector:**
  - Highest transaction volume with a total amount of 884k.
- **Finance Sector:**
  - Lowest transaction volume.

### Demographic Transaction Behavior
- **City Comparison:**
  - Sydney: Highest transaction count with 226 transactions.
  - New York and London: Same number of transactions, but London has a higher transaction amount.

### Branch Performance
- **Highest-Performing Branch:**
  - Branch 57.
- **Top Five Performing Branches:**
  - Highlighted using a funnel chart.

### Loyalty Analysis
- **Longest Association:**
  - The most loyal customers have been associated with the bank for 1649 days.



