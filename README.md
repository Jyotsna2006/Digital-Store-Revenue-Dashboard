# Digital-Store-Revenue-Dashboard
# Digital Store Revenue & Regional Sales Performance Dashboard

An interactive Business Intelligence solution built in Power BI to transform multi-state retail transaction ledgers into clean, executive-level operational insights.

## Dashboard Preview
![Digital Store Dashboard](Digital_Store_Revenue_Dashboard.png)

## Business Case
For expanding digital retail brands, tracking metrics across multiple regions, product categories, and payment channels can quickly become overwhelming. Raw transactional spreadsheets often hide major trends, making it difficult for management to:
* **Identify Profitability Cycles:** Spotting precisely when and why profit margins surge or dip throughout the fiscal year.
* **Optimize Inventory Mix:** Understanding product demand distribution to avoid overstocking slow-moving items.
* **Analyze Customer Behavior:** Evaluating localized payment preferences to smooth out the checkout experience.

This project bridges that gap by turning flat transaction rows into a centralized, highly responsive visual intelligence hub that supports data-driven decision-making.

## Project Objectives
* **Consolidate High-Level Metrics:** Give busy executives a clear overview of gross revenue, unit volumes, net profit, and average order values.
* **Expose Regional Performance:** Use geographic grouping to show exactly which states are driving the business forward.
* **Track Monthly Growth Trends:** Highlight seasonal performance shifts over a rolling 12-month calendar.
* **Enable Interactive Discovery:** Create a fully connected workspace where users can cross-filter the entire dashboard by clicking any chart element.

## 📈 Core Performance Metrics (KPIs)
The top section features crisp KPI cards highlighting macro-level business performance dynamically updating based on filter selection:
* **Sum of Amount:** The absolute gross revenue generated across all digital sales channels.
* **Sum of Quantity:** Total inventory units successfully cleared through fulfillment.
* **Sum of Profit:** The actual bottom-line revenue retained after factoring in product costs and margin variations.
* **Sum of AOV:** Cumulative Average Order Value tracking to measure consumer purchasing power and cart sizes.

## Key Visualizations & Insights
* **Dynamic Navigation Panel:** A dedicated multi-select sidebar featuring streamlined State and Quarterly slicers to let users instantly pivot the entire reporting layout.
* **Product Demand Matrix (Donut Chart):** Breaks down product quantity contribution by category, identifying the primary volume drivers across clothing, electronics, and furniture segments.
* **Checkout Channel Preferences (Donut Chart):** Monitors user transaction selections, mapping the distribution across cash on delivery (COD), UPI, debit cards, and credit cards.
* **Product Line Profitability (Horizontal Bar Chart):** Ranks sub-categories by true net profit, isolating high-margin performers for targeted promotional focus.
* **Chronological Profit Velocity (Column Chart):** Maps profit fluctuations month-by-month over time, making it effortless to identify strong seasonal growth peaks versus sudden margin drops.

## 📂 Dataset Overview
The project utilizes an order-level digital store transactions dataset. The database includes detailed line items capturing unique order dates, customer names, delivery cities, states, payment modes, and specific product categories. 

*Note: This dataset represents simulated business operations and was used entirely for technical learning, data modeling validation, and portfolio demonstration purposes.*

## Tools & Analytical Techniques Deployed
* **Power BI Desktop:** The core platform used for visual design, grid alignment, and interface wireframing.
* **Power Query Editor:** Deployed for data cleaning, structural validation, and removing duplicate records.
* **Data Modeling:** Modeled a clean relational database schema to maintain high-performance chart interactivity without screen lag.
* **DAX Formulas:** Formulated logical measures and custom aggregations to extract precise corporate performance targets.
* **Executive Presentation:** Crafted with a minimalist light corporate theme, focusing heavily on clean spaces, crisp text contrast, and rounded container cards to ensure professional readability.

## Key Learnings
* Developed a strong understanding of how to translate cluttered business tables into intuitive visual stories that speak directly to stakeholder needs.
* Gained hands-on experience using modern UI/UX design frameworks to lay out complex charts naturally for end users.
* Learned how to build end-to-end data pipelines, ensuring data formatting rules are fully aligned in Power Query before sketching out visuals.
* Mastered the professional workflow of packaging, documenting, and presenting data assets to clean corporate standards.
