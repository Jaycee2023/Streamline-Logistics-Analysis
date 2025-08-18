# Streamline-Logistics-Analysis
## An interactive dashboard that provides visibility into backlogs, delivery delays, resource allocation, and customer satisfaction. 

## Table of contents
- [project Overview](#project-overview)
- [Business Problem](business-problem)
- [Data Sources](data-sources)
- [Tools](tools)
- [Data Cleaning and Preparation](data-cleaning-and-preparation)
- [Exploratory Data Analysis](exploratory-data-analysis)
- [Results and findings](results-and-findings)

### Project Overview
####As a Data Analyst Consultant at Amdari, I worked with Streamline Logistics Solutions to "
tackle critical inefficiencies in their order fulfilment process. Using Microsoft Excel and 
Office Scripts, I built an interactive dashboard that provided visibility into backlogs, 
delivery delays, resource allocation, and customer satisfaction. My work led to improved 
operational decision-making and significant time savings in reporting.

<img width="1137" height="742" alt="image" src="https://github.com/user-attachments/assets/5950259d-6a79-4ff4-89a9-e7b66b94df94" />

### Business Problem
Streamline Logistics faced significant operational challenges impacting their service delivery
Mounting order backlogs due to inefficient routing and resource allocation
Growing customer dissatisfaction caused by delayed deliveries
Rising costs from overtime and expedited shipments
Poor visibility into real-time operations and driver performance"

### Data Sources

Logistics Deliver Data: The primary dataset used for this analysis is "Logistics_data.csv", which contains detailed information on deliveries made by the company.

### Tools

- Excel  Data cleaning and visualisation [Download here]((https://1drv.ms/x/c/273014e204d974cb/EdRAprWaKRJGor7wPtPCpC0BTnzh0S-bAlw41fDrz_vpMw?e=FjgyK5&nav=MTVfe0Y2MkVBMDBFLTcyMzMtNEU2OS05MkU0LTUyN0VGRUU2MjAzM30)
- Office Scripts (for automation)
- PivotTables, charts, and conditional formatting
- PowerPoint for presentation


### Data Cleaning and Preparation
In the initial data preparation phase, we performed the following tasks
1. Data loading and inspection
2. Handling missing values.
3. Data cleaning and formatting
4. Calculated fields: Delivery Duration, Delay Category, On-Time Status
5. Created feedback sentiment scoring and delivery zone groupings"


###Exploratory Data Analysis
Two types of EDAs were conducted:
##A. Preliminary Analysis: Given our business problem
1. How many orders are currently backlogged?
2. What is the average delay of the deliveries?
3. Which delivery zone experiences the highest average delays?
4. What is the distribution of customer feedback?
5. How many orders are 'Expediated Rules' Vs 'Custom'?

<img width="586" height="630" alt="image" src="https://github.com/user-attachments/assets/3964580d-3f96-4bb2-be62-1939b0ed104a" />

<img width="481" height="359" alt="image" src="https://github.com/user-attachments/assets/056a2c6f-f659-41f3-ae70-e8f8f4812e42" />


##B. Deep Dive Analysis: To optimise the order fulfilment process, I looked into specific areas that can offer insights for improvements
1. How does delivery correlate with customer feedback?
2. Which drivers are the most problematic in terms of delivery?
3. Which routes are the most problematic in terms of delivery?
4. Are certain vehicles associated with higher delays?
5. How do the 'Expedited Rules'perform compared to 'Customer Rules' in terms of delays?
 <img width="1266" height="631" alt="image" src="https://github.com/user-attachments/assets/34ca1bc2-d9c0-4c12-8ace-8d96772a9ce0" />
 <img width="1261" height="337" alt="image" src="https://github.com/user-attachments/assets/27655312-9b02-4f4c-aa1b-5cf6868bdd6b" />

  



### Results and Findings

📊 Visual Insights & Analysis Breakdown
🧩 Preliminary Analysis (Steps 1 & 2)

####Questions Answered:
Backlogged Orders: 767 in-progress orders
Average Delay:
Overall: 14.51 mins
Zone 1: 14.23 mins
Zone 2: 14.67 mins
Zone 3: 14.63 mins

####Highest Delay: Zone 2
Customer Feedback:
Negative: 529
Neutral: 490
Positive: 481
→ Negative feedback is slightly dominant, indicating room for improvement in customer experience.

Allocation Rules Usage:
Standard Rules: 513
Custom Rules: 509
Expedited Rules: 478
→ Majority of deliveries still follow Standard Rules, with lower use of Expedited options.

🔍 Deep Dive Analysis (Step 3)
Business Questions Explored:
📉 What’s the impact of feedback sentiment on delivery delay?
→ Negative feedback aligns with slightly lower delays (14.59 mins) compared to Positive (14.73 mins), suggesting expectations might be higher, not just delivery speed.

🚚 Which drivers are causing the most delays?
→ Top delay: Driver D86 (20.73 mins)
→ Other high-delay drivers include D66, D29, and D91.

🛣️ Which routes are most problematic?
→ Route 3 has the highest average delay (14.85 mins)
→ Route 5 is most efficient (13.69 mins)

🛵 Vehicle type & delays?
→ Bike C has the highest delay (14.81 mins)
→ Van A is most efficient (14.15 mins)

⚖️ Allocation Rules & delay impact:
Expedited Rules: 15.03 mins (highest delay)
Standard Rules: 14.23 mins
Custom Rules: 14.30 mins
→ Expedited Rules aren’t necessarily faster, suggesting a need to review urgency-based allocations.

📈 Comparative Summary Metrics

KPI	Insight
On-Time Deliveries	Only 3% – indicates a major performance issue
Backlog Rate	Ranges from 46% to 53% by route – significantly high
Most Delayed Route: Route 3
Most Delayed Driver	Varies across D8, D10, D86 depending on route/zone
Customer Satisfaction	Averages ~30% across routes – reflects delivery delays
🧮 Office Script Automations

Script Tasks Completed:
Auto-calculation of KPIs: Delivery time, delay % per driver/zone, backlog rate, etc.
Ad hoc report generation: Summary tables & conditional formatting using script
Automated refresh logic for new data entries
