# SuperStore-Data-Analysis-using-PowerBI

In this project we used dataset from Kaggle, that called: SuperStore. Which consist this columns:
| Column        | Meaning              |
| ------------- | -------------------- |
| Order ID      | Unique order         |
| Order Date    | Date of order        |
| Ship Date     | Shipping date        |
| Customer Name | Customer             |
| Segment       | Consumer / Corporate |
| Region        | Area                 |
| Category      | Product type         |
| Sub-Category  | Product group        |
| Sales         | Revenue              |
| Profit        | Profit or loss       |


we used powerBI to making  data analysis and producing dashboard to show the descriptive analysis and we applied this steps:
1. Remove empty rows
Home → Remove Rows → Remove Blank Rows

2. Change Date Format
Order Date → Date
Ship Date → Date

3.Check Sales & Profit
Ensure they are Decimal numbers

4. Create Year & Month Columns
From OrderDate:
Select OrderDate
Add Column → Date → Year → Year
Add Column → Date → Month → Name of Month

5.Handle Missing Values. ex:Replace null Sales with 0 and Remove rows with missing CustomerName

6. Create a Profit Category Column. By: Create a conditional column:
Profit > 0 → "Profit"
Profit ≤ 0 → "Loss"
# 7. Descriptive Analytics:
  
  7.1 Create Key Measures By DAX: Total Sales = SUM(Orders[Sales]) and Total Profit = SUM(Orders[Profit]) 
  
  7.2 Going to the Report view after saving your work in Table view, then we Created 2 cards:Card → Total Sales and Card → Total Profit to answer about  How much did we sell? How much profit did we make?
  
   7.2.2 show Sales by Region using Bar Chart to answer about Which region sells most? and show Monthly Sales Trend using Trend Line to show Sales trend over time and finally we used Donut chart to show Profit vs Loss  to show about: How much sales are profitable?



# Final Dashboard

<img width="880" height="488" alt="image" src="https://github.com/user-attachments/assets/7419ab9c-8188-42ac-9a90-260159337c1b" />
