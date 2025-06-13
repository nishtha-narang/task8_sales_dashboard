# task8_sales_dashboard
This Power BI dashboard provides interactive visual insights into sales performance using key business metrics such as Sales, Profit, Category, Region, and Order Date.

## Dataset Overview ##

| Column Name | Description                           |
|-------------|---------------------------------------|
| Order Date  | Date when the order was placed        |
| Region      | Sales region (e.g., East, West)       |
| Category    | Product category (e.g., Furniture)    |
| Sales       | Revenue generated from the order      |
| Profit      | Profit earned from the order          |

## Key Steps in Power BI ##

1. **Tool Used**: Power BI  
2. **Transformations**:
   - Converted `Order Date` to `Month-Year` format for time series analysis  
3. **Visualizations Created**:
   - 📈 **Line Chart**: Sales over Months  
   - 📊 **Bar Chart**: Sales by Region  
   - 🍩 **Donut Chart**: Sales by Category  
4. **Filters/Slicers**:
   - Added slicer for **Region**
  
## Insights ##
- West Region stands at the top in terms of Total Sales across Regions at 725K
- Max Sales of 352K have been hit in the month of November
- All the three categories amount to nearly equal percentage of total, Technology being on top with 36.4% of total

## Tools ##

- Power BI (Desktop)
- DAX for calculations
- Power Query for transformations
