## Problem statement

The dashboard aims to offer insights into the bank's loan distribution, customer demographics, and loan performance over time. It provides an overview for bank management to assess the current loan portfolio and customer base.dashboard aims to evaluate the bank's loan portfolio but lacks critical risk indicators. It needs to incorporate default rates by loan grade, assess the impact of high loan amounts relative to customer income, analyze loan purpose risks, and consider geographical factors influencing loan performance. Furthermore, a more detailed examination of verification status and customer demographics is crucial for effective risk management and strategic planning.

## Steps

1.Imported 'finance 1' and 'finance 2' datasets into Excel and cleaned them using Power Query by removing unnecessary columns.

2.Combined datasets using the 'id' column as a common key for data merging.

3.Utilized Power Pivot to create interactive charts and visualizations, crafting a comprehensive dashboard for stakeholders to analyze loan data based on various parameters.

4.Arranged visualizations on the dashboard thoughtfully, enabling easy interpretation and quick insights.

5.Ensured the dashboard's interactivity, allowing users to filter information by loan grade, home ownership, loan amount, and other key metrics.

6.Resulted in the Bank Analytics Dashboard, a powerful tool for visualizing and interpreting large loan datasets, facilitating data-driven decision-making.

## Snapshot

![Screenshot 2024-01-17 195031](https://github.com/sakshibadoni21/Bank-Analytics-Dashboard/assets/152711814/8ea32a75-a01c-4a46-8364-924f59eb26d0)

# Key Insight

## Customer and Loan Overview:
The bank has a total of 39,917 customers. The maximum interest rate on loans is 24.59%, while the minimum is 5.42%.There have been 34,516 inquiries in the last 6 months.

## Loan Grade Distribution:
Loans are categorized into grades A through G, with Grade A loans having the highest amount, indicating that most of the loans issued are considered low-risk.

## Home Ownership and Loan Status:
Most customers are renting or have a mortgage, with renters having a slightly higher number of loans.The "Customer Wise Home Ownership & Loan Status" chart indicates that the majority of loans are with customers who are renting (18,899) followed closely by those with a mortgage (17,659).

## Loan Verification Status: 
A donut chart shows the verification status by total amount, with a significant portion of the loans being verified (202M out of 324M).

## Loan Performance Over Time:
The "Year Wise Loan Amount" line chart shows a steady increase in loan amounts from 2007 to 2011, indicating growth in the loan portfolio.

## Loan Amount vs. Annual Income: 
There is a bar graph showing that the total loan amount is significantly higher than the annual income of the customers, which could indicate a high level of debt relative to income.

## Geographical Distribution:
The "Top 5 State By customer's" map indicates that California (CA) and Texas (TX) have the highest number of customers.

## Loan Purpose:
The "Top 5 Purpose By Loan Amount" shows that the majority of loans are for debt consolidation, followed by credit card payments, home improvement, major purchase, and small business.

## Conclusion

The Bank Analytics Dashboard offers a detailed snapshot of the loan portfolio, emphasizing growth in low-risk loans and highlighting key markets in California and Texas. While the dashboard successfully incorporates verification status and customer demographics, it falls short in addressing critical risk factors such as default rates and detailed loan purpose analysis. To strengthen risk management, it is essential to refine the dashboard by integrating these missing elements and conducting a more in-depth examination of customer data and loan performance. Overall, the dashboard serves as a valuable tool with room for improvement in risk assessment and strategic planning.







