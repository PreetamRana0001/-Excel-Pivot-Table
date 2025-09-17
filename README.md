# 📊 Excel Pivot Table

The **Pivot Table** in Excel is a powerful tool to **summarize, analyze, explore, and present large datasets** quickly.  
It helps in generating insights without writing complex formulas.

---

## 📌 Key Features
- Summarizes large datasets in **rows, columns, and values**.
- Supports **filters, slicers, and grouping**.
- Allows **aggregation functions** like SUM, COUNT, AVERAGE, MAX, MIN.
- Can create **interactive dashboards**.

---

## 📊 How to Create a Pivot Table
1. Select your dataset.
2. Go to **Insert → PivotTable**.
3. Choose the location (new worksheet or existing worksheet).
4. Drag fields into **Rows, Columns, Values, and Filters**.
5. Apply **sorting, filtering, and formatting** as needed.

---

## 📌 Example

Suppose you have a sales dataset:

| Product | Region | Sales |
|---------|--------|-------|
| Apple   | East   | 100   |
| Banana  | West   | 150   |
| Apple   | West   | 200   |
| Banana  | East   | 50    |

You can create a Pivot Table to show **total sales per product per region**:

- Rows → Product  
- Columns → Region  
- Values → SUM of Sales  

Result:

| Product | East | West | Grand Total |
|---------|------|------|-------------|
| Apple   | 100  | 200  | 300         |
| Banana  | 50   | 150  | 200         |
| **Grand Total** | 150  | 350  | 500         |

---

## 🚀 Key Tips
- Use **Slicers** for interactive filtering.
- Group dates or numbers for **better analysis**.
- Refresh Pivot Table after updating your dataset:  
  ```excel
  Right-click → Refresh
