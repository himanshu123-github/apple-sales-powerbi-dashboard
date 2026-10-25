# Insights & Recommendations Report
**Apple Sales Performance Dashboard · 2022–2025 · USD**
Prepared by Himanshu · Data Analyst / BI Analyst portfolio project

*All figures come from the Power BI dashboard built on a synthetic dataset modelled on Apple's product lines.*

---

## 1. Executive Summary

![Overview page](screenshots/01_overview.png)

The business generated **$14.6M in revenue** and **$5.5M in profit** (37.6% margin) from **14,000 orders** and 22,141 units. iPhone is the engine, bringing in half of all revenue. Revenue follows a strong seasonal pattern with a peak every December, and discounts are the main drag on profitability: margin falls from 40.9% to 30.6% as discounts rise from 0% to 15%.

| KPI | Value |
|---|---|
| Total revenue | $14.6M |
| Total profit | $5.5M |
| Profit margin | 37.6% |
| Total orders | 14,000 |
| Units sold | 22,141 |
| Average order value | $1,046 |
| Online revenue share | 30.0% |
| Average discount | 4.7% (about $0.82M in total) |
| Average rating | 4.14 / 5 |

---

## 2. Product Insights

![Product Analysis page](screenshots/02_product_analysis.png)

| Category | Revenue | Units | Margin |
|---|---|---|---|
| iPhone | $7,327,642 (50.1%) | 8,818 | 39.8% |
| Mac | $3,889,641 (26.6%) | 3,416 | 30.8% |
| Wearables, Home & Accessories | $1,771,372 (12.1%) | 4,979 | 44.0% |
| iPad | $1,357,120 (9.3%) | 2,407 | 29.0% |
| Services | $292,362 (2.0%) | 2,521 | 75.1% |

**Findings**
1. **iPhone is half the business.** It earns $7.33M at a healthy 39.8% margin. Concentration this high is also a risk.
2. **Services is the margin leader.** At 75.1% margin it earns about twice the company average, but it is only 2% of revenue.
3. **Mac and iPad are the weakest on margin** (30.8% and 29.0%), below the 37.6% company average.
4. **Wearables outperform on margin** (44.0%) and sell about 1.5 times as many units as Mac (4,979 vs 3,416).
5. **Top 10 products:** iPhone 13 ($1.40M), iPhone 14 Pro ($1.29M), iPhone 14 ($1.13M), iPhone 15 Pro ($1.11M), MacBook Pro 14 ($1.07M), iPhone 15 ($0.90M), iPhone 16 Pro ($0.85M), MacBook Air M3 ($0.70M), iMac 24 ($0.69M) and MacBook Air M2 ($0.68M). Six of the ten are iPhones and three are MacBooks.
6. **Older products lead partly because of time on sale.** iPhone 13 ranks first largely because it was on sale for the whole 2022–2025 period, whereas the iPhone 16 Pro had only about a year. Compare revenue per month on sale before judging a model's popularity.

---

## 3. Time Trends

1. **Revenue peaks every December.** The line chart shows a sharp spike each Q4, followed by a drop in January.
2. **September bump:** iPhone launches in September lift revenue ahead of the holiday peak.
3. **Steady growth:** each December peak is higher than the last, and December 2025 is the highest month, above $0.6M.
4. **YoY growth:** revenue grew 7.1% in 2023, 15.1% in 2024 and 9.8% in 2025, from $3.14M in 2022 to $4.26M in 2025.
5. **Launch-year view:** products launched in 2022 ($4.5M) and 2021 ($3.9M) generate the most revenue, followed by 2023 ($3.3M) and 2024 ($2.2M). 2020 launches bring in $0.7M.

---

## 4. Regional & Channel Insights

![Regional and Channel page](screenshots/03_regional_channel.png)

1. **Americas is the largest region** ($5.1M), followed by Europe ($3.4M), Greater China ($2.6M), Rest of Asia Pacific ($2.3M) and Japan ($1.0M). Middle East is the smallest ($0.2M, a single store).
2. **Channel mix (store-type donut on the Overview page):** Apple Stores bring in 64.55% of revenue, Online Stores 29.99% and Authorized Resellers 5.46%.
3. **Country leaders:** United States ($3.20M), China ($2.09M), Canada ($1.50M), United Kingdom ($1.33M) and India ($1.30M). India outsells Germany ($1.13M), Japan ($0.99M), France ($0.59M) and Italy ($0.36M).
   **Margin by country:** India has the best margin (44.3%), followed by Italy (41.0%) and the UK (40.7%). Japan has the lowest (34.7%).
4. **Top 10 cities are close together** ($0.54M–$0.64M each: Shanghai, Beijing, New York, Austin, Toronto, Chicago, Paris, Berlin, Munich, San Francisco), so no single city dominates.
5. **Payment methods:** Apple Pay leads with 34.7% of revenue, then Credit Card (29.7%), Debit Card (15.2%), Financing (12.5%) and UPI/Wallet (7.9%).

---

## 4b. Discount & Customer Insights

![Discount and Customer page](screenshots/04_discount_customer.png)

| Customer segment | Average discount |
|---|---|
| Consumer | 3.0% |
| Business | 8.1% |
| Education | 11.0% |

| Discount level | Profit margin |
|---|---|
| 0% | 40.9% |
| 5% | 37.9% |
| 10% | 34.2% |
| 15% | 30.6% |

1. **Every extra 5 points of discount costs about 3 points of margin.**
2. **Education and Business get the largest discounts**, so they are where margin leaks most.
3. **Discounts total about $0.82M**, roughly 5% on top of the $14.6M revenue, equal to about 15% of the $5.5M profit.
4. **Ratings are flat (about 4.1 in every category).** Rating does not explain revenue or margin differences in this data.
5. **iPhone sales in the Americas ($2.53M) skew to Consumer** ($1.57M) over Business ($0.76M) and Education ($0.20M), based on the decomposition tree.

---

## 5. Recommendations

| # | Recommendation | Evidence |
|---|---|---|
| 1 | **Cap discounts at 10% for Education and Business** unless volume justifies more | Margin falls from 40.9% to 30.6% between 0% and 15% discount |
| 2 | **Push Services attach rates** (AppleCare+, iCloud+) at checkout | 75.1% margin but only 2% of revenue |
| 3 | **Plan stock and marketing for September and Q4** | December peaks each year, with a September launch bump |
| 4 | **Reduce dependence on iPhone** by growing Wearables | iPhone is 50% of revenue; Wearables has 44% margin |
| 5 | **Review Mac and iPad pricing or costs** | Margins of 30.8% and 29.0% are below the 37.6% average |
| 6 | **Expand online presence where retail is thin** | Online brings 30% of revenue; Middle East has only one store |

---

## 6. Limitations

- The data is synthetic, so seasonality and discount effects were built in. Treat the findings as a demonstration of the analytical method.
- YoY growth starts in 2023 because the data begins in January 2022.
- Ratings were generated randomly, which is why they look flat.
- All prices are in USD with no currency conversion.
