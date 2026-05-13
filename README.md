# E-Commerce Profitability Analysis — BrightCart

## Project Overview
A complete end-to-end profitability analysis for BrightCart, a 
direct-to-consumer e-commerce brand generating $236,318 in net 
revenue across 8 product categories and 4 sales channels. The goal 
was to identify which categories and channels are truly profitable 
after accounting for all costs, and which marketing platforms deliver 
the best return on ad spend.

## Tools Used
- Microsoft Excel — Pivot Tables, Data Cleaning, Charts, Dashboard

## Dataset


| Dataset | Description | Link |
|---|---|---|
| Orders | 2,000 order-level transactions (2024–2025) | [orders.csv](orders.csv) |
| Products | 207 products across 8 categories | [products.csv](products.csv) |
| Marketing Spend | 144 months of spend across 6 platforms | [marketing_spend.csv](marketing_spend.csv) |

## Key Questions Answered
1. Which product category is most and least profitable?
2. Which sales channel delivers the best profit per order?
3. What is the return rate by category and channel?
4. Which marketing platform delivers the best ROAS?
5. Where should the company cut 20% of its marketing budget?

## Key Findings

### 1. Category Profitability
Electronics is the most profitable category at 26.4% margin earning 
the highest average profit per order. Books is the least profitable 
at approximately 12% margin — high shipping costs relative to low 
selling prices wipe out most of the revenue.

![Category Profitability Chart](screenshots/category_profitability.png)

### 2. Channel Analysis
Mobile App is the best performing sales channel at 25.9% margin. 
Marketplace is the worst at 11.2% — platform fees of $7,950 heavily 
cut into what would otherwise be a healthy margin.

![Channel Analysis Chart](screenshots/channel_analysis.png)

### 3. Return Rate Analysis
144 out of 2,000 orders were returned — a 7.2% overall return rate 
resulting in $22,207 in lost revenue. Electronics has the highest 
return rate at 8.6% and Social Commerce has the worst channel return 
rate at 9.1%.

![Return Rate Chart](screenshots/return_rate.png)

### 4. Marketing ROAS Analysis
TikTok Ads delivers the highest ROAS at the lowest cost per 
acquisition ($3.93). Email Marketing is the worst performing platform 
with the lowest ROAS and a CPA of $26.01 — over 6x more expensive 
than TikTok. December 2025 was the only month in the entire dataset 
where ROAS dropped below 1.0 (0.67), meaning BrightCart was actively 
losing money on advertising that month.

![ROAS Analysis Chart](screenshots/roas_analysis.png)

### 5. Budget Cut Recommendation
Cutting the entire Email Marketing budget saves $24,461 annually. 
Reallocating half of that to TikTok Ads is projected to generate 
$298,000 in additional attributed revenue based on current ROAS 
performance.

![Dashboard](screenshots/dashboard.png)

## Dashboard Preview
![Full Dashboard](screenshots/dashboard.png)

## Recommendations Summary
1. **Grow Electronics and Toys** — highest and second highest profit 
   margins. Protect and increase investment in these categories.
2. **Reduce Marketplace dependency** — $7,950 in platform fees makes 
   this the least profitable channel. Shift focus to Mobile App and 
   Website.
3. **Cut Email Marketing** — lowest ROAS of all 6 platforms. 
   Reallocate the $24,461 budget to TikTok Ads which delivers 24x 
   return on every dollar spent.
























