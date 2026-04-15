# Spread Locator – Statistical Distribution Analysis of E-commerce Transactions
Project Explanation Video
Video Link: https://drive.google.com/drive/u/0/folders/1cwWqVc7dUAXSdi1-yncFfHfljyOk-L2P

## Overview

This project analyzes customer transaction behavior on an e-commerce platform using statistical distribution techniques. It focuses on understanding how transaction data behaves, identifying suitable probability distributions, and handling skewed data for better analysis.

---

## Project Objective

The objective of this project is to:

- Analyze transaction patterns using statistical distributions  
- Identify whether data follows known distributions  
- Handle skewed data using transformations  
- Extract insights for business decision-making  

---

## Dataset Description

The dataset includes the following fields:

- transaction_id – Unique transaction identifier  
- customer_id – Unique customer identifier  
- transaction_amount – Transaction value (₹)  
- transaction_date – Date of transaction  
- transaction_count – Number of transactions per week  
- region – Customer region  
- transaction_status – Success or Failure  

---

## Tools and Libraries

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- SciPy  
- Statsmodels  

---

## Analysis Performed

### Bernoulli Distribution
- Modeled transaction success/failure as binary outcomes  
- Calculated probability of success  

---

### Binomial Distribution
- Analyzed number of successful transactions over multiple trials  

---

### Poisson Distribution
- Modeled number of daily transactions  
- Estimated average rate (λ)  

---

### Log-Normal Distribution
- Modeled skewed transaction amounts  
- Applied log transformation  

---

### Power Law Distribution
- Analyzed distribution with few high-value transactions  

---

### Q-Q Plot Analysis
- Checked whether data follows normal distribution  

---

### Box-Cox Transformation
- Converted skewed data to near-normal distribution  

---

### Z-Score Analysis
- Standardized transaction values  
- Identified high-value transactions  

---

### PDF and CDF
- Visualized probability density function  
- Analyzed cumulative distribution  

---

## Key Concepts Covered

- Statistical distributions  
- Discrete vs continuous data  
- Bernoulli, Binomial, Poisson  
- Log-Normal and Power Law  
- Q-Q Plot  
- Box-Cox Transformation  
- Z-score  
- PDF and CDF  

---

## Key Insights

- Transaction success follows Bernoulli distribution  
- Weekly transactions follow Binomial distribution  
- Daily transactions approximate Poisson distribution  
- Transaction amounts are right-skewed  
- Log-Normal distribution best fits transaction amounts  
- High-value transactions are rare  

---

## Use Cases

- Risk analysis  
- Fraud detection  
- Customer behavior analysis  
- Financial data modeling  

---

## Limitations

- Synthetic or limited dataset  
- No real-time data  
- Assumes independence of events  

---

## Future Improvements

- Use real-world large-scale datasets  
- Integrate machine learning models  
- Add predictive analytics  
- Build interactive dashboards  

---

## Conclusion

This project demonstrates how statistical distribution techniques can be applied to real-world transaction data. It highlights the importance of understanding data behavior and applying the right transformations to extract meaningful insights.
