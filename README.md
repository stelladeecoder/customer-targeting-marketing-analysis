# Customer Targeting Marketing Analysis

## Overview

This project analyzes customer data to understand spending behavior and campaign response. The goal is to identify which customer segments are more likely to respond to marketing efforts and how targeting strategies can be improved.

## Business Problem

Marketing campaigns are often sent to a broad audience without clear targeting, leading to low response rates and inefficient use of resources.

The key question is:
Which customer segments are most likely to respond to marketing campaigns, and how can targeting be improved?

## Dataset

The dataset includes customer demographics, income, spending across product categories, and past campaign responses.

## Data Preparation

- Filled missing income values using the median to keep the dataset complete and realistic  
- Removed unnecessary columns  
- Created new features such as total spending and number of children  
- Grouped marital status into simplified categories (single vs partnered)  

## Analysis

The analysis focuses on understanding customer behavior and identifying patterns related to marketing response.

### Key Visualizations

- **Income Distribution**  
  Shows how customer income is spread across the dataset  

- **Income vs Total Spending**  
  Identifies higher-value customers and spending patterns  

- **Spending by Customer Group**  
  Compares behavior across different segments  

- **Campaign Response vs Spending**  
  Examines whether higher spenders are more likely to respond  

- **Response by Household Structure**  
  Analyzes how children and relationship status impact campaign engagement  

## Key Insights

- Income and spending help identify higher-value customers but do not fully explain campaign response  
- Response rates vary across customer segments and household types  
- Customers who are single and have no children tend to respond more  
- Customer behavior is influenced by both financial and lifestyle factors  

## Conclusion

A one-size-fits-all marketing approach is not effective. More targeted strategies that consider both spending behavior and customer characteristics can improve response rates and reduce wasted effort.

## Tools Used

- Python  
- Pandas  
- Matplotlib  
- Jupyter Notebook  

## Project Structure

