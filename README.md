# Insurance Claims Analysis Project

# Overview
  This project aims to analyze insurance claim data to provide a 360-degree view of customer claims. It combines customer and claims data, cleans and preprocesses it, and then performs various analyses to extract meaningful insights.

# Usage
  1. Data Preparation: Combine claims_data.csv and cust_data.csv to create a comprehensive dataset. This involves merging the two files based on the customer ID.

  2. Data Cleaning and Preprocessing:

      Check and correct datatypes for all columns.
      Convert claim_amount from a string to a numeric type and remove the $ sign.
      Identify and flag injury claims that were not reported to the police.
      Ensure customer IDs are unique by keeping only the most recent claim record per customer.
      Impute missing values for continuous and categorical variables appropriately.

  3. Data Analysis:

      Calculate and categorize customer ages.
      Analyze average claim amounts across different segments.
      Determine the total claim amount based on incident causes and specific conditions.
      Explore the data through various visualizations, including pie charts, bar charts, and trend analysis.

  4. Statistical Analysis: Conduct hypothesis testing to explore relationships and differences within the data, focusing on claim amounts, customer demographics, and claim details.
