# A-B-test-project

 ### Business Question

Does offering a 15% discount increase total customer spending compared with regular pricing?

The objective of this A/B test is to evaluate whether the discount campaign has a statistically significant impact on customer spending.


### Dataset Description

The dataset contains purchase data from 100 customers collected over a one-week promotional campaign.

customer_id: Unique identifier for each customer
group: Control or Discount
orders_count : Number of orders placed by the customer
total_spent: Total amount spent by the customer during the week

Two groups were compared:
1-customers who saw regular prices (Control group)
2- customers who received a 15% discount (Discount group)

### Tools & Libraries Used :
 
Python (Pandas, NumPy, SciPy, Matplotlib, Seaborn)

Statistical Methods:
Shapiro–Wilk Test (Normality)
Levene’s Test (Equality of Variances)
Independent Samples t-test (Main Analysis)


### Hypotheses :

Null Hypothesis (H₀):
There is no significant difference in total customer spending between the Control and Discount groups.

Alternative Hypothesis (H₁):
There is a significant difference in total customer spendinge between the Control and Discount groups.



### statistical Tests

The following statistical tests were applied:

1. **Shapiro–Wilk Test** — to assess the normality of customer spending.
2. **Levene’s Test** — to assess equality of variances.
3. **Independent Samples t-test** — to evaluate whether the difference between the two groups was statistically significant.


The analysis showed that customers in the **Discount Group had higher total spending** compared with customers in the Control Group.

### Statistical Results

- **Shapiro–Wilk Test**
  - Control: p = 0.00018
  - Discount: p = 0.00030
  - Both groups showed statistically significant evidence of deviation from normality.

- **Levene’s Test**
  - p = 0.1489
  - No statistically significant difference in variances was detected between the two groups.

- **Independent Samples t-test**
  - t-statistic = -3.682
  - p-value = 0.0004

Since **p-value < 0.05**, the null hypothesis was rejected.

This provides statistically significant evidence that the 15% discount was associated with a difference in total customer spending between the two groups.


### Key Insights:

1-Customers in the Discount Group showed higher total spending than customers in the Control Group.

2-The result is statistically significant at the 95% confidence level.

3-Discount campaigns can drive short-term sales increases, but further testing is recommended to assess long-term profitability.



<br><br>

<img width="860" height="556" alt="Capture" src="https://github.com/user-attachments/assets/277e7a6c-2ccf-4e6e-a8a8-7e43173793ec" />

<br><br>


### Recommendations :

1. Conduct a longer-term experiment to determine whether the increase in spending is sustained after the discount period.
2. Evaluate discount profitability by comparing the additional revenue generated with the cost of the discount.
3. Conduct further A/B tests with different discount levels to identify the optimal discount strategy.
4.  Further testing is recommended to evaluate the long-term profitability of the discount strategy.


















