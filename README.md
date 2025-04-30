# Excel Project - Employee Data Analysis

## Overview
This Excel-based project analyzes employee data from two regions (New Zealand and India) to provide insights into workforce demographics, compensation, and performance metrics. The workbook contains multiple sheets for data storage, analysis, and visualization.

## File Structure
- **Business Questions**: Lists the key analysis objectives
- **NZ Data**: Employee records for New Zealand staff
- **India Staff**: Employee records for Indian staff
- **Total Staff**: Consolidated data with calculated tenure and bonuses
- **Analysis**: Key metrics and information lookup tools
- **Male vs Female Comparison**: Gender-based comparisons
- **Data Visualization**: Charts and regional scorecards

## Key Features

### Data Analysis
- Employee count and demographics
- Salary and age statistics (average, median)
- Gender comparisons
- Departmental breakdowns
- Regional comparisons (NZ vs India)

### Calculations
- **Tenure**: Calculated as `(TODAY()-JoinDate)/365`
- **Annual Bonus**: 
  - 3% of salary for tenure >3 years
  - 2% of salary for tenure ≤3 years
  - Rounded up to nearest whole number

### Tools
- Employee lookup functions (VLOOKUP, XLOOKUP)
- Department-specific filtering
- Rating-to-numeric conversion for analysis

## How to Use
1. View the "Business Questions" sheet to understand analysis objectives
2. Explore raw data in "NZ Data" and "India Staff" sheets
3. See calculated metrics in "Analysis" and visualization sheets
4. Use filters and lookups to find specific employee information

## Technical Notes
- Formulas use Excel functions including:
  - `COUNTA`, `COUNTIF`, `AVERAGE`, `MEDIAN`
  - `XLOOKUP`, `VLOOKUP`
  - `ROUNDUP`, `IF` statements
  - Date calculations with `TODAY()`

## Visualizations
- Salary spread analysis
- Salary vs. rating correlation
- Company growth over time
- Regional scorecards comparing NZ and India metrics

## Maintenance
To update the analysis:
1. Add new employee records to respective regional sheets
2. Ensure formulas in "Total Staff" cover new rows
3. Refresh any pivot tables or charts
