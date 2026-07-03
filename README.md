# Sales-Profit-Analyses
# Sales & Profit Performance Analysis — Excel Project

An end-to-end Excel data analysis project: raw sales data → formulas →
PivotTables → PivotCharts → business insights. 

## Skills demonstrated

- **Formula-driven calculations** — derived fields built with cell
  references (not hardcoded values), so the whole workbook recalculates
  automatically if the source data changes
- **PivotTables** — three PivotTables summarizing 20 orders by Product,
  District, and Salesperson
- **PivotCharts** — native Excel charts linked directly to each PivotTable
- **COUNTIF / SUM** — conditional counting and totals (e.g. total orders
  for a specific product or district)
- **Multi-sheet workbook structure** — a clean, navigable workbook (Cover
  Page → Data → Products → SalesPerson → District → Pivot Table)
- **Currency and number formatting** for a professional, readable layout

## The workbook

📄 [`Sales_Profit_Analysis.xlsx`](Sales_Profit_Analysis.xlsx)

| Sheet | What it contains |
|---|---|
| Cover Page | Title page for the workbook |
| Data | 20 raw sales orders plus two calculated columns (`Profit`, `Predicted Profit 10%`) |
| Products | PivotTable + PivotChart: total quantity sold by product |
| SalesPerson | PivotTable + PivotChart: total quantity sold by salesperson |
| District | PivotTable + PivotChart: total quantity sold by district |
| Pivot Table | Consolidated pivot view of the full dataset |



## Key insights

- **Quantity sold:** Paper (29 units) sold the most overall, followed
  closely by Folders (27) and Fasteners (26).
- **Profit by district:** Leeds recorded the highest quantity sold (32), followed
  by Cardiff (23) and Birmingham (21). Bristol (2) and Liverpool (6) were
  lowest.
- **Profit by salesperson:** Gareth Evans led in units sold (25), with Alison
  Smith (21) and Hadyn Jones (17) also performing strongly.
- **Profit by district:** London generated the highest total profit (£130),
  while Bristol generated the least (£20).
- **Profit by salesperson:** Gareth Evans also led in profit (£100), while
  three salespeople tied for lowest (£20 each) — a possible coaching
  opportunity.
- **Profit by product:** Envelopes were the most profitable line (£150
  total margin), while Fasteners were the least (£50).

## Tools used

Microsoft Excel — formulas, PivotTables, and PivotCharts only. No external
scripts or libraries were used to produce the analysis.
