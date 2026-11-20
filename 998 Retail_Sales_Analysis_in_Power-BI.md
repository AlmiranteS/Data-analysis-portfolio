<img width="826" height="460" alt="Captura de tela 2026-11-19 190901" src="https://github.com/user-attachments/assets/d2a20fb4-7b72-4cfe-b9eb-a2bf07a4711e" />
<img width="824" height="467" alt="Captura de tela 2026-11-19 190950" src="https://github.com/user-attachments/assets/1b749e72-a26a-4eed-8da0-c32cfeb74ec3" />

**RETAIL SALES ANALYSIS (IN POWER BI)**

*(Dashboard Screenshots at the Bottom)*

At the beginning of this work, I raise up the following business questions should be answered by my Dashboard:

1. What is our total revenue, and how is it trending over time? (Are we growing?);
2. Which product categories drive the most revenue and volume? (Where should we invest?);
3. Who is our core customer? (Gender, age segments — for targeting);
4. What is the average order value (AOV)? (Pricing/basket strategy);
5. Which months/quarters are strongest? (Seasonality for inventory/staffing);
5. How does purchasing behavior differ by gender and age group? (Segmentation);
6. What is the relationship between quantity purchased and price point? (Basket composition);

**KPI Targets for the Dashboard:**

1. Total Revenue, Total Transactions, Total Units Sold;
2. Average Order Value (AOV), Revenue per Customer;
3. Revenue by Category, by Gender, by Age Band;

**DAX OPERATIONS:**

After cleaning the data (in the Power Query), checking for nulls and duplicates, normalizing data types for each column, creating new columns to get calculated information 
and to check if Total Amount column was correct, I load the data and created some necessary measures and Calculated columns, as the following:

*Measures*: Total Revenue; Total Transactions; Total Units; AOV; Revenue per Customer; MoM Growth.

*Calculated Columns*: Age Band; Quarter.

**Analysis and Visualizations**

After that, I performed the analysis (Matrix Tables - Page 1 of the PBI report) and the visualizations (Charts - pages 2 and 3)

**Key Insights Summary**
1. Stable, balanced business — $455K revenue across 9,998 orders; no single category, gender, or age dominates; 
2. Core customer = 25–54, split evenly by gender — broad targeting is appropriate; hyper-segmentation offers limited ROI;
3. AOV is uniform (~$456) across all cuts — pricing power is consistent, suggesting a fixed price-ladder strategy rather than dynamic pricing;
4. Q4 holiday lift is real but modest (Dec +12% vs. average month) — inventory planning should ramp ~10–15% for Nov–Dec;
5. Revenue pattern = "few big tickets + many small fillers" — high-price items ($300–$500) at qty 1–2 anchor revenue; $25–$50 items at qty 3–4 drive volume.
6. Bundle strategies (attach low-price fillers to high-ticket anchors) could lift AOV.
7. Two 2024-dated transactions must be handled explicitly in YoY comparisons to avoid distortion; so, that rows were deleted.a2bf07a4711e" />
<img width="824" height="467" alt="Captura de tela 2026-11-19 190950" src="https://github.com/user-attachments/assets/1b749e72-a26a-4eed-8da0-c32cfeb74ec3" />
