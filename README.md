# Luxury Retail Customer Insights: Social Media & Sentiment Analytics

## Business Problem
Luxury retailers invest heavily in social media, but high follower counts do not always translate into meaningful engagement or positive brand perception.

This project analyses **Harrods’ social media performance** against **Selfridges** to:
- Diagnose engagement decline despite strong brand equity
- Identify gaps between passive and active engagement
- Extract customer sentiment and themes from verified reviews
- Translate insights into actionable content and CX recommendations

---

## Data & Scope
The analysis combines **platform performance data** and **customer-generated text data**:

- **Social media KPIs** (30-day window: 15 Feb – 16 Mar 2025)
  - Instagram, Facebook, TikTok
  - Engagement, posting frequency, follower growth, applause vs conversation
- **Customer reviews**
  - Verified Trustpilot reviews (Harrods)
  - Sentiment scores, polarity categories, topic prevalence

Competitor benchmark: **Selfridges**

---

## Analytical Approach

### 1. Social Media Performance Analysis
- Cross-channel KPI comparison
- Engagement per post vs posting frequency
- Applause (likes) vs conversation (comments) diagnostics
- Competitor benchmarking (Harrods vs Selfridges)
*Visual reference:*  
**Harrods vs Selfridges – Engagement & Conversation Comparison**  
*(visuals/harrods_vs_selfridges_engagement_per_post.png)* 

### 2. Sentiment & Text Analytics
- Context-aware sentiment scoring using R (`sentimentr`)
- Sentiment categorisation (Positive / Neutral / Negative)

Visual references:*  
- **Sentiment Score Distribution** *(visuals/sentiment_score_distribution.png)*  
- **Sentiment Category Breakdown** *(visuals/sentiment_category_split.png)

- Structural Topic Modelling (STM, K=8 topics)
- Topic–sentiment and topic–time relationships

*Visual references:*  
- **Topic Summary & Labels** *(visuals/topic_model_summary.png)*  
- **Sentiment vs Topic Effects** *(visuals/topic_vs_sentiment_effect_plot.png)*  
- **Topic Trends Over Time** *(visuals/topic_time_trend.png)*
---

## Key Insights

### Engagement Performance
- Harrods generated **~65,700 total engagements**, but this represented a **20.9% decline** versus the prior 30-day period.
- Despite lower posting volume, Harrods achieved **~1,530 engagements per post**, significantly higher than Selfridges (**~96 engagements per post**).
- Harrods dominated **passive engagement**:
  - **~63,500 applause interactions (likes/favourites)**
- Selfridges outperformed in **active engagement**:
  - **+52.9% increase in comments**, while Harrods comments declined **21.7%**

**Interpretation:**  
Harrods maintains strong brand affinity but underperforms in conversation-driven engagement.

---

### Content Strategy Gap
- Harrods posting frequency declined **10.4%** during the analysis period.
- Engagement decline coincided with reduced posting and limited interactive formats.
- Selfridges posted more frequently and adopted trend-led formats, particularly on TikTok, where it held **~166K followers vs Harrods’ ~19.9K**.

---

### Sentiment Analysis
- Trustpilot sentiment distribution showed:
  - **Majority positive sentiment**, aligning with Harrods’ **4-star average rating**
  - Smaller but persistent negative cluster
- **Topic modelling revealed:**
  - Negative sentiment strongly associated with **pricing, service delays, and payment issues**
  - Positive sentiment driven by **staff quality, ease of shopping, and overall experience**
- Complaint-related topics showed **declining prevalence over time**, indicating partial resolution but not elimination.

---

## Business Implications

- **Engagement strategy:**  
  Harrods should prioritise **conversation-led formats** (polls, Q&A, UGC prompts) to convert passive admiration into interaction.
  
- **Channel strategy:**  
  TikTok represents a clear competitive gap; increasing posting cadence and UGC activation is critical to reach younger luxury consumers.

- **Customer experience:**  
  Sentiment and topic analysis highlight **pricing transparency and service efficiency** as the highest-risk perception drivers.

- **Measurement maturity:**  
  Combining KPI diagnostics with sentiment analytics provides a fuller view than engagement metrics alone.

---

## Tools & Techniques
- **R:** sentimentr, ggplot2, stm
- **Analytics methods:** KPI benchmarking, sentiment analysis, topic modelling
- **Text analytics:** tokenisation, polarity scoring, topic prevalence
- **Business frameworks:** SWOT-informed recommendations, KPI diagnostics

---

## How to Navigate
- `README.md` → business context, insights, decisions
- `code/` → sentiment analysis & topic modelling scripts (R)
- `visuals/` → engagement diagnostics, sentiment distributions, topic outputs
- `data/` → cleaned Trustpilot review dataset
