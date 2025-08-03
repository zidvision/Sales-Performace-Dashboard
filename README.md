# Sales Performance Dashboard (Power BI)

## Project Objective  
To analyze sales trends, identify top-performing products, and visualize geographic distribution of transactions across an 11-month period.  
This dashboard supports business decision-making by highlighting revenue performance and helping stakeholders understand which products and regions drive the most sales.

---

## Dataset Used  
- `Online Retail`  
By: [Chen, D. (2015). Online Retail [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5BW33.](https://archive.ics.uci.edu/dataset/352/online+retail)
---

## Business Questions Answered  
- Which products generate the most revenue?  
- How do monthly sales trends fluctuate over time?  
- In which regions do most sales occur?  
- How can users explore product-level performance using interactive slicers?

---

## Process  

### Data Cleaning and Transformation (in Power BI)
- Removed nulls and duplicate records  
- Filtered irrelevant transactions (e.g., canceled orders)  
- Added a calculated column: `Total Sales = Quantity * Unit Price`  
- Formatted date fields to enable time-based analysis   

*All steps performed via Power Query within Power BI.*

---

## Dashboard Features  
- **Sales Trend Chart**: Monthly sales revenue trend over 11 months  
- **Top Products Chart**: Best-selling products based on total sales  
- **Map Visualization**: Geographic distribution of sales transactions  
- **Interactive Slicers**: Filters by country and month for dynamic exploration

[Open Power BI Dashboard](https://github.com/zidvision/Sales-Performace-Dashboard/blob/main/Dashboard/Sales%20Dashboard%20(2011).pbix)

---

## Key Insights  
- A small subset of products contributes to the majority of sales revenue  
- Sales performance fluctuates significantly across months, highlighting potential seasonal trends  
- The majority of sales are concentrated in a few key countries/regions  
- Interactive filters allow for quick segmentation of performance by product, time period, or location

---

## Conclusion  
This dashboard provides a clear, interactive overview of sales performance and helps business users:  
- Track revenue trends  
- Identify high-performing products  
- Explore market opportunities by geography  
- Make faster data-driven decisions

---

## Tools Used  
- **Power BI**  
  - Power Query for data cleaning and transformation  
  - M language for calculated fields  
  - Power BI visuals for dashboard creation
