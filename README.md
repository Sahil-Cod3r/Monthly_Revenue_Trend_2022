# Monthly Revenue Trend — 2022

A Looker Studio dashboard built to help the Sales Team understand how revenue changed month over month during 2022, in order to spot seasonal patterns and overall sales performance.

🛠️ Tools Used
- Google Looker Studio — for building the line chart and dashboard
- Google Sheets — as the connected data source

🧾 Dataset
- File: Sales_Data_2022.csv
- Columns:
  - order_id — unique order identifier
  - order_date — date the order was placed
  - before_discount — order revenue before discount was applied
  - discount — discount amount applied
  - after_discount — final revenue after discount

⚙️ How the Chart Was Built
1. Connected the dataset to Looker Studio via Google Sheets.
2. Set the Dimension to order_date, grouped by Year Month.
3. Set the Metric to SUM of before_discount, representing total monthly revenue.
4. Applied a filter: order_date is in the year 2022, to restrict the data to the required year.
5. Styled the chart with a custom title, border, and line color for a clean, presentable look.

🔍 Key Insight
Revenue stayed relatively stable from January through August 2022, then rose sharply from September through December — reflecting a strong seasonal/festive-quarter trend.

👤 Author
Sahil Kumar 
