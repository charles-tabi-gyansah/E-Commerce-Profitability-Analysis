# E-Commerce Profitability Analysis — BrightCart

## Project Overview
A complete end-to-end profitability analysis for BrightCart, a direct-to-consumer 
e-commerce brand generating **$236,318 in net revenue** across 8 product categories 
and 4 sales channels over 2 years (2024–2025). The goal was to identify which 
categories and channels are truly profitable after accounting for all costs, and 
which marketing platforms deliver the best return on ad spend.

**Total Profit: $56,334 | Total Orders: 2,000 | Return Rate: 7.2%**

## Tools Used
- Microsoft Excel — Pivot Tables, Data Cleaning, Charts, Dashboard

## Dataset
The analysis is based on three datasets:

| Dataset | Description | Link |
|---|---|---|
| Orders | 2,000 order-level transactions (2024–2025) | [orders.csv](orders.csv) |
| Products | 207 products across 8 categories | [products.csv](products.csv) |
| Marketing Spend | 144 months of spend across 6 platforms | [marketing_spend.csv](marketing_spend.csv) |

---

## Key Questions Answered
1. Which product category is most and least profitable?
2. Which sales channel delivers the best profit per order?
3. What is the return rate by category and channel?
4. Which marketing platform delivers the best ROAS?
5. Where should the company cut 20% of its marketing budget?

---

## Key Findings

### 1. Category Profitability
Electronics is the most profitable category at **31.1% margin** generating 
**$13,973 in total profit** — the highest of all 8 categories. Books is the 
least profitable at **11.9% margin** — shipping costs of $6,263 eat up most 
of the revenue on low-priced items. Beauty also underperforms at 17.4% margin 
due to high shipping costs relative to selling prices.

| Category | Profit Margin |
|---|---|
| Electronics | 31.1% |
| Toys | 26.2% |
| Home & Kitchen | 25.4% |
| Food & Beverage | 24.8% |
| Sports | 23.5% |
| Clothing | 20.0% |
| Beauty | 17.4% |
| Books | 11.9% |
<img width="319" height="177" alt="Category Profitability" src="https://github.com/user-attachments/assets/8b35f561-7960-4fc9-9afc-09a656bbaf8c" />


---

### 2. Channel Analysis
Mobile App is the best performing sales channel at **29.8% margin** earning 
an average of **$36.32 profit per order**. Website comes second at **27.0% margin** 
and generates the highest total profit ($25,118) due to its high order volume 
(795 orders). Marketplace is the worst channel at **13.0% margin** — platform 
fees of **$7,950** heavily cut into what would otherwise be a healthy margin. 
Website and Mobile App pay zero platform fees which is why they significantly 
outperform Marketplace and Social Commerce.

| Channel | Profit Margin | Platform Fees |
|---|---|---|
| Mobile App | 29.8% | $0 |
| Website | 27.0% | $0 |
| Social Commerce | 15.4% | $1,945 |
| Marketplace | 13.0% | $7,950 |
<img width="362" height="215" alt="Channel Analysis" src="https://github.com/user-attachments/assets/daf831f9-61e3-4d5a-b023-496fc5ca9169" />


---

### 3. Return Rate Analysis
**144 out of 2,000 orders were returned** — a 7.2% overall return rate resulting 
in **$22,207 in lost revenue**. Electronics has the highest category return rate 
at **8.6%** ($4,305 lost) followed by Books at 8.4% and Clothing at 8.2%. 
Social Commerce has the worst channel return rate at **9.1%** — nearly 1 in 10 
Social Commerce orders gets sent back. Food & Beverage and Beauty have the 
lowest return rates at 5.7% and 5.9% respectively.

<img width="386" height="215" alt="Return Rate" src="https://github.com/user-attachments/assets/75bb7621-81f8-4f5f-b4ab-bff67cdaa7dc" />


---

### 4. Marketing ROAS Analysis
TikTok Ads delivers the highest ROAS at **24.44** and the lowest cost per 
acquisition at **$3.93**. Email Marketing is the worst performing platform with 
a ROAS of **5.41** and a CPA of **$26.01** — over 6x more expensive than TikTok. 
December 2025 was the only month in the entire dataset where ROAS dropped below 
1.0 to just **0.67**, meaning BrightCart spent **$1,797 and only received $1,199 
back** — a net loss on advertising.

| Platform | Avg ROAS | Avg CPA |
|---|---|---|
| TikTok Ads | 24.44 | $3.93 |
| Influencer | 23.45 | $4.80 |
| Instagram Ads | 16.99 | $5.55 |
| Google Ads | 13.69 | $6.48 |
| Facebook Ads | 11.25 | $8.38 |
| Email Marketing | 5.41 | $26.01 |
<img width="357" height="215" alt="ROAS analysis" src="https://github.com/user-attachments/assets/384b20a5-5e34-42c9-bd2f-158c1765cd3a" />


---

### 5. Budget Cut Recommendation
Total marketing spend is **$503,506**. A 20% cut requires saving **$100,701**. 
The recommendation is to cut the entire Email Marketing budget of **$24,461** — 
it delivers the lowest ROAS of all 6 platforms at 5.41 and was the only platform 
to record a monthly ROAS below 1.0 (December 2025: 0.67). Reallocating half of 
that budget to TikTok Ads is projected to generate **$298,000 in additional 
attributed revenue** based on current ROAS performance.


---

## Dashboard Preview
<img width="554" height="386" alt="BrightCart Analysis Screenshot" src="https://github.com/user-attachments/assets/1212e011-c598-47e8-a5ef-06585dc02298" />


---

## Recommendations Summary
1. **Grow Electronics and Toys** — highest profit margins at 31.1% and 26.2%. 
   Protect and increase investment in these categories.
2. **Reduce Marketplace dependency** — $7,950 in platform fees makes this the 
   least profitable channel at 13.0% margin. Shift focus to Mobile App (29.8%) 
   and Website (27.0%) which pay zero platform fees.
3. **Cut Email Marketing** — lowest ROAS of all 6 platforms at 5.41 and a CPA 
   of $26.01. Reallocate the $24,461 budget to TikTok Ads which delivers a 24.44 
   ROAS at just $3.93 per acquisition — saving costs while projecting $298,000 
   in additional revenue.
