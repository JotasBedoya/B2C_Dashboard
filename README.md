# Call Center KPI Dashboard – Operational Analytics (Power BI)

## Overview
This project delivers a full operational analytics dashboard for a Call Center environment. Before this solution, leadership teams had no centralized, real-time view of call performance metrics. Data was scattered across systems, decisions were based on intuition, and critical operational information, such as peak-hour demand and service levels, was not tracked or understood.

The dashboard consolidates call-center KPIs into a single analytics product that supports decision-making for Operations, Workforce Management, Customer Experience, and Leadership teams.

## Business Problem
Prior to this dashboard:
- No visibility into real-time daily, weekly, and monthly call behavior
- No understanding of peak hours to assign agents efficiently
- Data loss due to a lack of a reporting structure
- SLA performance and customer experience metrics were not measured or monitored
- Leadership could not quantify abandoned calls, ghost calls, callback quality, or segmentation by brand and skill

This resulted in:
- Staffing misalignment during high-volume periods
- Untracked losses in customer experience
- Slow decision-making due to manual reporting

## Solution – What the Dashboard Delivers
The dashboard provides a multi-layer analytics view:

### Page 1 – Monthly / Weekly / Daily Trends
- Volume of calls by month, week, and day
- Quarter-hour heatmaps showing peak demand
- Brand segmentation (DEWALT, BLACK+DECKER, CRAFTSMAN, etc.)
- Insights used to adjust staffing schedules to match demand

### Page 2 – Operational Performance
- Service Level (SLA)
- Average Speed of Answer (ASA)
- Abandon Rate
- Average Handle Time (AHT)
- Callback Service Level
- Callback Connection Rate

### Page 3 – Customer Experience
- Customer Satisfaction (CSAT)
- Net Promoter Score (NPS)
- Callback time performance
- Trend analysis by product issue type

### Page 4 – Geographic Intelligence
- Call volume by U.S. State and global country
- Brand penetration by region
- Used to understand where demand originates and guide commercial strategy

### Page 5 – Dispositions & Issue Classification
- Breakdown of caller reasons (warranty issue, product information, order status, ghost call, licensee transfer, etc.)
- Insight enabling better routing and workflow automation

## KPIs Included
| KPI | Description |
|-----|-------------|
| SLA | Percentage of calls answered within target |
| ASA | Average wait time before connection |
| AHT | Average call handling time |
| Abandon Rate | % of customers who hang up before being attended |
| Ghost Calls | Calls where nobody is on the line |
| Callback SLA | Target callbacks met |
| Customer Satisfaction | Customer rating after interaction |
| Net Promoter Score | Likelihood to recommend |

## Business Impact
This dashboard enabled:
- Realignment of staffing based on hourly demand patterns
- Faster executive reporting (reduced manual reporting time)
- Ability to identify issue categories causing overload
- Visibility of performance by brand, region, product category, and skill

Examples of measurable impact:
- Reduction of decision-making time
- Identification of >10% of calls as ghost calls (lost CX opportunity)
- Workforce optimization based on quarter-hour peak analysis

## Tools & Stack
- Power BI Desktop
- DAX calculations & measures
- Data Model (Star Schema)
- Power Query for ETL
- Optional SQL-based cleaning

## Repository Structure
