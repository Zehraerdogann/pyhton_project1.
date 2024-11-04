# Telecom Customer Churn Analysis

This project, **Telecom Customer Churn Analysis**, analyzes customer churn patterns for a telecom company. Using customer demographics, payment details, and usage habits, we aim to understand which customers are more likely to churn (leave the service).

## Project Objective

The objective of this project is to identify patterns and reasons behind customer churn, helping the company retain more customers by understanding the main factors that lead to churn.

## Dataset

The dataset used for this analysis includes columns such as:
- **Customer ID**: Unique identifier for each customer
- **Demographics**: Age, gender, marital status, and number of dependents
- **Geographical Info**: City, zip code, latitude, and longitude
- **Account Info**: Payment method, monthly charges, total charges, refunds, and total revenue
- **Customer Status**: Customer’s current status (stayed, churned, or joined)
- **Churn Category & Reason**: Specific reason if the customer has churned (e.g., competitor, dissatisfaction, reliability issues)

The data was processed and analyzed to identify patterns in customer churn based on different features.

## Analysis Steps

1. **Data Cleaning**: Missing values were handled, and data types were adjusted to ensure the dataset was ready for analysis.
2. **Exploratory Data Analysis (EDA)**: An initial analysis was conducted to understand data distribution, relationships, and patterns.
   - Distribution of monthly charges, total charges, and revenue.
   - Count of churn reasons to determine the most common reasons for customer churn.
3. **Correlation Analysis**: A heatmap was created to identify correlations between numerical variables and how they may impact customer churn.
4. **Churn Reasons Analysis**: Visualized the most common reasons for customer churn, such as network reliability or dissatisfaction with the product.
5. **Gender-Based Analysis**: Analyzed total revenue based on gender to understand spending patterns across demographics.

## Results

- The **top churn reasons** identified include product dissatisfaction, network reliability issues, and competitor offerings.
- **High correlation** was found between monthly charges and total revenue, suggesting that customers with higher monthly charges contribute significantly to revenue.
- **Churn by demographics** shows variations in churn reasons across age groups and gender, offering insights into targeted retention strategies.

## Key Visualizations

### Churn Reason Distribution
![Top_10_Churn_Reasons](https://github.com/user-attachments/assets/24e7e043-f0b3-4a8d-9941-1d79b40a8374)



### Revenue by Gender
![Total_Revenue_According_to_Gender](https://github.com/user-attachments/assets/d3229015-5fcf-4fd1-995c-05ad1b3b59b4)


### Age Distributions
![Age_distribution](https://github.com/user-attachments/assets/dde8b804-2830-4ffc-99ac-bd350e847413)

### Correlation Heatmap
![Correlation Heatmap](https://github.com/user-attachments/assets/dc6a31a5-eba4-4a3a-b1ba-920572e90d74)




## Conclusion

The analysis highlights critical churn factors that can help the telecom company develop strategies to improve customer retention. By addressing the most common churn reasons, the company can focus on improving product satisfaction and network reliability to reduce churn.

