# ☕ Coffee Sales Dashboard (Excel)

An interactive sales dashboard built in Excel to visualize and analyze a fictional coffee shop's performance over time. This guided project focused on using Excel's advanced functions and pivot features to transform a raw dataset into an insightful and user-friendly business intelligence tool.

---

## 📁 Dataset Overview

The project uses a **sample dataset** split across three sheets:

### 🔹 `orders` (1001 rows)
- Order ID, Order Date, Customer ID, Product ID, Quantity
- Customer details (name, email, country, loyalty card) via `XLOOKUP` from the `customers` sheet
- Product details (coffee type, roast, size, unit price) via `INDEX/MATCH` from the `products` sheet
- Sales = `Unit Price * Quantity`
- Derived fields for full coffee type and roast names using `IF` statements

### 🔹 `products` (49 rows)
- Coffee Type, Roast Type, Size, Unit Price, Price per 100g, Profit

### 🔹 `customers` (1001 rows)
- Customer ID, Name, Email, Phone, Address, City, Country, Loyalty Card

---

## 📊 Dashboard Features

The final dashboard (on the `Dashboard` sheet) includes:

- 📈 **Line Chart**: Total sales over time, broken down by coffee type
- 🌍 **Bar Chart**: Sales by country
- 🧍 **Bar Chart**: Top 5 customers by revenue
- 🗓️ **Timeline**: Selectable month/year range
- 🧩 **Slicers**:
  - Roast Type: Dark, Light, Medium
  - Product Size: 0.2kg, 0.5kg, 1.0kg, 2.5kg
  - Loyalty Card: Yes / No

All visuals are **interactive** and dynamically respond to slicer selections and time filters.

---

## 🛠️ Excel Techniques Used

- `XLOOKUP`, `INDEX/MATCH` to merge data across sheets
- `IF` for label cleanup and conditional logic
- `Pivot Tables` and `Pivot Charts` to summarize sales metrics
- `Table formatting` to enable dynamic range tracking
- `Date formatting` for cleaner visuals (e.g., `dd-mmm-yyyy`)
- `Currency formatting` for unit prices and sales
- Dashboard visual polish:
  - Hidden formula bar, sheet tags, and gridlines
  - Clean white canvas

---

## 📌 Key Insights

- Track revenue trends over months and years
- Identify top-performing coffee types and countries
- Spot high-value customers and reward loyalty card holders
- Make time-based comparisons and analyze product segmentation

---

## 🎯 Use Case

This dashboard simulates a **retail sales analysis tool** for a coffee company. It would be useful for:
- **Sales managers** tracking revenue trends and top customers
- **Marketing analysts** targeting promotions by country or loyalty card usage
- **Product teams** assessing which roast types and sizes sell best

---

## 🖼️ Screenshot

![image](https://github.com/user-attachments/assets/3dca91dc-9373-49a1-bac5-f8a8ee775175)


---

## 📌 Future Improvements

- Add profit analysis and margin tracking
- Include customer lifetime value (CLTV)
- Automate refresh from external data sources
- Provide tooltips and annotations for user guidance

---

## 📂 Files

- `coffee-dashboard.xlsx` – Final version with dashboard and data

