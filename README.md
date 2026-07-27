# Quarterly Team Performance Dashboard - Nexus Tech

This project presents a Quarterly Team Performance Management Dashboard for a fictitious B2B company that sells computer hardware. The analysis is based on sales pipeline data covering accounts, products, sales teams, and sales opportunities, and it was built to help management monitor team performance across quarters and managers.

An interactive dashboard built in Power BI, featuring dynamic visuals driven by the custom DAX measures. The dashboard is designed to show how each sales team is performing compared with the rest, whether any sales agents are lagging behind, how results change quarter over quarter, and which  sales agents have stronger win rates. It combines summary KPIs, agent-level performance tables, and detailed performance charts to support faster performance review and better decision-making.

# The Dataset
This project uses CRM records exported from MavenTech, covering the period from October 2016 to December 2017. The dataset includes sales opportunities and related attributes such as product type, account details, and final deal outcome. Source: https://mavenanalytics.io/data-playground/crm-sales-opportunities. All files used and created for this analysis are stored in the CRM+Sales+Opportunities folder in this repository.

# The Dashboard 

<img width="1626" height="893" alt="Nexus Tech_Power BI__All" src="https://github.com/user-attachments/assets/3bc50e17-98b0-4a51-8182-43b14f591717" />

# What the dashboard shows

The top section of this interactive dashboard highlights key KPIs for the selected manager and quarter, including previous quarter revenue, open deals, and whether the agent is on track or lagging, product rank by revenue. Upper section also includes a manager trend visual that shows total sales revenue by manager, making it easier to compare performance across leaders and spot differences in revenue contribution. 

The lower section breaks down individual agent performance through metrics such as won deals, win rate, average sales cycle, total revenue, and lost deals, which makes it easier to identify top performers and weaker. The second page shows product sales performance by agent, including a matrix of sales activity across hardware product groups, the average sales cycle in days, and total revenue earned. It also includes a quarterly revenue chart.

# Main business questions

 This interactive dashboard was built to answer the following questions:
 
- How is each sales team performing compared with the rest?
- Are any sales agents lagging behind?
- Does any sales agent have better win rates?
- Which managers contribute the most revenue?
- Which manager leads the strongest team overall?
- Which products are sold the most?


# Filters used

The dashboard includes two main filters at the top right: Team Manager, Quarter and Product.

 - The Team Manager filter lets the user switch between 6 team managers such as Rocco Neubert and Celia Rouche, allowing complete review of team performance.
- The Quarter filter lets the user view one quarter at a time or all quarters together, which supports comparison across reporting periods and quarter-over-quarter trends.
- The Product filter allows users to view product performance by selecting the desired product.

These filters update all visuals on the page, so the dashboard can be explored from different angles without changing the layout.

<img width="1617" height="887" alt="Nexus tech_Power BI_Malvin Marxen" src="https://github.com/user-attachments/assets/4b5171e3-2637-4375-87f9-20f74ca5fb60" />


Additional images of the dashboard and model created can be found in the Images_Sales Performance folder of this repository.

<img width="1622" height="891" alt="Nexus Tech_Power BI_Page2" src="https://github.com/user-attachments/assets/a8593603-79c7-45f8-8ab0-d36f2a0f8d31" />

# Key findings

 - Melvin Marxen’s team generated the highest yearly  total revenue, while Darcel Schecht recorded the most won deals and the highest revenue overall, but also the most lost deals.
 - Seven agents are currently lagging behind in performance, including Boris Faz, Rosalina Dieter, and Rosie Papadoulus.
-  Willburn Ferren, from Cara Losch’s team, achieved the highest winning rate.
- Vicki Laflamme, on Celia Rousche’s team, closed the most deals but did not generate the highest revenue among all teams.
- The top-selling products are GTX Basix, which generated 499K in revenue, and MG Advanced, which achieved total revenue of 44K.
- The average time required to sell the products was 51 days.

# Recommendations

- Leverage top performers to standardize best practices
Use Melvin Marxen’s and Darcel Schecht’s approaches to deals and product focus as a benchmark, documenting what they do differently and turning it into a playbook for the rest of the sales organization.

- Address high loss rates with targeted coaching
Since Darcel Schecht combines high revenue and many lost deals, review their pipeline qualification, pricing strategies, and negotiation tactics to reduce losses while preserving their strong win volume.

- Prioritize performance improvement plans for lagging agents
Develop tailored coaching and KPI targets for the seven underperforming agents (including Boris Faz, Rosalina Dieter, and Rosie Papadoulus), focusing on win rate, deal value, and activity quality rather than just volume.

- Optimize deal strategy around high win-rate and high-volume agents
Refine lead assignment by using Willburn Ferren’s high win rate and Vicki Laflamme’s high deal volume as guides, directing high-potential opportunities to agents who either convert most consistently or can manage larger, more complex deals that generate higher revenue.

- Refine product and sales-cycle strategy around GTX Basix and MG Advanced
Increase sales of GTX Basix and MG Advanced through targeted campaigns, pricing and bundling strategies,

- Investigate why some products take longer to sell then other
Investigate why the average sales cycle is 51 days and identifying specific steps to shorten it for high-value products (e.g., clearer value framing)


