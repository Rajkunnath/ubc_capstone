# Used Car Sales

## Executive Summary

This report aims to provide actionable insights into the factors influencing used car prices, helping your dealership optimize inventory and pricing strategies. By leveraging data-driven models, we identified key determinants of used car prices and evaluated the performance of various predictive models. Our findings and recommendations will assist in making informed decisions to enhance profitability and meet customer demands effectively.

## Business Objective

The primary goal is to understand what factors make a car more or less expensive and provide recommendations on what consumers value in a used car. This understanding will help your dealership fine-tune its inventory and pricing strategies.

## Data Preparation

    Data Cleaning: Removed rows with missing values to ensure the quality of the data.
                   Removed duplicate rows
                   Removed vehicles with price <100
                   Removed buses and others from the list
                   
    Encoding Categorical Variables: Used LabelEncoder to convert categorical variables into numerical format.

    Data Split: Divided the data into training and testing sets to evaluate model performance effectively.
    
## Model Evaluation
We evaluated four different models: Linear Regression, Lasso Regression, Ridge Regression, and Random Forest. Here are the key performance metrics:

    Linear Regression: Moderate performance.
    Lasso Regression: Slight improvements over linear regression.
    Ridge Regression: Better performance, reducing overfitting.
    Random Forest: Best performance with the lowest RMSE and CV_RMSE, indicating high accuracy and generalizability.
    
## Key Findings

    Age: Newer cars are more expensive.
        
    Odometer: Lower mileage significantly increases car prices.
    
    Cylinder: Cylinders have impact on the prices. Higher Cylinder has higher price
        
    Drive: Cars with various drive type has impact on the price

    Model: Cars from well-known manufacturers model  command higher prices due to brand value.
    
    Additional Features: Fuel type, transmission, drive type, and color also affect prices, albeit to a lesser extent.

## Recommendations

**Inventory Strategy:***
    
    Focus on acquiring *newer* cars from reputed manufacturers and models.

    Prioritize vehicles with lower mileage and in good condition.

**Pricing Strategy:**

    Use the Random Forest model to set competitive and profitable prices.

**Model Updates:**

    Regularly update the model with new data to maintain accuracy.
    
Our analysis provides a comprehensive understanding of the factors influencing used car prices. By adopting data-driven pricing and inventory strategies, your dealership can enhance profitability and better meet customer demands. Regular updates and continuous monitoring of market trends will ensure sustained success.
