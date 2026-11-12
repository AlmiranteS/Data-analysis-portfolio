**SALES TRANSACTIONS ANALYSIS**

**TOOLS:** Python 3.14.3, Pandas, Matplotlib, Seaborn, Jupyter Notebook

**KEY INSIGHTS:**

I just completed a comprehensive Exploratory Data Analysis (EDA) project on a sales transactions dataset with 18045 lines and 36 columns. The goal was to turn raw data into business intelligence, **covering 5 key pillars: Financials, Product Portfolio, Logistics, Customer Behavior, and Sales Channels.**

**Here are the main insights the data revealed:**

**1. The Danger of Discounts (Financials):**
The current discount policy is eroding profit margins. While products sold at 0% discount maintain a healthy margin (25% and an average profit of $120), discounts above 10% drop the margin to 10% and average profit to $41. Above 20%, profit is practically zero. The most surprising finding? Increasing the discount did not increase sales volume.

**2. Accessories are the "Hidden Gems" (Portfolio):**
Electronics and Office Furniture are the cash cows in terms of revenue volume. However, when analyzing Markup, Accessories stand out with the highest profit margin over cost (1.40x), while Printers have the tightest margin (1.16x). Furthermore, the ABC Curve showed that a small number of products (Class A) drive the vast majority of revenue.

**3. Logistics Bottlenecks (Operations):**
The average delivery time is 4 days, but there is a massive discrepancy: the "Standard" method takes an average of 4.5 days, while "Express" and "Next Day" meet very similar timelines (around 1.5 to 2 days). Late deliveries are the primary reason for returns, surpassing even defective products.

**4. The High-Value Customer is Unhappy (Experience):**
There is a red flag here: the more a customer spends, the worse their rating. Customers with a rating of 1 (highly dissatisfied) have a very high average ticket ($410), while customers who rate 5 spend significantly less. This indicates a serious problem in delivering value to the high-ticket audience. The female audience aged 26-45 is the main revenue driver.

**5. Online is King, but Human Sales Matter (Channels & Sales):**
The Online channel dominates absolute revenue, but the B2B Portal and Retail Store show a much more balanced profit ratio. In human sales, representatives Lucas Moore and Michael Clark lead in generated profit. For payments, Credit Card and Apple Pay concentrate the highest volume, but with slightly higher return rates.

**What would I do with this in practice?**
There is an urgent need to review the discount policy, focus on cross-selling accessories with electronics, and investigate why high-value customers are giving such low ratings.

This was a great exercise in data cleaning (handling nulls and standardizing categorical variables like Gender and Payment Method) and data visualization using Python, Pandas, Matplotlib, and Seaborn.

<img width="1790" height="1965" alt="Dashboard of Sales Transactions" src="https://github.com/user-attachments/assets/6b8e05ee-9a78-4f92-823b-1d387f000cf9" />
#DataAnalytics #Python #DataScience #EDA #BusinessIntelligence #Pandas #DataViz #Insights
