# Model Equations

## 1. Simple Regression Equation 1 (Marketing Spend)

**Equation:**

Monthly Sales = 560777.35 + (2.13 × Marketing Spend)

**Interpretation:**

For every one-unit increase in marketing spend, monthly sales are expected to increase by approximately 2.13 units, assuming all other factors remain constant.

---

## 2. Simple Regression Equation 2 (Footfall)

**Equation:**

Monthly Sales = 446410.58 + (35.68 × Footfall)

**Interpretation:**

For every additional customer visiting the store, monthly sales are expected to increase by approximately 35.68 units.

---

## 3. Multiple Regression Equation

**Equation:**

Monthly Sales = 96294.24
+ (1.18 × Marketing Spend)
+ (27.99 × Footfall)
- (71956.85 × Average Discount Percentage)
+ (3002.85 × Staff Count)
+ (2983.78 × Inventory Availability Percentage)
- (2883.79 × Competitor Distance)
+ (12790.85 × Holiday Flag)
+ (10456.51 × Customer Rating)

---

## 4. Explanation of Each Coefficient

- **Marketing Spend:** Higher marketing expenditure leads to increased sales.
- **Footfall:** More customers visiting the store increase sales.
- **Average Discount Percentage:** Higher discounts are associated with lower sales in this dataset.
- **Staff Count:** More staff members improve store operations and increase sales.
- **Inventory Availability Percentage:** Better stock availability positively impacts sales.
- **Competitor Distance:** Greater competitor distance shows a negative relationship with sales in this model.
- **Holiday Flag:** Sales tend to increase during holidays.
- **Customer Rating:** Higher customer satisfaction results in higher sales.

---

## 5. Explanation of Dummy Variables

Categorical variables such as **Region** and **Store Type** were converted into dummy variables.

Example:

- Region_North = 1 if the store belongs to North region, otherwise 0.
- Region_South = 1 if the store belongs to South region, otherwise 0.
- Region_East = 1 if the store belongs to East region, otherwise 0.

Dummy variables allow categorical data to be used in regression analysis.

---

## 6. Reference Category Used

The **West region** was selected as the reference category and was excluded from the regression model to avoid multicollinearity.

---

## 7. Final Model Selected

The **Multiple Regression Model** was selected as the final model.

---

## 8. Reason for Selecting the Final Model

The multiple regression model was selected because it achieved the highest R-squared value (**0.828**), explaining approximately **82.8%** of the variation in monthly sales. It considers multiple business factors simultaneously and provides better predictive performance than simple regression models.
