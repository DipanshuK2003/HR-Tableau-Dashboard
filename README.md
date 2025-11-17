# HR Analytics Dashboard

## Project Overview
An interactive Tableau dashboard designed to help HR managers analyze workforce data through comprehensive summary views and detailed employee records. This project addresses key HR needs including workforce demographics, income analysis, and employee lifecycle tracking.

## Live Interactive Dashboard
**[View the full interactive dashboard on Tableau Public](https://public.tableau.com/app/profile/dipanshu.kumar1559/viz/HumanResourcesDashboard_17633784084680/HRSummary)**

*Experience the complete functionality with filters, tooltips, and dynamic interactions.*

## Dashboard Preview

### Summary View
<img width="800" alt="charts" src="https://github.com/DipanshuK2003/HR-Tableau-Dashboard/blob/main/Assets/Dashboard%20stills/HR%20%7C%20Summary.png">

<img width="800" alt="charts" src="https://github.com/DipanshuK2003/HR-Tableau-Dashboard/blob/main/Assets/Dashboard%20stills/HR%20%7C%20Details.png">

Comprehensive summary view showing Overview, Demographics, and Income Analysis sections

## Business Objectives Met

### Overview Section
- **Employee Lifecycle Tracking**: Total hired, active, and terminated employees
- **Trend Analysis**: Hiring and termination patterns over years (2015-2024)
- **Organizational Structure**: Employee distribution across departments and job titles
- **Geographic Distribution**: HQ vs branch comparison and state/city breakdowns

### Demographics Section  
- **Diversity Metrics**: Gender ratio visualization
- **Workforce Composition**: Age group distribution and education level analysis
- **Performance Insights**: Correlation between education and performance ratings

### Income Analysis Section
- **Pay Equity**: Salary comparison across education levels by gender
- **Compensation Trends**: Age vs salary correlation within departments

### Employee Records
- **Detailed View**: Comprehensive employee listing with all attributes
- **Advanced Filtering**: Multi-column filtering for deep-dive analysis

## Technical Implementation

### Data Generation
- **Records**: 8,950 synthetic employee records
- **Tools**: Python Faker library, ChatGPT
- **Timeframe**: 2015-2024 employee data
- **Attributes**: 15+ fields including demographics, compensation, and employment history

### Key Features
- **Dynamic Filtering**: Interactive cross-filtering across all visualizations
- **Drill-down Capability**: From summary metrics to individual employee records
- **Responsive Design**: Optimized for different screen sizes

## Key Insights Discovered

### Workforce Trends
- Total number of active employees: 7,984, hired employees: 8,950 & terminated employees: 966.
- Operations and sales department leads in number of employees while HR department has the least number of employees.
- New York state have roughly 70% of the employees alone.

### Demographic Patterns
- 46% of employees are female.
- Most employees fall in the age bracket of 35-44.
- Most employees have done bachelors.

### Compensation Analysis
- Pay gap between genders is highest among PhDs and least among high school graduates.
- Finance and IT manager earns the most while also having the highest average age.

## Project Files

| File | Description |
|------|-------------|
| `HR Dashboard New.twbx` | Complete Tableau packaged workbook |
| `Dataset/dataset.csv` | Generated dataset (8,950 records) |
| `Assets/` | Dashboard screenshots and logos |

## How to Use

1. **Interactive Exploration**: Click the Tableau Public link above for full functionality
2. **Local Analysis**: Download the `.twbx` file to explore in Tableau Desktop
3. **Data Verification**: Review the generated dataset and Python script

## Connect
[[LinkedIn](https://www.linkedin.com/in/dipanshu-kumar-61a21322a/)]

---
*Dataset generated synthetically for demonstration purposes. Any resemblance to real individuals or organizations is coincidental.*
