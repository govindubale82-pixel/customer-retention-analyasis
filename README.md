I'm waiting for your confirmation to update the README file. Please accept or reject this action to continue.# Customer Retention Analysis Dashboard

Customer Retention Analysis Dashboard using Excel and Power BI to analyze customer loyalty, churn rate, and retention trends

## 📋 Project Overview

Customer Retention Analysis is a comprehensive data analytics project designed to help businesses understand customer loyalty, retention trends, and churn behavior. This project leverages Excel for data preparation and Power BI for interactive visualization and insights. By analyzing customer data across multiple dimensions, businesses can identify patterns, predict churn risks, and develop targeted retention strategies.

## 🎯 Objectives

- Analyze customer retention rate and identify retention patterns
- Analyze customer churn rate and understand churn drivers
- Identify customer trends by region and market segments
- Track customer engagement metrics over time
- Improve customer engagement strategies based on data insights
- Support decision-making for customer retention programs

## 📊 Key Performance Indicators (KPIs)

| KPI | Description |
|-----|-------------|
| **Total Customers** | Total number of customers in the database |
| **Active Customers** | Number of customers currently active |
| **Churned Customers** | Number of customers who have left/churned |
| **Retention Rate (%)** | Percentage of customers retained over a period |
| **Churn Rate (%)** | Percentage of customers lost over a period |
| **Average Customer Lifetime** | Average tenure of customers |

## 🛠️ Tools Used

- **Microsoft Excel** - Data cleaning, preprocessing, and preparation
- **Power BI** - Interactive dashboards, visualizations, and business intelligence
- **GitHub** - Version control and project documentation

## 📈 Dataset Fields

| Field | Description |
|-------|-------------|
| **Customer ID** | Unique identifier for each customer |
| **Customer Name** | Name of the customer |
| **Region** | Geographic region of the customer |
| **Join Date** | Date when customer joined |
| **Last Purchase Date** | Date of the most recent purchase |
| **Purchase Frequency** | Number of purchases made |
| **Total Spending** | Total amount spent by customer |
| **Status** | Current status (Active/Churned) |
| **Tenure Days** | Number of days as a customer |

## 🎨 Dashboard Features

### Main Dashboard Components

1. **Customer Retention Rate Card**
   - Displays overall retention percentage
   - Shows comparison with previous period
   - Color-coded for quick insights

2. **Customer Churn Rate Card**
   - Displays churn percentage
   - Tracks churn trends
   - Alerts on high churn periods

3. **Customers by Region**
   - Geographic distribution of customers
   - Regional retention comparison
   - Identifies high-performing regions

4. **Monthly Retention Trend**
   - Line chart showing retention trends over time
   - Helps identify seasonal patterns
   - Supports forecasting

5. **Customer Status Distribution**
   - Pie chart of Active vs Churned customers
   - Visual representation of customer health
   - Breakdown by customer segments

6. **Churn Analysis by Region**
   - Regional churn comparison
   - Identifies at-risk regions
   - Supports targeted interventions

7. **Customer Engagement Metrics**
   - Purchase frequency analysis
   - Customer lifetime value distribution
   - Spending patterns

## 🚀 How to Use the Dashboard

### Accessing the Dashboard

1. Open the Power BI file in Power BI Desktop or Power BI Service
2. Connect to the Excel data source if prompted
3. Refresh data to load the latest customer information

### Interactive Features

- **Date Slicers** - Filter data by specific date ranges
- **Region Filter** - Select specific regions for analysis
- **Status Filter** - Toggle between Active and Churned customers
- **Drill-through** - Click on visualizations to see detailed customer information
- **Tooltips** - Hover over data points for additional context

### Key Analyses You Can Perform

- Compare retention rates across different regions
- Identify seasonal trends in customer churn
- Analyze spending patterns of retained vs churned customers
- Discover high-value customer segments
- Monitor key metrics in real-time

## 📋 Data Flow

```
Excel Data Source
        ↓
Data Cleaning & Preparation
        ↓
Excel Processed Data
        ↓
Power BI Connection
        ↓
Data Transformation (DAX)
        ↓
Interactive Dashboard & Visualizations
```

## 💡 Expected Outcome

This dashboard enables businesses to:

- **Gain Visibility** - Understand customer retention and churn patterns across all dimensions
- **Identify Risks** - Spot at-risk customer segments early
- **Drive Actions** - Make data-driven decisions to improve retention
- **Measure Impact** - Track the effectiveness of retention programs
- **Optimize Resources** - Allocate resources to high-impact retention initiatives
- **Predict Trends** - Forecast future churn and retention patterns

## 📂 Project Structure

```
customer-retention-analyasis/
│
├── README.md                      # Project documentation
├── Data/
│   ├── raw_customer_data.xlsx     # Original customer data
│   └── processed_data.xlsx        # Cleaned and processed data
│
├── Dashboard/
│   └── Customer_Retention_Dashboard.pbix  # Power BI dashboard file
│
└── Documentation/
    └── Data Dictionary.md         # Detailed field descriptions
```

## 🔧 Setup & Installation

### Prerequisites

- Microsoft Excel 2016 or later
- Power BI Desktop (free version available at powerbi.microsoft.com)
- Sample customer data in Excel format

### Steps

1. Clone or download this repository
2. Open the Excel file and review the data structure
3. Open the Power BI file (.pbix)
4. Update data source if using different Excel file
5. Click "Refresh" to load the latest data
6. Interact with the dashboard using filters and slicers

## 📊 Key Insights

### Metrics to Monitor

- **Retention Rate Target** - Aim for 85%+ retention
- **Churn Rate Alert** - Flag if churn exceeds 15%
- **Regional Performance** - Benchmark regions against company average
- **Customer Lifetime Value** - Focus on high-value customer retention

## 🎓 Business Recommendations

Based on typical customer retention analysis:

1. **Personalized Engagement** - Increase touchpoints with high-value customers
2. **Early Warning System** - Create alerts for customers at churn risk
3. **Regional Focus** - Allocate more resources to low-retention regions
4. **Loyalty Programs** - Develop programs for long-term customer retention
5. **Feedback Loop** - Collect feedback from churned customers

## 📞 Contact & Support

- **Author** - Govind Ubale
- **Email** - govindubale82@gmail.com
- **GitHub** - [@govindubale82-pixel](https://github.com/govindubale82-pixel)

## 📄 License

This project is open source and available for educational and business use.

## 🤝 Contributing

Contributions are welcome! Feel free to:

- Report bugs or issues
- Suggest improvements to the dashboard
- Add new visualizations
- Enhance documentation

## 📝 Version History

- **v1.0** - Initial release with basic retention and churn analysis
- **v1.1** - Added regional analysis and trend forecasting

---

**Last Updated:** June 2026

For questions or feedback, please open an issue in the repository.
