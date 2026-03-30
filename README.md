# Banking-Data-Analytics-Transaction-Insights

## 📋 Table of Contents
- [Overview](#overview)
- [What This Project Does](#what-this-project-does)
- [Project Structure](#project-structure)
- [Dashboard Features](#dashboard-features)
- [Data Files Explained](#data-files-explained)
- [Technical Details](#technical-details)
- [How to Use Everything](#how-to-use-everything)
- [Learning Outcomes](#learning-outcomes)

---

## Overview
This is a complete banking analytics system that turns raw banking data into easy-to-understand visual reports. Think of it as a "control center" for a bank - just like how a school office tracks student information, attendance, and performance, this system helps bank managers see what's happening with money, loans, and customers all in one place.

Built as a college capstone project, this system demonstrates real-world business intelligence skills using actual banking data.

---

## What This Project Does

### The Main Goal
Helps bank managers answer important questions like:
- How much money do customers have in their accounts?
- Who is taking out loans and for what purpose?
- Are there patterns in how people use banking services?
- Which products are most popular?
- Where should we focus our attention?

### Real-World Application
Just like a school principal uses data to improve student performance, bank managers use this dashboard to:
- Spot trends before they become problems
- Make decisions based on facts, not guesses
- Track progress toward goals
- Identify opportunities to serve customers better

---

## Project Structure

```
Banking Analysis/
│
├── Banking/                          # Main project folder
│   │
│   ├── BG/                          # Background research and designs
│   │   ├── Demo Design/            # First draft designs (practice versions)
│   │   │   ├── Deposit Analysis.png
│   │   │   ├── Home Page (with icons).png
│   │   │   ├── Home Page (without icons).png
│   │   │   ├── Loan Analysis 2.png
│   │   │   └── Loan Analysis.png
│   │   │
│   │   ├── New Design/             # Final approved designs
│   │   │   ├── Deposit Analysis.png
│   │   │   ├── Drill Through.png
│   │   │   ├── Drill Through1.png
│   │   │   ├── Home.png
│   │   │   ├── Loan Analysis.png
│   │   │   └── Summary.png
│   │   │
│   │   ├── Old Design/             # Earlier versions (for comparison)
│   │   │   ├── Deposit Anlysis.png
│   │   │   ├── Drill Through .png
│   │   │   ├── Drill Through.png
│   │   │   ├── Home.png
│   │   │   ├── Loan Anlysis.png
│   │   │   └── Summary.png
│   │   │
│   │   └── Designs.pptx            # Design presentation slides
│   │
│   ├── datasets/                   # Raw data files (the "ingredients")
│   │   ├── banking-clients.csv     # Customer information
│   │   ├── banking-realtionships.csv  # How customers are connected to the bank
│   │   ├── gender.csv              # Gender distribution data
│   │   └── investment-advisiors.csv # Financial advisor assignments
│   │
│   ├── Banking Dashboard (2025).pbix   # Latest Power BI report file ⭐
│   ├── Banking Dashboard.pbix          # Original Power BI report
│   ├── Banking Report.docx             # Written report document
│   ├── Banking.csv                     # Complete banking dataset
│   ├── Banking.pptx                    # Project presentation
│   └── clients.csv                     # Client master list
│
├── BankEDA (Version 1).ipynb      # Data exploration notebook - First version
├── BankEDA (Version 2).ipynb      # Data exploration notebook - Improved version
└── Banking.csv                    # Copy of main data at root level
```

---

## Dashboard Features

### 1. **Home Page** - The "Big Picture" View
**What it shows:** All the important numbers at a glance
**Like in school:** The bulletin board in the main hallway showing overall school stats
**Includes:**
- Total deposits across all accounts
- Total loans issued
- Number of active customers
- Key performance indicators (KPIs)
- Quick trend indicators (going up or down?)

### 2. **Deposit Analysis** - Tracking Customer Savings
**What it shows:** Where customers keep their money
**Like in school:** Tracking which students have perfect attendance and patterns of absence
**Includes:**
- Deposit amounts by account type
- Trends over time (are deposits growing?)
- Comparison between different customer groups
- Geographic distribution of deposits
- Average deposit sizes

### 3. **Loan Analysis** - Understanding Borrowing Patterns
**What it shows:** Who's borrowing money and why
**Like in school:** Identifying students who need extra tutoring or advanced classes
**Includes:**
- Loan types (personal, business, mortgage, etc.)
- Loan amounts and approval rates
- Default rates (who's not paying back?)
- Interest rate analysis
- Loan purpose breakdown

### 4. **Summary Page** - Executive Overview
**What it shows:** The "report card" for the entire bank
**Like in school:** End-of-term report cards with grades and teacher comments
**Includes:**
- Top performers and underperformers
- Month-over-month changes
- Goals vs. actual results
- Action items and recommendations

### 5. **Drill Through Pages** - Deep Dive Details
**What it shows:** Individual transaction-level details
**Like in school:** Looking at one specific student's complete file - every test score, every absence
**Includes:**
- Individual customer records
- Transaction histories
- Account-by-account breakdowns
- Filterable by any criteria

---

## Data Files Explained

### Main Dataset: `Banking.csv`
The "master spreadsheet" containing everything about the bank's operations.

### Supporting Datasets:

**`banking-clients.csv`**
- Customer names and IDs
- Contact information
- When they became customers
- What products they use

**`banking-realtionships.csv`** *(note: "relationships" is misspelled in original)*
- How customers are connected to the bank
- Which branch they belong to
- Their assigned banker
- Service tier (premium, standard, etc.)

**`gender.csv`**
- Male/female customer breakdown
- Used for diversity analysis
- Helps identify market segments

**`investment-advisors.csv`** *(note: "advisors" is misspelled in original)*
- Which customers have financial advisors
- Advisor assignments and specialties
- Investment portfolio information

---

## Technical Details

### Tools Used
- **Power BI Desktop**: Main dashboard creation tool (like PowerPoint but for data)
- **Python with Jupyter Notebooks**: For cleaning and exploring data before visualization
- **CSV Files**: Universal data format that works with any spreadsheet program

### Skills Demonstrated
1. **Data Cleaning**: Taking messy real-world data and making it usable
2. **Data Modeling**: Connecting different tables together logically
3. **Visualization Design**: Choosing the right chart for each type of data
4. **Business Intelligence**: Asking the right questions to solve business problems
5. **Dashboard UX**: Making it easy for non-technical users to find what they need

### Design Evolution
The project shows three design iterations:
1. **Old Design**: First attempt (basic, functional)
2. **Demo Design**: Practice version (testing new ideas)
3. **New Design**: Final version (polished, user-tested)

This shows the ability to iterate and improve based on feedback - a crucial professional skill.

---

## How to Use Everything

### Step 1: Open the Dashboard
```
1. Install Power BI Desktop (free from Microsoft)
2. Open "Banking/Banking Dashboard (2025).pbix"
3. Click "Refresh" to load the latest data
4. Start exploring!
```

### Step 2: Navigate the Dashboard
```
- Use the navigation menu (usually on the left or top)
- Click on any chart to see more details
- Use slicers (filters) to focus on specific time periods or segments
- Right-click on visuals for additional options
```

### Step 3: Run Your Own Analysis
```
1. Install Python and Jupyter Notebook
2. Open "BankEDA (Version 2).ipynb"
3. Run cells one by one to see the analysis process
4. Modify code to explore your own questions
```

### Step 4: Review Documentation
```
- Read "Banking Report.docx" for detailed written analysis
- View "Banking.pptx" for presentation slides
- Check "BG/Designs.pptx" for design thinking process
```

---


## Learning Outcomes

### Technical Skills Gained
✅ **Data Analysis**: Working with real, messy data (not textbook examples)  
✅ **Power BI**: Creating interactive dashboards from scratch  
✅ **Python Programming**: Using pandas, matplotlib, and seaborn  
✅ **SQL Concepts**: Even without a database, understanding relationships  
✅ **Statistics**: Calculating averages, trends, and correlations  

### Business Skills Gained
✅ **Critical Thinking**: Asking "why" behind every number  
✅ **Communication**: Explaining technical findings to non-technical audiences  
✅ **Problem Solving**: Fixing data quality issues creatively  
✅ **Time Management**: Balancing multiple project components  
✅ **Presentation Skills**: Defending design choices to instructors  

### Career Preparation
This project demonstrates job-ready skills for positions like:
- Business Analyst
- Data Analyst
- Business Intelligence Developer
- Financial Analyst
- Operations Research Analyst

---

## Common Questions Answered

### "Why are there so many versions of the same files?"
Real projects evolve! The old designs show growth and improvement. Employers want to see that you can iterate based on feedback, not just create one perfect thing on the first try.

### "The data has typos - why not fix them?"
That's real-world data for you! Part of the learning experience is dealing with imperfect inputs. In the workplace, you'll spend 80% of your time cleaning data and only 20% analyzing it.

### "Can I add this to my portfolio?"
Absolutely! Just make sure you understand every part of it so you can explain your choices during interviews.

---

## Tips for Students Starting Similar Projects

1. **Start with the data first** - You can't build anything until you know what you're working with
2. **Sketch your designs on paper** - Don't jump straight into Power BI
3. **Test with real users** - Have classmates try your dashboard and tell you what's confusing
4. **Document everything** - Future you will thank present you for leaving notes
5. **Version control matters** - Name files clearly (v1, v2, final, FINAL_final)
6. **Embrace the messiness** - Real data is never clean, and that's okay

---

## Next Steps for Improvement

If you want to take this project further:

1. **Add Predictive Analytics**: Use machine learning to forecast future trends
2. **Create Automated Reports**: Set up email subscriptions for stakeholders
3. **Build a Mobile Version**: Optimize for phones and tablets
4. **Add More Data Sources**: Connect to live banking APIs
5. **Implement Security**: Add user authentication and role-based access
6. **Create Alerts**: Notify managers when metrics hit certain thresholds

---

## Troubleshooting Common Issues

**Problem**: Power BI says "Cannot connect to data source"  
**Solution**: Make sure all CSV files are in the correct folders. You may need to update file paths.

**Problem**: Charts look wrong or empty  
**Solution**: Refresh the data in Power BI (click the Refresh button)

**Problem**: Jupyter notebook won't run  
**Solution**: Install required packages: `pip install pandas matplotlib seaborn jupyter`

**Problem**: File sizes are too large  
**Solution**: Some images are high-resolution. Consider compressing PNG files.

---

## Resources for Learning More

- **Power BI**: Microsoft Learn has free courses
- **Python for Data Analysis**: Look up "Python for Everybody" course
- **Dashboard Design**: Read "Storytelling with Data" by Cole Nussbaumer Knaflic
- **Portfolio Building**: Check out GitHub Student Developer Pack resources

---

*Last Updated: March 2026*  















