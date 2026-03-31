📊 Statistical Distribution Analysis of E-commerce Transactions
🎥 Project Explanation Video

👉 Video Link: https://drive.google.com/drive/u/0/folders/1cwWqVc7dUAXSdi1-yncFfHfljyOk-L2P

📌 Project Overview

This project focuses on analyzing customer transaction behavior on an e-commerce platform using statistical distribution techniques.

The main objective is to understand:

How transactions behave statistically
Whether data follows known distributions
How to handle skewed data
What insights can be derived for decision-making
🧾 Dataset Description

The dataset contains the following fields:

Column Name	Description
transaction_id	Unique ID for each transaction
customer_id	Unique ID for each customer
transaction_amount	Amount of transaction (₹)
transaction_date	Date of transaction
transaction_count	Number of transactions per week
region	Customer region (North, South, etc.)
transaction_status	Success or Failure
⚙️ Tools & Libraries Used
Python
NumPy
Pandas
Matplotlib
Seaborn
SciPy
Statsmodels
📊 Tasks Performed
1. Bernoulli Distribution
Modeled transaction success/failure as binary outcomes
Calculated probability of success
2. Binomial Distribution
Modeled number of successful transactions over multiple trials
3. Poisson Distribution
Analyzed number of transactions per day
Estimated average rate (λ)
4. Log-Normal Distribution
Modeled skewed transaction amounts
Applied log transformation
5. Power Law Distribution
Analyzed distribution where few large values dominate
6. Q-Q Plot
Checked whether data follows normal distribution
7. Box-Cox Transformation
Converted skewed data into normal-like data
8. Z-Score Analysis
Standardized transaction values
Calculated probability of high-value transactions
9. PDF & CDF Analysis
Visualized probability density and cumulative probability
📈 Key Concepts Explained
Statistical Distributions
Discrete vs Continuous Data
Bernoulli, Binomial, Poisson
Log-Normal and Power Law
Q-Q Plot
Box-Cox Transformation
Z-score
PDF and CDF
🔍 Key Insights
Transaction success follows Bernoulli distribution
Weekly transactions follow Binomial distribution
Daily transactions approximate Poisson distribution
Transaction amounts are right-skewed
Log-Normal distribution best fits transaction amount data
Box-Cox transformation improves normality
High-value transactions are relatively rare
🧠 Conclusion

This project demonstrates how statistical techniques can be applied to real-world transaction data.

The analysis shows that:

Data is not normally distributed
Skewness is present in transaction amounts
Log-Normal distribution is most suitable

These insights can help businesses in:

Risk analysis
Fraud detection
