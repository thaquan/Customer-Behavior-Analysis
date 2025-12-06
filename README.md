# Customer Behavior Analysis

A comprehensive data analytics project analyzing customer shopping behavior patterns using Python, SQL Server, and Power BI to derive actionable business insights.

## 📋 Overview

This project analyzes customer shopping behavior data to uncover patterns in purchasing habits, demographics, and preferences. The analysis combines exploratory data analysis, data cleaning, SQL queries, and interactive visualizations to help businesses understand their customer base and make data-driven decisions.

## 📊 Dataset

The dataset contains **3,900 customer records** with 18 attributes including:

- **Customer Demographics**: Customer ID, Age, Gender, Location
- **Purchase Information**: Item Purchased, Category, Purchase Amount (USD), Size, Color, Season
- **Customer Behavior**: Review Rating, Previous Purchases, Frequency of Purchases
- **Transaction Details**: Payment Method, Shipping Type, Discount Applied, Promo Code Used, Subscription Status

**Key Statistics:**
- Age range: 18-70 years
- Purchase amounts: $20-$100 USD
- Categories: Clothing, Footwear, Accessories, Outerwear
- 50 different locations across the US

## 🛠️ Tools & Technologies

- **Python** - Data loading, cleaning, and exploratory data analysis
  - pandas - Data manipulation
  - Jupyter Notebook - Interactive analysis environment
- **SQL Server** - Database queries and data analysis
- **Power BI** - Interactive dashboard creation
- **Gamma** - Professional report and PDF generation

## 🔍 Project Steps

### 1. Data Loading
- Imported CSV dataset into Python using pandas
- Initial data exploration with `. head()`, `.info()`, and `. describe()`

### 2.  Exploratory Data Analysis (EDA)
- Analyzed data structure and distributions
- Identified key patterns in customer demographics
- Examined purchase behavior across different segments

### 3. Data Cleaning
- **Handled Missing Values**: Filled 37 missing values in Review Rating using median imputation by category
- **Column Standardization**: Converted column names to lowercase and replaced spaces with underscores
- **Data Transformation**: 
  - Created age groups (Young Adult, Adult, Middle-aged, Senior) using quartile-based segmentation
  - Mapped purchase frequency to numerical days for better analysis

### 4. SQL Analysis
- Loaded cleaned data into SQL Server
- Executed analytical queries to extract insights
- Performed aggregations and trend analysis

### 5. Power BI Dashboard
- Connected Power BI to SQL Server database
- Built interactive visualizations
- Created comprehensive dashboard for stakeholder presentation

### 6. Report Generation
- Compiled findings and insights
- Created professional report using Gamma
- Exported final deliverable as PDF

## 📈 Dashboard

The Power BI dashboard (`Customer_Behavior. pbix`) provides interactive visualizations including:
- Customer demographics breakdown
- Purchase patterns by category and season
- Revenue analysis by location and age group
- Payment method preferences
- Subscription and discount usage trends

## 📄 Results

The analysis reveals comprehensive insights into customer shopping behavior, documented in:
- **Business Problem Document. pdf** - Problem statement and objectives
- **Customer Shopping Behavior Analysis.pdf** - Detailed analysis report
- **Customer-Shopping-Behavior-Analysis.pdf** - Final comprehensive report

## 🚀 How to Run

### Prerequisites
- Python 3.x
- SQL Server
- Power BI Desktop
- Jupyter Notebook

### Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/thaquan/Customer-Behavior-Analysis. git
   cd Customer-Behavior-Analysis
   ```

2. **Run Python Analysis**
   ```bash
   jupyter notebook customer_shopping_analysis.ipynb
   ```
   - Execute cells sequentially to load, clean, and analyze the data

3. **SQL Server Setup**
   - Import the cleaned dataset into SQL Server
   - Run queries from `customer_behavior_queries.sql`

4. **View Power BI Dashboard**
   - Open `Customer_Behavior.pbix` in Power BI Desktop
   - Refresh data connections if needed
   - Explore interactive visualizations

5. **Review Reports**
   - Check the PDF reports for detailed findings and insights

## 📁 Project Structure

```
Customer-Behavior-Analysis/
│
├── customer_shopping_behavior. csv          # Raw dataset
├── customer_shopping_analysis.ipynb        # Python analysis notebook
├── customer_behavior_queries.sql           # SQL queries
├── Customer_Behavior.pbix                  # Power BI dashboard
├── Business Problem Document.pdf           # Project objectives
├── Customer Shopping Behavior Analysis.pdf # Analysis report
└── Customer-Shopping-Behavior-Analysis. pdf # Final report
```

## 💡 Key Insights

- Detailed customer segmentation by age groups
- Purchase frequency patterns mapped to business cycles
- Category-wise performance analysis
- Location-based purchasing trends

## 👤 Author

**thaquan**

---

*This project demonstrates end-to-end data analytics workflow from raw data to actionable insights.*
