# Global Superstore Executive Dashboard (Power BI)

An interactive Power BI dashboard that turns Global Superstore sales data into clear, decision-ready insights on revenue, profit, regions, products, customer segments and time trends. The project includes the dashboard itself, an executive summary with business recommendations, and a short Business Intelligence overview.

![Global Superstore Executive Dashboard](images/dashboard-preview.png)

## Project Objective

To analyse key business dimensions (revenue, profit, geographic regions, products, orders, product categories, customer segments, profit margin and time) and build an interactive dashboard that helps senior management:

- monitor business performance at a glance,
- identify trends and areas of concern, and
- make informed, evidence-based strategic decisions.

## Headline Metrics

| Metric | Value |
|---|---|
| Revenue | $12.64M |
| Profit | $1.467M |
| Profit Margin | 11.61% |
| Total Orders | 51.29K |
| Total Quantity Sold | 178.31K |
| Average Sale | $246.49 |
| Shipping Cost | $1.353M |

*Figures are for the full period shown on the dashboard (year filter 2011–2015, all other filters set to "All").*

## Repository Contents

| File | Description |
|---|---|
| `global_superstore_dashboard.pbix` | The Power BI Desktop report file (open in Power BI Desktop to explore the interactive version). |
| `Global_superstore_Dashboard.pdf` | A static, one-page PDF export of the dashboard. |
| `Executive_Summary_Report.pdf` | Business insights, risks, opportunities and recommendations drawn from the dashboard. |
| `Business_Intelligence_Overview_Report.pdf` | A short overview of BI concepts, why dashboards matter for decision-making, and the project objective. |
| `images/dashboard-preview.png` | Preview image of the dashboard used in this README. |

## Dashboard Features

**KPI cards:** Revenue, Profit, Total Quantity Sold, Profit Margin, Average Sale, Total Orders and Shipping Cost.

**Visuals:**
- Revenue and Profit by Region
- Revenue and Profit by Order Year (trend)
- Revenue and Profit by Month
- Revenue and Profit by Customer Segment
- Revenue and Profit by Product Category
- Revenue and Profit by Product Name
- Profit by Day of the Week
- Country-level table of sales, profit and profit margin

**Interactive filters (slicers):** Year, Month, Day, Region, Country, State, City, Ship Mode, Category, Sub-Category and Customer Segment.

## Key Findings

*Summarised from `Executive_Summary_Report.pdf`.*

**Insights**
- The **Central** region has the highest revenue and profit among the regions shown.
- The **Consumer** segment contributes the most revenue and profit.
- **Technology** is the highest-revenue product category.
- **December** generates the highest revenue, while **November** generates the highest profit, so the busiest month is not always the most profitable.
- Revenue and profit show an upward trend over the years analysed.

**Risks**
- The overall profit margin of about **11.61%** is relatively low, so rising costs, shipping expenses or heavy discounting could reduce profitability.
- **Furniture** earns more revenue than **Office Supplies**, but Office Supplies appears to contribute more profit.
- **Southeast Asia** shows negative profit in some periods, with some products also loss-making.

**Opportunities**
- Study the **North** and **North Asia** regions, which show favourable profit-to-revenue performance, and replicate what works.
- Use targeted campaigns to lift sales in the weaker early-year months without relying on heavy discounts.
- Grow the profitable **Office Supplies** category through bundles and targeted offers.

## Recommendations

1. Strengthen sales and customer retention in the Central region.
2. Develop targeted marketing for the Consumer segment.
3. Review pricing, shipping costs and discounts to improve profit margin.
4. Review the profitability of Furniture and Office Supplies separately.
5. Introduce targeted campaigns during lower-performing months.
6. Expand profitable regional markets and investigate Southeast Asia's losses.
7. Build a regular product-level profitability monitoring routine.

The full report includes the supporting insight, expected benefit and a suggested performance measure for each recommendation.

## Tools and Skills Demonstrated

- **Power BI Desktop:** interactive dashboard design, KPI cards, slicers, charts and tables
- **DAX:** calculated measures such as Profit Margin
- **Data analysis and storytelling:** turning KPIs and trends into business insights, risks and recommendations
- **Business Intelligence concepts:** data integration (ETL), data modelling and presentation

## How to Use

1. Download or clone this repository.
2. Open `global_superstore_dashboard.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows).
3. Use the slicers on the left to filter by year, region, country, category, segment and more.
4. Prefer a quick look? Open `Global_superstore_Dashboard.pdf` or read `Executive_Summary_Report.pdf`.

## Notes and Limitations

- The dashboard is a descriptive analysis of historical data; the recommendations are based on what the dashboard shows and have not been tested or measured for impact.
- The report was built on a single flat table of order-level data rather than a multi-table star schema.
- Dataset source: *[add the source or link to the Global Superstore dataset here]*.

## Author

**Oluwatunmise Philip Bamigbola**
Data Analyst | Lagos, Nigeria

- LinkedIn: [linkedin.com/in/tunmise-bamigbola-b0b11616b](https://www.linkedin.com/in/tunmise-bamigbola-b0b11616b/)
- Portfolio: [behance.net/bamigbotunmise](https://www.behance.net/bamigbotunmise)
