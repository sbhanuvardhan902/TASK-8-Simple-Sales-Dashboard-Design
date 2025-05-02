
# 🧾 TASK 8: Simple Sales Dashboard Design

## 📌 Objective
Create an interactive sales dashboard using Power BI to analyze sales data by product category, region, and month.

---

## 📁 Dataset
**File Used**: Sample_Superstore_Sales.csv  
**Columns**: Order Date, Region, Category, Sales, Profit

---

## 🛠 Tools Used
- Power BI Desktop
- (Optional) Python + Pandas (for initial exploration)

---

## 🚀 Steps to Reproduce

1. **Import Data**
   - Load `Sample_Superstore_Sales.csv` into Power BI using **Home > Get Data > Text/CSV**.

2. **Transform Date**
   - Create a new column: `MonthYear = FORMAT([Order Date], "MMM-YYYY")`
   - Sort `MonthYear` using a helper column: `MonthNum = YEAR([Order Date]) * 100 + MONTH([Order Date])`
   - Sort `MonthYear` by `MonthNum`.

3. **Create Visuals**
   - 📈 **Line Chart**: Sales over `MonthYear`
   - 📊 **Bar Chart**: Sales by `Region`
   - 🍩 **Donut Chart**: Sales by `Category`

4. **Add Slicer**
   - Use a slicer for `Region` (or `Category`)
   - Change slicer to dropdown using the dropdown arrow on the visual

5. **Apply Conditional Formatting**
   - Use color gradients or custom colors to highlight top-performing segments

---

## 📈 Insights Summary
See `TASK_8_Sales_Dashboard_Insights.txt` for 3–4 key findings from the dashboard.

---

## 📦 Deliverables
- 📊 Dashboard (Power BI `.pbix` file or PDF screenshot)
- 📄 `TASK_8_Sales_Dashboard_Insights.txt`
- 📘 This `README.md`

