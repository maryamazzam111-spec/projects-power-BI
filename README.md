 📊 B2B Financial & Sales Performance Analysis (Power BI)

##  Project Overview
This project delivers an interactive Power BI dashboard analyzing the financial performance of a B2B mobility & equipment manufacturing business across different regions, product categories, and customer segments (2013–2014).

The analysis goes beyond surface-level sales numbers to evaluate key financial drivers, unit economics, profitability margins, and underlying operational risks.

---

##  Key Metrics (KPIs)
* *Total Revenue:* $118.73M
* *Total Profit:* $16.89M
* *Overall Profit Margin:* 14.23%

---

## Key Business Insights

### 1. Product Performance Analysis
* *Top Performer (Paseo):* Generates the highest sales and total profit, serving as the core revenue driver across all markets.
* *Underperformer (Carretera):* Yields the lowest net profit due to high manufacturing/logistics costs relative to its pricing structure.

### 2. Strategic Segment Findings & Margin Variance
* *High-Margin Drivers (Channel Partners & Small Business):* 
  * Channel Partners achieves an exceptional *73% Profit Margin* due to low overhead and distribution costs.
  * Small Business yields a solid *26.3% Margin*, outperforming traditional B2B averages.
* *The Revenue Anchor (Government):* Generates over 50% of total sales volume ($52.5M). Despite a moderate margin of *12.9%* due to bulk volume discounts, it provides necessary cash-flow stability.
* *Critical Risk (Enterprise):* Shows a *Negative Profit Margin (-3%)*. Volume discounts and high fulfillment overhead severely erode profitability, resulting in net operational losses.

### 3. Geographic & Temporal Growth Trends
* *Geographic Balance:* US leads in both top-line revenue and net profit, with balanced performance across European and Mexican markets.
* *Year-Over-Year Growth (2013 vs 2014):* 
  * Sales grew by *~250%* (from $26M to $92M).
  * Net Profit surged by *~330%* (from $3M to $13M), demonstrating strong economies of scale and improved operational efficiency.

---

##  Strategic Recommendations
1. *Restructure Enterprise Pricing:* Eliminate aggressive volume discounting and renegotiate contract terms to turn the segment profitable.
2. *Expand High-Margin Channels:* Allocate more sales and marketing efforts toward Channel Partners and Small Business segments to maximize net returns.
3. *Optimize Product Mix:* Shift promotional focus toward Paseo while evaluating cost-cutting measures or price adjustments for Carretera.

---

## Data Modeling & DAX Measures Created
* Total Sales = SUM(financials[Sales])
* Total Profit = SUM(financials[Profit])
* Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)

---

## 🛠️ Tools Used
* *Power BI Desktop:* Data Modeling, DAX, Interactive Visualization, Dashboard Design.
* *Dataset:* Financial Sample Dataset (B2B Multi-Region Sales).
