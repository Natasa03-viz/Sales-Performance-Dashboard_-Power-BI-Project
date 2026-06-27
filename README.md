# Quarterly Team Performance Dashboard - Nexus Tech

This project presents a Quarterly Team Performance Management Dashboard for a fictitious B2B company that sells computer hardware. The analysis is based on sales pipeline data covering accounts, products, sales teams, and sales opportunities, and it was built to help management monitor team performance across quarters and managers.

The dashboard is designed to show how each sales team is performing compared with the rest, whether any sales agents are lagging behind, how results change quarter over quarter, and which  sales agents have stronger win rates. It combines summary KPIs, agent-level performance tables, sector revenue analysis, and detailed performance charts to support faster performance review and better decision-making.

# The Dataset

The dataset consists of CRM records exported from MavenTech spanning October 2016 to December 2017. It details various sales opportunities, including related information such as product types, account details, and final deal outcomes (won or lost). Source: https://mavenanalytics.io/data-playground/crm-sales-opportunities

## The Dashboard 

<img width="2083" height="1163" alt="Nexus Tech_POWER BI_All" src="https://github.com/user-attachments/assets/1ee0f96d-52f2-4209-92d9-24fdb46d3030" />

## What the dashboard shows

The top section of the dashboard highlights key KPIs for the selected manager and quarter, including previous quarter revenue, open deals, and whether the agent is on track or lagging . The central visuals show sales performance by agent and product category, with a matrix of sales activity across hardware product groups and a treemap of total sales revenue by sector. Upper section also includes a manager trend visual that shows total sales revenue by manager, making it easier to compare performance across leaders and spot differences in revenue contribution. The lower section breaks down individual agent performance through metrics such as won deals, win rate, average sales cycle, total revenue, and lost deals, which makes it easier to identify top performers and weaker areas.

## Main business questions

- This dashboard was built to answer the following questions:
- How is each sales team performing compared with the rest?
- Are any sales agents lagging behind?
- Does any sales agent have better win rates?
- Which agents generate the highest revenue relative to their open deals?
- Which managers contribute the most revenue?
- Which manager leads the strongest team overall?

# Data Model

<img width="1492" height="1062" alt="Nexus Tech_Data Model" src="https://github.com/user-attachments/assets/7b548033-49cf-44e0-b1bf-64318c5bbed8" />

The data required minimal cleaning, and the modeling process was straightforward. The primary objective was establishing a relationship between the Date and Sales tables to link both engagement and closure dates.

# Filters used

The dashboard includes two main filters at the top right: Team Manager and Quarter.

 - The Team Manager filter lets the user switch between 6 team managers such as Rocco Neubert and Celia Rouche, allowing side-by-side review of team performance.

- The Quarter filter lets the user view one quarter at a time or all quarters together, which supports comparison across reporting periods and highlights quarter-over-quarter trends.

These filters update all visuals on the page, so the dashboard can be explored from different angles without changing the layout.

<img width="2092" height="1170" alt="Nexus tech_Power BI_Rocco Neubert_Q2" src="https://github.com/user-attachments/assets/5bdfa6c8-829c-4b29-bb04-f43677b28a9e" />


<img width="2092" height="1165" alt="Nexus Tech_Power BI_Celia_Rouche_All" src="https://github.com/user-attachments/assets/828e4329-d162-4a90-9819-04add9fb1cf8" />


# Key dashboard elements

- KPI cards summarize the current quarter’s main performance indicators, such as revenue, open deals, and lagging/on-track status .

- Agent performance matrix shows sales activity across product categories for each agent.

- Sector treemap highlights which product sectors generate the most revenue.

- Manager trend visual compares total sales revenue across managers.

- Agent detail charts show won deals, win rate, average sales cycle, total revenue, and lost deals for deeper performance analysis .

# Business value

This dashboard helps management review team performance, compare managers, and identify where sales activity is strong or weak. It also supports coaching by showing which agents are lagging, which ones close deals efficiently, and which product or sector segments are driving revenue. Overall, it turns raw B2B pipeline data into a practical performance management tool for quarterly review and action planning.

