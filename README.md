## 📊 Income Statement Dashboard

### 📜 Project Overview

The **Income Statement Dashboard** is a dynamic and interactive Power BI project designed to analyze and monitor key financial metrics, including **Net Income**, **Total Revenue**, and **Operating Income**. This dashboard provides stakeholders with a clear and concise overview of the company's financial performance across multiple fiscal years, aiding in strategic decision-making and financial planning.

### ✨ Objective

The primary objectives of this project are:
- To provide a comprehensive overview of the company's income statement for fiscal years FY21 and FY22.
- To highlight trends in key financial metrics, including revenue, costs, and net income.
- To support data-driven decisions by visualizing financial performance.

### 🔍 Key Insights and Features

#### 1. Key Metrics
- **Net Income (FY22):** 72.74K
- **Total Revenue (FY22):** 198.27K
- **Operating Income (FY22):** 83.38K

#### 2. Year-over-Year Financial Performance
- **Total Revenue Growth:** Increased from 168.09K (FY21) to 198.27K (FY22).
- **Net Income Growth:** Increased from 61.27K (FY21) to 72.74K (FY22).
- **Operating Income Growth:** Increased from 69.91K (FY21) to 83.38K (FY22).

#### 3. Gross Margin Analysis
- **Gross Margin (FY22):** 135.62K, up from 115.85K (FY21).

#### 4. Expense Breakdown
- **Research and Development (FY22):** 24.51K
- **Sales and Marketing (FY22):** 21.83K
- **General and Administrative (FY22):** 5.90K

#### 5. Visualizations
- **Bar Chart:** Year-wise comparison of Net Income and Total Revenue from FY16 to FY22.
- **KPI Cards:** Instant insights into Net Income, Total Revenue, and Operating Income.


### 🛠️ Tools and Technologies Used

- **Power BI:** For designing and developing the interactive dashboard.
- **DAX (Data Analysis Expressions):** To calculate key metrics and perform advanced data analysis.
- **Data Sources:** Processed financial data in Excel format.

### 📊 Dashboard Visualizations

The dashboard includes:
- **KPI Tiles:** Overview of Net Income, Total Revenue, and Operating Income.
- **Bar Chart:** Trend analysis of Net Income and Total Revenue across multiple years.
- **Matrix Table:** Detailed comparison of income statement components for FY21 and FY22.

### 📈 Project Learnings

This project highlights:
- The importance of visualizing financial data for better decision-making.
- Advanced Power BI features, including calculated measures, KPI tiles, and interactive charts.
- Effective financial data modeling and DAX calculations.

### 📂 How to Use the Dashboard

#### 1. Clone the Repository:
```bash
git clone https://github.com/your-username/income-statement-dashboard.git
```
#### 2. Open in Power BI Desktop:
Load the `.pbix` file into Power BI Desktop.

#### 3. Interact with the Dashboard:
- Use slicers and filters to analyze financial performance for specific years or components.
- Drill down into specific metrics for a detailed analysis.

### 📊 Dashboard Preview
![Income Statement Dashboard Preview](https://github.com/JanviDhonde/Powerbi-IncomeStatement-Dashboard/blob/main/Income%20Statement%20Dashboard.png)

### 📊 Key DAX Measures

#### Gross Margin
```DAX
GrossMargin = [TotalRevenue] - [TotalCostOfRevenue]
```

#### Net Income
```DAX
NetIncome = [IncomeBeforeTaxes] - [ProvisionForIncomeTaxes]
```

### 🌟 Why This Project Matters

This dashboard transforms raw financial data into actionable insights, enabling stakeholders to:

- Identify revenue growth trends and cost control opportunities.
- Make informed financial decisions to drive business success.
- Gain a clear understanding of the company's financial health.

### ⭐ Feedback

If you found this project helpful, consider ⭐ this repository and sharing your feedback! 😊
