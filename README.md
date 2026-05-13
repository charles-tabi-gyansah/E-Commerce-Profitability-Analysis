# E-Commerce Profitability Analysis — BrightCart

## Project Overview
A complete end-to-end profitability analysis for BrightCart, a direct-to-consumer 
e-commerce brand generating $236,318 in net revenue across 8 product categories 
and 4 sales channels. The goal was to identify which categories and channels are 
truly profitable after accounting for all costs, and which marketing platforms 
deliver the best return on ad spend.

## Tools Used
- Microsoft Excel — Pivot Tables, Data Cleaning, Charts, Dashboard

## Dataset
The analysis is based on three datasets:

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

---

## Key Findings

### 1. Category Profitability
Electronics is the most profitable category at **26.4% margin** — the highest 
of all 8 categories. Books is the least profitable at **10.0% margin** — high 
shipping costs relative to low selling prices wipe out most of the revenue.

| Category | Profit Margin |
|---|---|
| Electronics | 26.4% |
| Toys | 22.5% |
| Home & Kitchen | 21.7% |
| Food & Beverage | 20.6% |
| Sports | 20.3% |
| Clothing | 16.7% |
| Beauty | 15.2% |
| Books | 10.0% |

![Category Profitability Chart](screenshots/category_profitability.png)

---

### 2. Channel Analysis
Mobile App is the best performing sales channel at **25.9% margin**. Marketplace 
is the worst at **11.2%** — platform fees of **$7,950** heavily cut into what 
would otherwise be a healthy margin. Website and Mobile App pay zero platform fees 
which is why they outperform Marketplace and Social Commerce.

| Channel | Profit Margin | Platform Fees |
|---|---|---|
| Mobile App | 25.9% | $0 |
| Website | 22.6% | $0 |
| Social Commerce | 12.7% | $1,945 |
| Marketplace | 11.2% | $7,950 |

![Channel Analysis Chart](screenshots/channel_analysis.png)

---

### 3. Return Rate Analysis
**144 out of 2,000 orders were returned** — a 7.2% overall return rate resulting 
in **$22,207 in lost revenue**. Electronics has the highest category return rate 
at 8.6% and Social Commerce has the worst channel return rate at 9.1%, meaning 
nearly 1 in 10 Social Commerce orders gets sent back.

![Return Rate Chart](screenshots/return_rate.png)

---

### 4. Marketing ROAS Analysis
TikTok Ads delivers the highest ROAS at **24.02** and the lowest cost per 
acquisition at **$3.93**. Email Marketing is the worst performing platform with 
a ROAS of **4.81** and a CPA of **$26.01** — over 6x more expensive than TikTok. 
December 2025 was the only month in the entire dataset where ROAS dropped below 
1.0 to just **0.67**, meaning BrightCart spent $1,797 and only got $1,199 back.

| Platform | ROAS | Avg CPA |
|---|---|---|
| TikTok Ads | 24.02 | $3.93 |
| Influencer | 22.70 | $4.80 |
| Instagram Ads | 15.73 | $5.55 |
| Google Ads | 14.38 | $6.48 |
| Facebook Ads | 11.45 | $8.38 |
| Email Marketing | 4.81 | $26.01 |

![ROAS Analysis Chart](screenshots/roas_analysis.png)

---

### 5. Budget Cut Recommendation
Total marketing spend across all platforms is **$503,506**. A 20% cut requires 
saving **$100,701**. The recommendation is to cut the entire Email Marketing 
budget of **$24,461** — it delivers the lowest ROAS of all 6 platforms and was 
the only platform to record a monthly ROAS below 1.0 (December 2025: 0.67). 
Reallocating half of that budget to TikTok Ads is projected to generate 
**$298,000 in additional attributed revenue** based on current ROAS performance.

![Budget Recommendation Chart](screenshots/roas_analysis.png)

---

## Dashboard Preview
![Full Dashboard](screenshots/dashboard.png)

---

## Recommendations Summary
1. **Grow Electronics and Toys** — highest profit margins at 26.4% and 22.5%. 
   Protect and increase investment in these categories.
2. **Reduce Marketplace dependency** — $7,950 in platform fees makes this the 
   least profitable channel. Shift focus to Mobile App and Website which pay 
   zero platform fees.
3. **Cut Email Marketing** — lowest ROAS of all 6 platforms at 4.81 and a CPA 
   of $26.01. Reallocate the $24,461 budget to TikTok Ads which delivers a 24.02 
   ROAS at just $3.93 per acquisition.
