# Mobile-Sale-Dashboard (Interactive Mobile sale Dashboard creation using Power BI)
## Project Object:
Build a dashboard to evaluate the sales performance of mobile phone products by brand, time, city, payment method, etc. Also track this month’s sales performance in real time and evaluate the growth compared to the previous year.

## About data:
The dataset includes information on sales revenue, time, product prices, and payment methods for mobile phone purchases across cities in India.The purpose of the dashboard is to analyze sales performance, evaluate product performance, monitor business efficiency over time, and compare revenue growth against the same period last year.
# Process:
## 1. Data prepation
- Collected advertising performance data from Kaggle 
- Cleaned and transformed datasets by handling missing values, standardizing date and currency formats.
- Created a Calendar table and reformatted date columns to enable accurate time-based analysis and filtering.
## 2. Data modeling 
- Build a Star Schema including tables
- Create DAX measures to calculate the main KPI:
- Total sale = sum([Sale])
- Total quantity = sum([quantity])
- Transaction = count([Transaction])
- Averge price = averge([price])
## 3. Visualization 
- Design 3 separate dashboard pages: Mobile Sale Dashboard, MTD Report & Last same period year
- Mobile Sale Dashboard:  evaluate the sales performance of mobile phone by brand, time, city, payment method, etc
- MTD Report: track this month’s sales performance in real time
- Last same period year: compare revenue growth against the same period last year.
- Use navigator buttons to smoothly switch pages.
## 4. Insight 
- Sales are highest in metros (New Delhi, Mumbai, Bangalore).
- Apple and Samsung are the leading brands.
- March–May is the peak season for sales.
- Customers have a wide range of payment methods.
- Satisfaction is high (~65% Good).
Sales are high early in the week, low in the middle of the week.
# Dashboard 
![Dashboard](https://github.com/user-attachments/assets/ce50575d-eab0-44cc-b7ea-298af01c0706) 

![MTD Report](https://github.com/user-attachments/assets/58600e30-f5c3-40e8-af5b-1a8640566ca2) ![Same Period Last Year report](https://github.com/user-attachments/assets/ef15fef6-18d6-47e9-a911-7ea38247c21f)








.
