# Retail Sales Regression Analysis

## 1. Business Problem Summary

The objective of this project is to identify the factors that influence monthly sales across retail stores and develop regression models to predict future sales. The analysis helps businesses make data-driven decisions regarding marketing, staffing, inventory, and customer management.

---

## 2. Dataset Description

The dataset contains information about retail store performance, including sales, marketing activities, customer behavior, inventory levels, and store characteristics.

The dataset consists of 320 observations and multiple variables related to store operations and sales performance.

---

## 3. Dependent and Independent Variables

### Dependent Variable (Target Variable)
- `monthly_sales`

### Independent Variables
- `marketing_spend`
- `footfall`
- `avg_discount_pct`
- `staff_count`
- `inventory_availability_pct`
- `competitor_distance_km`
- `holiday_flag`
- `customer_rating`

Categorical variables such as region and store type were converted into dummy variables.

---

## 4. Regression Approach

The following regression techniques were used:

1. Simple Linear Regression:
- Monthly Sales vs Marketing Spend
- Monthly Sales vs Footfall

2. Multiple Linear Regression:
- Monthly Sales predicted using multiple independent variables simultaneously.

Excel Data Analysis ToolPak was used to perform regression analysis.

---

## 5. Dummy Variable Approach

Categorical variables cannot be directly used in regression models. Therefore, dummy variables were created for categorical columns such as region and store type.

For example:

- Region_North = 1 if the store belongs to North, otherwise 0.
- Region_South = 1 if the store belongs to South, otherwise 0.
- Region_East = 1 if the store belongs to East, otherwise 0.

One category was kept as the reference category to avoid multicollinearity.

---

## 6. Model Comparison Summary

| Model | R-Squared |
|--------|-----------|
| Simple Regression (Marketing Spend) | 0.167 |
| Simple Regression (Footfall) | 0.736 |
| Multiple Regression | 0.828 |

The multiple regression model showed the highest explanatory power.

---

## 7. Final Model Selected

The Multiple Linear Regression model was selected as the final model because it explains approximately 82.8% of the variation in monthly sales.

---

## 8. Business Recommendations

- Increase marketing investments strategically to improve sales.
- Focus on increasing customer footfall through promotional activities.
- Maintain adequate inventory levels to avoid stock shortages.
- Improve customer satisfaction to drive higher sales.
- Optimize staffing levels during high-demand periods.

---

## 9. Assumptions and Limitations

### Assumptions
- Linear relationship exists between predictors and sales.
- Errors are independent.
- Residuals are normally distributed.
- Variance of errors remains constant.

### Limitations
- The model may not capture external factors such as economic conditions or competitor strategies.
- Seasonal trends may not be fully represented.
- Correlation does not necessarily imply causation.

---

## 10. Screenshots Included

The project includes screenshots of:

- Simple Regression Output 1
- Simple Regression Output 2
- Multiple Regression Output
- Residual Analysis Output
- Model Comparison Table
