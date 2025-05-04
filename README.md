# Walmart Customer Purchase Behavior Analysis

## Project Overview

This project analyzes customer purchase behavior at Walmart, specifically focusing on purchase amounts in relation to gender and other demographic factors. The goal is to help the business make better decisions by understanding spending habits across different customer segments.

## Dataset Description

The dataset contains 550,068 records with 10 columns including:
- `User_ID`: Unique identifier for customers
- `Product_ID`: Unique identifier for products
- `Gender`: Gender of customer (F/M)
- `Age`: Age group of customer (0-17, 18-25, 26-35, 36-45, 46-50, 51-55, 55+)
- `Occupation`: Occupation category (coded as numbers)
- `City_Category`: Category of city (A, B, C)
- `Stay_In_Current_City_Years`: Years of stay in current city (0, 1, 2, 3, 4+)
- `Marital_Status`: Marital status (0=single, 1=married)
- `Product_Category`: Category of product
- `Purchase`: Purchase amount

## Analysis Methods

The analysis uses:
- Descriptive statistics
- Data visualization
- Central Limit Theorem application
- Confidence interval calculation
- Hypothesis testing

## Key Findings

1. Gender differences:
   - Males account for 75% of users and spend more on average (925,344.40) than females (712,024.39)
   - Male spending patterns differ by age group, with 51-55 showing highest average purchases

2. Age distribution:
   - 40% of users are 26-35 years old
   - 20% are 36-45 years old
   - 18% are 18-25 years old

3. Marital status:
   - 60% of users are single, 40% are married
   - Single users spend more on average (880,380.08) than married users (843,047.92)

4. City categories:
   - Males from City Category A have higher purchase values
   - Females from City Category A have lower purchase values

## Confidence Intervals

- Single users: 95% CI (822,263.99, 938,496.17)
- Married users: 95% CI (776,119.16, 909,976.68)
- Various age groups have distinct confidence intervals showing different spending patterns

## Recommendations

1. Focus on retaining and acquiring male customers who spend more
2. Develop unique product combinations targeting single users
3. Research product preferences for the 18-50 age demographic
4. Increase product offerings in City Category C where male customers spend more
