# SQL Analysis Portfolio

A collection of SQL projects exploring customer conversion, marketing attribution, and subscription churn. These analyses demonstrate how SQL can help answer business questions about customer acquisition, purchasing behavior, and retention.

## Projects

### 1. Funnel Analysis

Explore how users move from a quiz to a home try-on and purchase.

- Count participants at each survey stage.
- Calculate conversion rates between funnel stages.
- Compare purchase conversion for three-pair and five-pair try-ons.
- Analyze revenue by product, style, model, and color.

**Tables:** `survey`, `quiz`, `home_try_on`, `purchase`

### 2. Marketing Attribution

Explore which marketing sources and campaigns appear at different points in the customer journey.

- Identify each user's first and last recorded visits.
- Attribute purchase-page visits to sources and campaigns.
- Compare campaign counts under different attribution approaches.
- Explore traffic sources, campaigns, and page activity.

**Table:** `page_visits`

### 3. User Churn Analysis

Examine subscription cancellations overall and by customer segment.

- Explore subscription dates and segment sizes.
- Identify active and canceled subscriptions for each month.
- Calculate monthly churn rates for January–March 2017.
- Compare churn across customer segments.

**Table:** `subscriptions`

## SQL Skills

- **Joins:** `JOIN`, `LEFT JOIN`, and `CROSS JOIN`
- **Query organization:** Common table expressions (CTEs)
- **Aggregations:** `COUNT`, `SUM`, `MIN`, and `MAX`
- **Conditional logic:** `CASE` statements and null handling
- **Data analysis:** Grouping, filtering, date comparisons, and ratio calculations

## Files

- `SQL_Funnel_Analyse.txt` — Funnel conversion and product revenue queries.
- `SQL_Marketing_Attribution` — First-touch, last-touch, and purchase attribution queries.
- `SQL_User_Churn_Analyse` — Monthly and segment-level churn queries.
- `Churnrate Projekt.pptx` — Accompanying churn analysis presentation.

## Purpose

Practice translating business questions into SQL queries and exploring metrics across the customer journey.
