# OTT Industry Strategic Analysis  
## Comparative Study of Netflix, Prime Video, Hulu, and Disney+ Hotstar

---

## Project Overview

This project performs a comparative data analysis of the OTT streaming ecosystem by integrating:

- Content library data (titles, genres, release years, country, content type)
- Subscriber growth data
- Financial metrics (Revenue, Profit, ARPU)

The objective is to evaluate how content strategy, pricing, and competitive positioning influence subscriber growth and monetization performance across major streaming platforms.

---

## Business Questions

1. How does annual content release volume affect subscriber growth?
2. Do ARPU changes correlate with content expansion or contraction?
3. What content categories increase when Netflix experiences performance decline?
4. How do Prime Video, Hulu, and Disney+ Hotstar differentiate their content strategies?
5. Is content quantity linked to monetization efficiency?

---

## Datasets Used

### Content Datasets
- Netflix Titles Dataset
- Amazon Prime Titles Dataset
- Hulu Titles Dataset
- Disney+ Hotstar Titles Dataset

Key fields analyzed:
- `title`
- `listed_in` / genre
- `release_year`
- `country`
- `type` (Movie / TV Show)

### Financial and Growth Data
- Annual Subscriber Count
- Revenue
- Profit
- ARPU (Average Revenue Per User)

---

## Data Preparation

The following preprocessing steps were performed:

- Standardization of column names across datasets
- Normalization of `release_year`
- Addition of `provider` labels for each platform
- Handling of missing values
- Concatenation of datasets for cross-platform comparison
- Aggregation of yearly release counts
- Calculation of ARPU growth using percentage change

---

## Analyses Conducted

### 1. Content Library Comparison
- Total titles per platform
- Distribution of Movies vs TV Shows
- Genre distribution comparison
- Country-level production analysis

### 2. Yearly Content Release Trends
- Annual release count per platform
- Platform growth acceleration periods
- Competitive timing comparison

### 3. Subscriber and ARPU Analysis
- Subscriber growth trends
- ARPU growth rate calculation
- Identification of Netflix decline years
- Competitor performance during Netflix downturn periods

### 4. Correlation and Relationship Analysis
- Release volume vs ARPU correlation
- ARPU vs subscriber growth correlation
- Platform-wise financial sensitivity to content expansion

---

## Key Insights

- Netflix and Prime Video maintain the largest content libraries.
- Netflix is relatively TV-heavy, while Prime Video exhibits a more balanced distribution.
- ARPU growth does not consistently move in direct proportion to content volume.
- During Netflix slowdown periods, competitors increased release volumes in select genres.
- Content strategies vary significantly based on competitive positioning and market focus.

---

## Business Implications

- Content expansion alone does not guarantee monetization improvement.
- Genre diversification may enhance competitive stability.
- Competitor expansion during market leader decline may capture incremental demand.
- Pricing strategy must align with perceived content value.

---

## Visualizations Included

- Content library comparison charts
- Genre distribution analysis
- Country-wise production analysis
- Dual-axis charts (Subscribers vs Release Volume)
- ARPU growth trend analysis
- Correlation heatmaps
---

## Limitations

- No user-level engagement data included
- Financial data aggregated annually (no quarterly granularity)
- Correlation does not imply causation
- No lag-based time series modeling implemented

---

## Future Improvements

- Lag-based regression modeling
- Engagement-weighted content performance scoring
- Churn prediction modeling
- Cohort retention analysis
- Interactive dashboard deployment (Streamlit or Power BI)

