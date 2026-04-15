# -E-Commerce-Sales-Analysis-Dashboard
A fully interactive dark-themed Excel dashboard built from scratch using raw e-commerce data, Pivot Tables, Slicers, and advanced chart formatting.


🚀 Overview
This project transforms raw e-commerce transactional data into a premium, interactive Excel dashboard that provides real-time business insights across sales, profit, customers, and product performance.

✨ Features

📦 5 KPI Cards — Sales, Profit, Quantity, Orders, Profit Margin
⚠️ Smart Alert Card — Red warning card for declining Profit Margin (YOY ▼5.15%)
▲▼ YOY Growth Indicators — Green/Red conditional formatting with custom number format
📈 Monthly Sales & Profit Trend — Combo chart (Bar + Line)
🏷️ Profit by Category — Column chart (Technology, Office Supplies, Furniture)
🍩 Sales Distribution by Category — Donut chart with percentages
👥 Top 5 Customers by Revenue — Horizontal bar chart
🗺️ Geographic Sales Distribution — Filled map chart with teal gradient
🛒 Best Selling Products by Quantity — Donut chart with custom icon
🎛️ Interactive Slicers — Filter by Region & Shipment Mode


🛠️ Tools & Techniques Used
ToolUsageMicrosoft ExcelDashboard buildingPivot TablesData aggregationPivot ChartsAll 7 visualizationsSlicersInteractive filteringConditional FormattingYOY growth colorsCustom Number Format▲▼ arrow symbolsSparklinesKPI card trend linesMap ChartGeographic distributionShape FormattingDark theme KPI cards

📁 Project Structure
📦 ecommerce-dashboard
 ┣ 📊 ECommerce_Dashboard.xlsx    # Main dashboard file
 ┣ 📄 Raw_Data.csv                # Original dataset
 ┗ 📸 dashboard_preview.png       # Dashboard screenshot

📊 Dataset
The dataset contains 9,994 orders with the following fields:

Order ID, Order Date, Ship Date
Region, State, City
Category, Sub-Category, Product Name
Customer Name, Segment
Sales, Profit, Quantity, Discount
Ship Mode


📈 Key Insights
MetricValueYOY GrowthTotal Sales$2,297,200.86▲ 20.62%Total Profit$286,397.02▲ 14.41%Total Quantity37,873▲ 27.45%Total Orders9,994▲ 28.64%Profit Margin12.47%▼ 5.15% ⚠️

Technology leads in profit ($145.45K)
Furniture has the lowest profit margin despite 32.30% sales share
Staples is the highest selling product by quantity (876 units)
Sean Miller is the top customer ($25.04K)
Sales peak in Q4 (Sep–Dec) showing strong seasonality


🎨 Design Highlights

Dark navy theme (#0A0F1E background)
Cyan accent (#00BCD4) for positive metrics
Metallic grey KPI cards with gradient
Lime green profit trend line (#76FF03)
Deep red alert card for declining margin
Teal gradient map chart


🔧 How to Use

Download ECommerce_Dashboard.xlsx
Open in Microsoft Excel 2016 or later
Use Region slicer to filter by Central / East / South / West
Use Ship Mode slicer to filter by shipping class
All charts and KPIs update automatically ✅


📌 Requirements

Microsoft Excel 2016+ (for Map Chart support)
Windows recommended (Map Charts may not render on Mac)


🙋‍♂️ Author
Built with 💪 from raw data to a professional dashboard.
Feel free to ⭐ star this repo if you found it useful!

📄 License
This project is open source and available under the MIT License.
