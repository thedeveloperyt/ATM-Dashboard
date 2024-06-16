
Full Column Names
1. BANK: Bank Name
2. ATM ID: Automated Teller Machine Identification Number
3. STATE: State Location
4. Effective Days: Number of Days the ATM was Operational
5. Financial Transactions: Number of Financial Transactions
6. Non-Financial Transactions: Number of Non-Financial Transactions
7. Monthly Transactions: Total Number of Transactions Per Month
8. Average Financial Transactions: Average Number of Financial Transactions Per Day
9. Average Non-Financial Transactions: Average Number of Non-Financial Transactions Per Day
10. Average Total Transactions: Average Total Number of Transactions Per Day
11. Monthly Revenue: Revenue Generated Per Month
12. MHA Revenue: Managed Hosting Agreement Revenue
13. ATM Revenue: Revenue Generated Specifically from the ATM
14. Total CRA: Total Cost Recovery Agreement
15. MHA Cost: Managed Hosting Agreement Cost
16. Spare Replacement (SLM) (Asset OEM): Spare Replacement Cost for Self-Learning Mode (Asset OEM)
17. Site Maintenance (Non-Asset): Cost for Non-Asset Site Maintenance
18. Spare Replacement (AC): Spare Replacement Cost for Air Conditioning
19. Spare Replacement (UPS): Spare Replacement Cost for Uninterruptible Power Supply
20. One-time Cost: Any One-time Costs Incurred
21. FLM Supplies: First Line Maintenance Supplies Cost
22. UPS AMC: Annual Maintenance Contract Cost for UPS
23. ATM AMC: Annual Maintenance Contract Cost for ATM
24. VSAT AMC: Annual Maintenance Contract Cost for Very Small Aperture Terminal (VSAT)
25. Bandwidth and Backhaul: Cost for Bandwidth and Backhaul
26. E-Surveillance: Cost for Electronic Surveillance
27. Housekeeping: Housekeeping Cost
28. Electric Bill: Cost of Electricity
29. Rent: Rent Cost
30. Insurance: Insurance Cost
31. EJ Compensation: Electronic Journal Compensation Cost
32. Penalty: Any Penalty Incurred
33. Total Cost: Total Operational Cost
34. Gross Profit: Total Gross Profit
35. Gross Profit Percentage: Gross Profit Percentage
36. Quarter: Financial Quarter
37. ATM Type: Type of ATM
38. Margin Range: Profit Margin Range
39. Current Month Transaction Range: Transaction Range for the Current Month
40. Previous Month Transaction Range: Transaction Range for the Previous Month
41. Previous 2nd Month Transaction Range: Transaction Range for the Second Previous Month
42. Current Margin Range Above/Below 0%: Indicates if the Current Margin Range is Above or Below 0%
43. Previous Month Margin Range Above/Below 0%: Indicates if the Previous Month Margin Range is Above or Below 0%
44. Previous 2nd Month Margin Range Above/Below 0%: Indicates if the Second Previous Month Margin Range is Above or Below 0%
45. Previous 3rd Month Margin Range Above/Below 0%: Indicates if the Third Previous Month Margin Range is Above or Below 0%
46. Category: Category of the ATM
47. Revenue Performance: Performance Based on Revenue
48. Up Time: Operational Uptime of the ATM

 Steps to Visualize Data in Power BI

1. Import Data:
   - Open Power BI Desktop.
   - Click on "Get Data" and import your dataset (Excel, CSV, etc.).

2. Data Cleaning and Transformation:
   - Use Power Query Editor to clean and transform your data. Ensure all columns have appropriate data types.

3. Creating Relationships:
   - If you have multiple tables, ensure they are related correctly using primary and foreign keys.

4. Building Visuals:
   Bar/Column Charts: Show Financial and Non-Financial Transactions, Monthly Transactions, and Revenue.
   Pie/Donut Charts: Show the distribution of Cost Types (e.g., Site Maintenance, Spare Replacement).
   Line Charts: Show trends over time for Transactions, Revenue, and Costs.
   Cards/KPIs: Display key metrics like Total Revenue, Total Cost, Gross Profit, and Up Time.

5. Using Filters and Slicers:
   - Add filters and slicers to enable dynamic data analysis. For instance, you can filter by State, ATM Type, Quarter, etc.

6. Setting Up Dashboards:
   - Arrange your visuals in a coherent dashboard. Group related visuals together for better insights.

 Example Visuals and Insights

1. Monthly Revenue and Cost Analysis:
   Visual: Clustered Bar Chart
   Insight: Compare Monthly Revenue against Total Cost to visualize profitability.

2. Transaction Trends:
   Visual: Line Chart
   Insight: Observe trends in Financial and Non-Financial Transactions over months.

3. Cost Breakdown:
   Visual: Stacked Column Chart
   Insight: Breakdown of different cost components (e.g., Maintenance, Spare Parts).

4. Profit Margin Analysis:
   Visual: Scatter Plot
   Insight: Scatter plot of Gross Profit Percentage vs. ATM ID to identify which ATMs are most profitable.

5. Geographical Analysis:
   Visual: Map
   Insight: Display ATMs on a map to see geographical distribution and performance metrics by state.

 Implementing in Power BI

1. Create Calculated Columns/Measures for complex calculations like Gross Profit Percentage or Average Transactions.
2. Use Tooltips to show detailed information when hovering over visuals.
3. Conditional Formatting to highlight important insights (e.g., negative profit margins).

This setup will provide a comprehensive and interactive dashboard that offers clear insights into ATM performance, costs, and profitability.
