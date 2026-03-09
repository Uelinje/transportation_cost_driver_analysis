# Retail Profitability & Discount Policy Analysis

## Business Problem

A retail company generated **~$13M in revenue but only ~$1M in profit**, indicating substantial margin leakage.

This project investigates:

- What factors are driving low profitability?
- How do discount policies affect margins?
- What pricing strategy could improve profitability?

The analysis combines **SQL, Python, and Power BI** to identify profit drivers and simulate pricing scenarios.

---

# Key Insights

### 1. Shipping Cost Consumes Most Profit

Total Shipping Cost ≈ **$1M**, nearly equal to total profit.

This suggests logistics costs are a major driver of margin erosion.

---

### 2. Heavy Discounts Destroy Profitability

Orders with discounts above **20% generate negative margins**.

| Discount Bucket | Avg Margin |
|-----------------|------------|
| No Discount | ~26% |
| Low (0–10%) | ~18% |
| Medium (10–20%) | ~15% |
| High (>20%) | **-29%** |

---

### 3. Category-Level Profitability

Furniture category drives most losses, while Technology and Office Supplies remain profitable.

---

### 4. Pricing Policy Simulation

A simulation model tested profit sensitivity to discount reduction.

If deep discounts are limited:

Assumption: **customer demand remains constant.**

---

# Analytical Workflow

---

# Dashboard Overview

![Dashboard](images/dashboard_overview.png)

The dashboard enables decision-makers to explore:

- Profit drivers
- Discount behavior
- Category profitability
- Pricing policy scenarios

---

# Discount vs Margin Analysis

![Discount Margin](images/discount_margin_analysis.png)

High discounting (>20%) produces negative profit margins.

---

# Category Profitability

![Category Profit](images/category_profit_analysis.png)

Furniture category contributes disproportionately to losses.

---

# Discount Policy Simulation

![Simulation](images/pricing_simulation.png)

Reducing deep discounts significantly increases profit.

---

# Technologies Used

- Python
- Pandas
- SQL (SQLite)
- Power BI
- Jupyter Notebook

---

# Repository Structure

---

# Business Recommendation

Limit discounts above **20%**, particularly in loss-making categories.

A pricing discipline policy could significantly increase profitability without requiring revenue growth.

---

# Skills Demonstrated

- Data Cleaning
- SQL Analytics
- Feature Engineering
- Profitability Modeling
- Scenario Simulation
- Business Intelligence Dashboarding
- Data Storytelling

