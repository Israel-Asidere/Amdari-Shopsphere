# Exploratory Data Analysis for Shopshere Inc

## 🏢 About Shopshere
Shopshere is an online shopping platform operating across multiple markets, connecting customers with a wide range of products through a digital-first retail experience. Despite a growing customer base, Shopshere faces a core business problem: low conversion rates across several customer segments, meaning too many users browse or make a single purchase without returning or spending more. This analysis was commissioned to shine a light on the behaviour of each customer group, understand what is driving disengagement, and provide concrete segment-level recommendations to help Shopshere get more users buying more products, more often.

---

## 📌 Project Overview
This project performs an end-to-end exploratory data analysis on Shopshere's transaction data (385,314 records, 8 features, covering 2023–2024). The analysis covers data quality checks, distribution analysis, cohort retention tracking, and RFM-based customer segmentation using K-Means clustering. Four distinct customer segments were identified, each with a tailored set of conversion and retention strategies designed to move users up the value ladder.


---

## 📊 Key Findings

| Finding | Detail |
|---|---|
| Missing values | None, dataset passed all quality checks |
| Outliers | Present in both UnitPrice (right-skewed) and Quantity (both tails) |
| Top markets | US (4,372 customers) narrowly ahead of UK (4,359) |
| Retention after month 1 | ~25–30%, roughly 1 in 4 customers return |
| Improving cohorts | March and June 2024 cohorts show ~30% retention, suggesting recent efforts are gaining traction |
| Optimal clusters | 4 segments identified via elbow method |


<img width="393" height="271" alt="Image" src="https://github.com/user-attachments/assets/36948119-bef8-4e83-99ee-9f086cb2a3b0" />
> *Fig. 1 — Elbow Plot used to identify 4 segments.*


<img width="445" height="423" alt="Image" src="https://github.com/user-attachments/assets/c3def175-4af0-45fe-9a0d-17edde9569bf" />
> *Fig. 2 — Customer Segment Composition*

**Customer Segments (RFM-based K-Means):**
- 🟥 **V-VIPs** — highest spenders, most frequent and most recent purchasers
- 🟦 **VIPs** — high engagement and spend, slightly less active than V-VIPs
- 🟧 **Loyal Regulars** — consistent buyers with moderate frequency and spend
- 🟩 **At Risk / Lost** — low engagement, long gap since last purchase

---

## 💡 Actionable Insights and Recommendations

- **First 30 days are the highest-leverage window.** Most customers buy once and stop. A strong post-purchase re-engagement sequence in the first month is the single biggest conversion opportunity across all segments.
- **V-VIPs and VIPs need protecting, not converting.** Early access, personalised rewards, and exclusive membership tiers reduce churn in Shopshere's most profitable segment and keep average order value high.
- **One-time buyers are the primary drag on overall conversion.** Win-back campaigns with time-limited discounts or personalised product suggestions can reactivate a significant portion of this group.
- **Loyal Regulars have untapped upside.** Gamified loyalty programs, referral incentives, and subscription nudges can grow basket size and purchase frequency without heavy discounting.
- **At Risk and Lost customers require a reactivation-first approach.** "We miss you" campaigns, retargeting based on browsing history, and survey incentives to understand drop-off reasons should come before any upsell attempts.
- **Regional conversion gaps exist.** Learnings from high-performing markets like the US and UK should be systematically applied to underperforming regions to close the gap across Shopshere's full customer base.
