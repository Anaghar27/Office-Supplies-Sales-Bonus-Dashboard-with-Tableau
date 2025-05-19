# 📦 Office Supplies Sales & Bonus Dashboard

This project includes a dataset and interactive Tableau dashboard that analyze sales patterns and support bonus distribution decisions for office supply sales representatives.

## 📁 Repository Contents

- `OfficeSupplies.csv`: Sales transaction data across various regions and sales reps.
- `Employee_Bonus_Report.twbx`: Tableau workbook presenting detailed visualizations for performance monitoring and bonus analysis.

## 📄 Dataset Description

The dataset contains 43 sales records with the following fields:

| Column Name | Description |
|-------------|-------------|
| `OrderDate` | Date of the order (e.g., 4-Jul-2014) |
| `Region`    | Sales region (East, Central, etc.) |
| `Rep`       | Sales representative’s name |
| `Item`      | Type of item sold (e.g., Pen Set, Binder) |
| `Units`     | Number of units sold |
| `Unit Price`| Price per unit in USD |

The dataset provides transactional-level data useful for computing revenue, performance comparisons, and incentive distribution.

## 📊 Key Insights from the Tableau Dashboard

The **Employee Bonus Report** dashboard (in Tableau) highlights the following:

### 🔹 Regional Sales Performance
- **Central region** records high-value sales due to larger quantities and high-priced items.
- **East region** generates frequent but smaller transactions.

### 🔹 Top Performing Representatives
- Reps like **Morgan**, **Susan**, and **Richard** consistently meet or exceed sales benchmarks.
- Bonus eligibility is clearly visualized based on both revenue and unit targets.

### 🔹 Product Insights
- **Pen Set** and **Binder** are the most frequently sold items.
- High unit price items like **Pen Set** (up to \$23.95) significantly boost total revenue per transaction.

### 🔹 Time-Based Trends
- Most sales are clustered between **July and August 2014**, indicating possible seasonal demand or campaign-based selling.

## 📈 Business Value

This visualization project allows:
- Easy identification of high-performing sales reps.
- Justified bonus allocations using transparent KPIs.
- Regional and product-level insights for optimizing future sales strategies.

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Anaghar27/Office-Supplies-Sales-Bonus-Dashboard-with-Tableau.git
