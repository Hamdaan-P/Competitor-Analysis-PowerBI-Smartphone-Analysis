This project is a dynamic Power BI report designed to provide strategic market intelligence for the smartphone industry. It leverages data wrangling (Power Query), DAX calculations, and advanced visualization techniques (like the Strategy Matrix) to benchmark competitor performance, pricing, and feature trends.

🎯 Project Goal
To create a comprehensive, three-part interactive report that allows product managers and strategists to quickly identify market leaders, assess long-term feature performance, and pinpoint strategic opportunities/vulnerabilities within the mobile market.

🛠️ Skills & Technologies Used
Tool: Power BI Desktop (DAX, Power Query)

Visualization: Scatter Plots (Strategy Matrix), Line Charts, Bar Charts, Donut Charts

Advanced Features: Page Navigator, Drillthrough, Conditional Formatting (Data Bars, Rules), Tooltip Pages

Data Source: mysmartprice_mobile_dataset.csv

Data Preparation: Power Query was used extensively for data cleansing, including:

Handling text-based numerical data (e.g., converting "16.9K Ratings" to a numeric value).

Cleaning and transforming the expert_view and price fields.

📊 Key Report Pages & Insights
The report is structured into three strategic pages, each addressing a critical business question:

1. Market Overview 📈
Focus: High-level market landscape, price distribution, and overall brand dominance.

Key Insight: Realme, Samsung, and Vivo are the dominant brands by sheer Total Models (volume), but Apple maintains the highest Average Price by a significant margin (∼₹86K vs. ∼₹41K for Google/Nubia), underscoring its premium positioning.

2. Feature Benchmarking 🔋
Focus: Analyzing user satisfaction trends and feature popularity over time.

Key Insight: The User Satisfaction Trend shows that Apple consistently maintains the highest rating, but brands like Oppo and Realme have shown significant recovery in 2024. The average user rating dip across most brands from 2020 to 2022 suggests an industry-wide challenge in meeting expectations during that period.

Technical Detail: The CPU Distribution Donut Chart highlights the fragmentation of the processor market, with a few key players like MediaTek and Snapdragon dominating the top share.

3. Price vs. Performance Strategy 💡
Focus: Competitive positioning using a custom-built Strategy Matrix (Scatter Plot with Average Lines).

Key Insight (Strategy Quadrants):

Value Leaders (Top-Left): Brands like Xiaomi and Vivo offer high ratings at an affordable price—the biggest competitive threat.

Premium Leaders (Top-Right): Apple sits alone, justifying its high price with a high rating (the Benchmark).

Vulnerable (Bottom-Right): Brands in this quadrant (e.g., Cat, Nubia) charge high prices but fail to deliver on user satisfaction, making them prime targets for competitors.

Interactivity: The Top Competitor Metrics table uses Conditional Formatting (Data Bars and Background Colors) to instantly compare the value proposition (Rating vs. Price) of the top brands.

🖱️ How to Use the Report
The final report is built for maximum interactivity:

Page Navigation: Use the Page Navigator buttons at the bottom to switch between the three main views.

Drillthrough: Right-click any brand name in the Top Competitor Metrics table and select "Drillthrough" to jump to the Brand Drilldown page for full model-level specifications.

Tooltip: Hover over any line on the User Satisfaction Trend chart to instantly view key metrics for that brand via the custom tooltip.

File: Competitor Analysis.pbix

Data: mysmartprice_mobile_dataset.csv


## License
This project is licensed under the [MIT License](LICENSE).
