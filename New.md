 1. Monthly Revenue and Cost Analysis
Visual: Clustered Bar Chart

Steps to Create:
1. Select the Clustered Bar Chart visual.
2. Drag State Location (STATE) to the Axis.
3. Drag Revenue Generated Per Month (Monthly Rev) and Total Operational Cost (Total Cost) to the Values.

Insight:
- This chart helps you compare the revenue generated and the total costs incurred for each state.
- You can identify which states have the highest profitability and which states have higher operational costs.

 2. Transaction Trends
Visual: Line Chart

Steps to Create:
1. Select the Line Chart visual.
2. Drag Effective Days or Date to the Axis.
3. Drag Number of Financial Transactions (Fin Txn) and Number of Non-Financial Transactions (Non Fin Txn) to the Values.

Insight:
- This chart allows you to observe trends in the number of financial and non-financial transactions over time.
- You can see seasonal patterns, peaks, and troughs in transaction volumes which can help in planning and forecasting.

 3. Cost Breakdown
Visual: Stacked Column Chart

Steps to Create:
1. Select the Stacked Column Chart visual.
2. Drag State Location (STATE) to the Axis.
3. Drag various Cost Components (e.g., Spare Replacement (SLM) (Asset OEM) (Spare Rep. (SLM) (AssetOEM)), Site Maintenance (Non-Asset) (Site Maint (Non Asset)), etc.) to the Values.

Insight:
- This chart shows the breakdown of different types of costs by state.
- You can identify which cost components are the largest contributors to the total cost in each state and target them for cost-saving measures.

 4. Profit Margin Analysis
Visual: Scatter Plot

Steps to Create:
1. Select the Scatter Plot visual.
2. Drag Automated Teller Machine Identification Number (ATM ID) to the Details.
3. Drag Gross Profit Percentage (GROSS PROFIT %) to the X-Axis.
4. Drag Total Gross Profit (Gross Profit) to the Y-Axis.

Insight:
- This scatter plot helps you see the relationship between the gross profit percentage and the total gross profit for each ATM.
- You can identify which ATMs are performing well and contributing the most to the overall profitability.

 5. Geographical Analysis
Visual: Map

Steps to Create:
1. Select the Map visual.
2. Drag State Location (STATE) to the Location.
3. Drag Revenue Generated Specifically from the ATM (ATM Rev) or Number of Transactions (Monthly Txn) to the Size.
4. Drag Number of Financial Transactions (Fin Txn) and Number of Non-Financial Transactions (Non Fin Txn) to the Tooltips.

Insight:
- This map visual displays ATMs geographically, showing where they are located and their performance metrics.
- You can easily see the distribution of ATMs across states and identify regions with high or low transaction volumes and revenue.

 Additional Tips for Implementing in Power BI

1. Calculated Columns/Measures:
   - Create measures for complex calculations such as Gross Profit Percentage:
     ```DAX
     Gross Profit Percentage = DIVIDE(SUM('Table'[Gross Profit]), SUM('Table'[Monthly Revenue]), 0)
     ```

2. Tooltips:
   - Use tooltips to show additional information when hovering over visuals. For example, you can show the number of financial and non-financial transactions when hovering over a revenue bar.

3. Conditional Formatting:
   - Apply conditional formatting to highlight important data points. For instance, you can color-code profit margins to quickly identify positive and negative margins.

 Example Visuals and Insights Recap

1. Monthly Revenue and Cost Analysis: Identify the most and least profitable states by comparing revenue and cost.
2. Transaction Trends: Observe seasonal patterns and trends in transaction volumes.
3. Cost Breakdown: Analyze the largest cost contributors to target for cost-saving measures.
4. Profit Margin Analysis: Identify which ATMs are performing well in terms of profitability.
5. Geographical Analysis: Visualize the distribution and performance of ATMs across different regions.

These visualizations will help you gain comprehensive insights into ATM performance, operational costs, and profitability, enabling better decision-making and strategic planning for your single bank's ATMs.
