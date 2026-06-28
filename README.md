# Quarterly Team Performance Dashboard - Nexus Tech

This project presents a Quarterly Team Performance Management Dashboard for a fictitious B2B company that sells computer hardware. The analysis is based on sales pipeline data covering accounts, products, sales teams, and sales opportunities, and it was built to help management monitor team performance across quarters and managers.

The dashboard is designed to show how each sales team is performing compared with the rest, whether any sales agents are lagging behind, how results change quarter over quarter, and which  sales agents have stronger win rates. It combines summary KPIs, agent-level performance tables, and detailed performance charts to support faster performance review and better decision-making.

# The Dataset
This project uses CRM records exported from MavenTech, covering the period from October 2016 to December 2017. The dataset includes sales opportunities and related attributes such as product type, account details, and final deal outcome. Source: https://mavenanalytics.io/data-playground/crm-sales-opportunities. All files used and created for this analysis are stored in the CRM+Sales+Opportunities folder in this repository.

## The Dashboard 

<img width="1718" height="966" alt="NT_POWER BI_All" src="https://github.com/user-attachments/assets/7d2b01df-2101-4d53-8abc-dbaf0b296082" />

## What the dashboard shows

The top section of this interactive dashboard highlights key KPIs for the selected manager and quarter, including previous quarter revenue, open deals, and whether the agent is on track or lagging. Upper section also includes a manager trend visual that shows total sales revenue by manager, making it easier to compare performance across leaders and spot differences in revenue contribution. The central visuals show product sales performance by agent, with a matrix of sales activity across hardware product groups. The lower section breaks down individual agent performance through metrics such as won deals, win rate, average sales cycle, total revenue, and lost deals, which makes it easier to identify top performers and weaker areas.

## Main business questions

 This interactive dashboard was built to answer the following questions:
 
- How is each sales team performing compared with the rest?
- Are any sales agents lagging behind?
- Does any sales agent have better win rates?
- Which managers contribute the most revenue?
- Which manager leads the strongest team overall?
- Which products are sold the most?

# Data Model

<img width="1492" height="1062" alt="Nexus Tech_Data Model" src="https://github.com/user-attachments/assets/7b548033-49cf-44e0-b1bf-64318c5bbed8" />

The dataset required only minimal cleaning, and the modeling process was straightforward. The main focus was creating a relationship between the Date and Sales tables to connect both engagement and closure dates. All KPI visuals on the dashboard were created using DAX measures.

# Filters used

The dashboard includes two main filters at the top right: Team Manager and Quarter.

 - The Team Manager filter lets the user switch between 6 team managers such as Rocco Neubert and Celia Rouche, allowing comoplete review of team performance.

- The Quarter filter lets the user view one quarter at a time or all quarters together, which supports comparison across reporting periods and quarter-over-quarter trends.

These filters update all visuals on the page, so the dashboard can be explored from different angles without changing the layout.

<img width="1735" height="972" alt="NT_POWER BI_Melvin Marxen" src="https://github.com/user-attachments/assets/b7f2d8d6-1ec6-4a1f-bc08-8778b3ef3be2" />


Additional images can be found in the Images_Sales Performance folder of this repository.

<img width="1732" height="977" alt="NT_POWER BI_CELIA ROUCHE" src="https://github.com/user-attachments/assets/2d2d99eb-899d-4068-943b-2d28db885278" />



# Key findings

 - Melvin Marxen’s team generated the highest yearly  total revenue, while Darcel Schecht recorded the most won deals and the highest revenue overall, but also the most lost deals.

- Seven agents are currently lagging behind in performance, including Boris Faz, Rosalina Dieter, and Rosie Papadoulus.

- Willburn Ferren, from Cara Losch’s team, achieved the highest winning rate.

- Vicki Laflamme, on Celia Rousche’s team, closed the most deals but did not generate the highest revenue among all teams.

# Key dashboard elements

- KPI cards summarize the current quarter’s main performance indicators, such as revenue, open deals, and lagging/on-track status .

- Agent performance matrix shows sales activity across product categories for each agent.

- Sector treemap highlights which product sectors generate the most revenue.

- Manager trend visual compares total sales revenue across managers.

- Agent detail charts show won deals, win rate, average sales cycle, total revenue, and lost deals for deeper performance analysis .

# Business value

This dashboard helps management review team performance, compare managers, and identify where sales activity is strong or weak. It also supports coaching by showing which agents are lagging, which ones close deals efficiently, and which product types are driving revenue. Overall, it turns raw B2B pipeline data into a practical performance management tool for quarterly review and action planning.

