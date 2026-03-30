# Banking-Data-Analytics-Transaction-Insights

## Overview
This project is a comprehensive banking analytics dashboard built with Power BI. It provides visual insights into banking operations including deposits, loans, and client relationships.

## Project Structure

```
Banking Analysis/
├── Banking/
│   ├── BG/                      # Background design files
│   │   ├── Demo Design/        # Initial design concepts
│   │   ├── New Design/         # Updated dashboard designs
│   │   └── Old Design/         # Previous design iterations
│   ├── datasets/               # Raw data files for analysis
│   │   ├── banking-clients.csv
│   │   ├── banking-realtionships.csv
│   │   ├── gender.csv
│   │   └── investment-advisiors.csv
│   ├── Banking Dashboard (2025).pbix  # Current Power BI report
│   ├── Banking Dashboard.pbix         # Original Power BI report
│   └── Banking.csv             # Main banking dataset
├── BankEDA (Version 1).ipynb   # Exploratory Data Analysis - Version 1
├── BankEDA (Version 2).ipynb   # Exploratory Data Analysis - Version 2
└── Banking.csv                 # Root level dataset
```

## Features

### Dashboard Pages
- **Home Page**: Overview of key banking metrics and KPIs
- **Deposit Analysis**: Detailed breakdown of customer deposits
- **Loan Analysis**: Comprehensive loan portfolio visualization
- **Summary**: Executive summary with key insights
- **Drill Through**: Detailed transaction-level analysis

### Data Sources
- Client information and demographics
- Banking relationships
- Gender distribution data
- Investment advisor information
- Transaction and account data

## Getting Started

### Prerequisites
- Microsoft Power BI Desktop
- Python 3.x (for Jupyter notebook analysis)
- CSV data files included in the `datasets` folder

### How to Use

1. **Open the Dashboard**
   - Open `Banking/Banking Dashboard (2025).pbix` in Power BI Desktop
   - Refresh data connections if needed

2. **Explore the Data**
   - Navigate through different pages using the menu
   - Use filters to customize your view
   - Click on visualizations for drill-down analysis

3. **Run Data Analysis**
   - Open Jupyter notebook files for detailed EDA
   - Execute cells to reproduce analysis

## Files Description

- **`.pbix` files**: Power BI report files containing interactive dashboards
- **`.ipynb` files**: Jupyter notebooks with exploratory data analysis
- **`.csv` files**: Raw and processed datasets
- **`.png` files**: Dashboard design mockups and screenshots
- **`.pptx` / `.docx`**: Presentation and documentation files

## Dashboard Capabilities

Think of this dashboard like a school's main office:
- **Home Page** = Principal's overview board showing overall school performance
- **Deposit Analysis** = Student attendance records tracking who's present and patterns
- **Loan Analysis** = Academic performance tracking which students need extra help
- **Summary** = Report card showing key metrics at a glance
- **Drill Through** = Individual student files with detailed records

## Team Collaboration
This was developed as a collaborative college group project with team members working on different aspects including data analysis, visualization design, and business intelligence.

## Next Steps
- Regular data updates from banking systems
- Continuous improvement of visualizations
- Adding new metrics based on business requirements

---
*Last Updated: March 2026*
