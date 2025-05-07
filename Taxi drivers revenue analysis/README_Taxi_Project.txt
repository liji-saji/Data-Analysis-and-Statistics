
Maximizing Revenue for Taxi Cab Drivers through Payment Type Analysis

Problem Statement
-----------------
In the fast-paced taxi booking sector, maximizing revenue is essential for long-term success and driver satisfaction. This project aims to use data-driven insights to identify whether payment methods impact fare pricing, focusing on the relationship between payment type and fare amount.

Objective
---------
The main goal of this project is to perform A/B testing to examine the relationship between total fare amount and payment method (Card vs Cash). Using Python, we apply hypothesis testing and descriptive statistics to extract actionable insights that help taxi drivers increase their earnings.

Research Question
-----------------
Is there a relationship between total fare amount and payment type, and can we nudge customers toward payment methods that generate higher revenue for drivers, without negatively impacting customer experience?

Analysis
--------
- **Distribution Analysis**:
  - Most fares fall in the ₹5–₹15 range.
  - For higher fare amounts, customers prefer using cards over cash.
  - Trip distance and duration are also higher when the payment is made by card.

- **Passenger Count Distribution**:
  - Single-passenger rides dominate, especially for card payments.
  - Multi-passenger trips are also more likely to be paid by card for higher distances and fares.

- **Descriptive Statistics**:
  - Mean fare amount for card payments: ₹13.11
  - Mean fare amount for cash payments: ₹11.75
  - Mean trip distance and duration are both higher for card payments.

- **Hypothesis Testing**:
  - Null Hypothesis: There is no significant difference in average fare between card and cash payments.
  - Alternative Hypothesis: There is a significant difference.
  - **Test Used**: Mann-Whitney U Test (non-parametric)
  - **Result**: U statistic = 714031552642.5, p-value = 0.0
  - **Conclusion**: Reject the null hypothesis. There is a significant difference in fare amounts between payment types.

Conclusion
----------
The analysis indicates that customers who use credit cards tend to take longer and more expensive rides compared to those who use cash. This suggests that card-paying customers may represent a more valuable segment for taxi drivers.

Recommendations
---------------
- **Incentivize Card Payments**: Encourage drivers to promote card payments by offering digital payment discounts or loyalty rewards.
- **Marketing Strategy**: Taxi service providers can target frequent high-value riders (e.g., business professionals) who are more likely to pay by card.
- **Driver Insights**: Train drivers to identify patterns in rider behavior by payment type and offer services accordingly.
- **Improve Digital Infrastructure**: Ensure card payment systems are robust, quick, and reliable across all taxis.

