# Telecom Customer Churn Analysis Project

This project analyzes customer churn patterns in a telecommunications company using data analysis techniques. The goal is to answer the question: "What factors contribute most to customer churn?"

## Technologies Used

- Python
- Pandas for data manipulation
- Matplotlib/Seaborn for visualization


## Dataset Description

### Overview

The dataset represents information about customers of a telecom service provider. Each row corresponds to a unique customer, with various attributes described in the dataset metadata.

### Columns

The dataset includes the following types of information:

- Churn Information: Indicates whether the customer left the service within the last month.

- Services Subscribed:

    - Phone service

    - Multiple lines

    - Internet service

    - Online security

    - Online backup

    - Device protection

    - Tech support

    - Streaming TV

    - Streaming movies

- Customer Account Information:

    - Tenure (how long the customer has been with the service)

    - Contract type (monthly, yearly, etc.)

    - Payment method

    - Paperless billing

    - Monthly charges

    - Total charges

- Demographic Information:

    - Gender

    - Age range

    - Partner status

    - Number of dependents

## Procedure for Analysis

1. Preprocessing

    - Handling Missing Values: Identify and fill or remove missing data.

    - Data Type Conversion: Ensure correct data types for each column (e.g., numeric, categorical).

    - Encoding Categorical Variables: Convert categorical variables into numerical representations if necessary.

2. Exploratory Data Analysis (EDA)

    - Summary Statistics: Generate basic descriptive statistics for numerical columns.

    - Visualization:

        - Box plots for numerical features.

        - Bar plots for categorical features.

        - Correlation heatmaps to identify relationships between variables.

3. Statistical Analysis

    - Chi-Square Test for Categorical Variables:

        - Test the association between churn and categorical features (e.g., gender, contract type, payment method).

        -  Identify statistically significant relationships.

        - Report p-values and interpret the results.

## Key Findings

1. Contract Type Impact:
    - Month-to-month contracts show significantly higher churn rates
    - Long-term contracts (1-2 years) demonstrate better customer retention

2. Service Features:
    - Customers without online security and tech support are more likely to churn
    - Multiple services subscription correlates with lower churn rates

3. Payment and Billing:
    - Electronic payment methods show lower churn compared to mailed checks
    - Higher monthly charges correlate with increased churn probability

4. Demographics:
    - Senior citizens show slightly lower churn rates
    - Partner status and dependents correlate with longer customer retention

5. Customer Tenure:
    - Newer customers (0-12 months) have highest churn risk
    - Loyalty increases significantly after 24 months of service
