# Luxury Retail Customer Insights: Social & Sentiment Analytics

This project analyses social media engagement and customer sentiment data to generate actionable customer and brand insights for luxury retail.

Using Harrods as the focus brand and Selfridges as a key competitor, the analysis translates social and review data into clear recommendations for customer engagement, brand positioning, and content strategy.

---

## Business Problem

Luxury retailers invest heavily in social and digital channels but often struggle to understand:
- Why engagement declines despite high brand awareness
- How their performance compares to key competitors
- Which customer experience factors most influence sentiment and perception

The objective of this project was to diagnose engagement performance, identify sentiment drivers, and provide data-backed recommendations to improve customer engagement and brand impact.

---

## Data & Features

The analysis combines multiple data sources:

- **Social media performance metrics**
  - Engagement per post
  - Applause, conversation, and amplification
  - Posting frequency across platforms

- **Customer review data**
  - Trustpilot reviews (Harrods)
  - Textual feedback for sentiment and trend analysis

- **Comparative benchmarks**
  - Cross-channel comparison with Selfridges

---

## Analytical Approach

A structured customer analytics workflow was applied:

### 1. KPI & Competitive Analysis
- Cross-channel engagement comparison (Harrods vs Selfridges)
- Platform-level analysis of applause, conversation, and amplification
- Posting frequency vs engagement diagnosis

### 2. Trend & Performance Analysis
- Identification of engagement decline patterns
- Diagnosis of underperformance drivers beyond volume metrics

### 3. Sentiment & Text Analytics
- Review text cleaning and preprocessing
- Sentiment scoring and polarity analysis
- Trend extraction to surface recurring customer themes

---

## Key Insights

- Harrods significantly outperformed Selfridges in total audience size but underperformed on **engagement per post**, indicating inefficient content performance.
- Engagement decline aligned with **reduced posting frequency**, suggesting visibility and consistency issues rather than brand fatigue.
- Sentiment analysis revealed strong positive perception around brand prestige, but recurring negative themes around **service experience and value perception**.
- Competitor benchmarking showed Selfridges achieving higher engagement efficiency despite a smaller audience base.

Supporting visuals:
- Cross-channel engagement comparison
- Posting frequency vs engagement diagnosis
- Sentiment and coefficient plots (see `/visuals`)

---

## Business Implications

- Engagement performance should be evaluated on **efficiency (engagement per post)** rather than reach alone.
- Content strategy should prioritise consistency and platform-specific optimisation.
- Customer experience pain points identified through sentiment analysis should inform service and communication priorities.
- Competitive benchmarking enables realistic performance targets rather than vanity metrics.

The insights directly support customer analytics, brand strategy, and marketing optimisation decisions.

---

## How to Navigate This Repository

- **README.md** → Business context, insights, and recommendations  
- **visuals/** → Key charts used for diagnosis and decision-making  
- **code/** → R scripts for sentiment analysis and trend modelling  
- **data/** → Cleaned, analysis-ready datasets  

---

## Tools & Techniques

- **R**: data cleaning, sentiment analysis, regression and trend analysis  
- **Text analytics**: sentiment scoring, theme identification  
- **Customer analytics**: KPI benchmarking, competitor analysis  
- **Visual analytics**: engagement diagnostics and insight communication
