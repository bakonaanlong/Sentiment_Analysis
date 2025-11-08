# Sentiment_Analysis
Interact with the dashboard here - https://lookerstudio.google.com/s/rodCmGIaGOw

---

## 1. Background and Overview  

### Purpose  
This Sentiment Analysis Dashboard provides a comprehensive view of user perceptions across multiple digital platforms. It aggregates and visualizes sentiment data from social media interactions to enable data-driven decision-making in customer experience, marketing, and product strategy.

### Scope  
- **Time Frame**:2011 - 2023 + Full calendar year (12 months), with monthly, daily, and hourly granularity  
- **Platforms Tracked**: Instagram, Facebook, Twitter (X)  
- **Sentiment Categories**: Positive, Negative, Neutral  
- **Total Data Points Analyzed**: 499 user sentiments  

### Key Objectives  
1. Measure overall sentiment health  
2. Identify trends over time (monthly and daily)  
3. Pinpoint platform-specific performance  
4. Detect peak engagement periods by time of day  
5. Inform proactive customer engagement and reputation management  

---

## 2. Data Structure Overview  

| **Component**                     | **Description**                                                                 | **Value / Format**       |
|-----------------------------------|---------------------------------------------------------------------------------|--------------------------|
| **Total Sentiments**              | Aggregate count of all classified user comments/mentions                        | 499                      |
| **Positive Sentiments**           | Number of sentiments classified as favorable                                    | 166 (33.3%)              |
| **Negative Sentiments**           | Number of sentiments classified as unfavorable                                  | 134 (26.9%)              |
| **Neutral Sentiments**            | Number of sentiments with no strong polarity                                    | 199 (39.9%)              |
| **Sentiment Distribution by Platform** | Ranked by volume of mentions                                              | 1. Instagram: 171  <br>2. Facebook: 165  <br>3. Twitter: 91  <br>4. Twitter: 68  <br>5. Facebook: 4 |
| **Monthly Sentiment Trend**       | Line chart showing sentiment volume over 12 months                              | X-axis: Months (Aug–Jul) <br>Y-axis: Sentiment count |
| **Time-of-Day Distribution**      | Bar chart showing sentiment volume by time segment                              | Morning, Noon, Night     |

> **Note**: Duplicate entries for Twitter and Facebook in platform ranking suggest either data duplication or multi-campaign tagging. Requires validation.

---

## 3. Executive Summary  

- **Overall Sentiment Balance**: **39.9% Neutral**, **33.3% Positive**, **26.9% Negative**  
- **Sentiment Ratio**: **1.24:1** (Positive to Negative) — moderately favorable  
- **Dominant Platform**: **Instagram** leads with **171 sentiments**, followed closely by **Facebook (165)**  
- **Peak Engagement Month**: **August** — highest volume across all sentiment types  
- **Time-of-Day Insight**: **Noon** records the highest sentiment volume, followed by **Night**  
- **Trend Observation**: Positive sentiment peaks early in the year, declines mid-year, and stabilizes  

> **Verdict**: Sentiment is **stable but not strongly positive**. Opportunities exist to convert neutral and negative feedback into advocacy.

---

## 4. Insights Deep Dive  

![yeah yeah](https://github.com/bakonaanlong/Sentiment_Analysis/blob/main/sentiment.PNG)

### 4.1 Monthly Sentiment Trends  
- **August** shows a sharp spike in **all three sentiment types**, especially **Positive (17)** and **Neutral (20)**  
- **Positive sentiment** declines steadily from August through December, then fluctuates mildly  
- **Negative sentiment** remains relatively consistent, with minor peaks in **March** and **July**  
- **Neutral sentiment** dominates volume throughout the year, indicating **low emotional intensity** in user feedback  

### 4.2 Platform Performance  
| Platform  | Total Mentions | % of Total | Insight |
|----------|----------------|------------|-------|
| Instagram | 171            | 34.3%      | Highest reach; strong visual/content resonance |
| Facebook  | 165            | 33.1%      | High volume but fragmented (two entries suggest tagging inconsistency) |
| Twitter   | 159            | 31.9%      | Moderate engagement; possible under-monitoring |

> **Anomaly Alert**: Facebook appears twice (165 + 4) — likely due to campaign or channel misclassification.

### 4.3 Time-of-Day Behavior  
- **Noon (12:00–14:59)**: Peak sentiment volume (~75–80 sentiments)  
- **Night (18:00–23:59)**: Second-highest (~60 sentiments)  
- **Morning (06:00–11:59)**: Lowest activity (~50 sentiments)  

> **Implication**: Users are most vocal during lunch and post-work hours which ideal windows for response and engagement.

---

## 5. Recommendations  

### Immediate Actions (0–30 Days)  
1. **Resolve Data Duplication**: Audit and merge duplicate platform entries (Facebook, Twitter)  
2. **August Campaign Review**: Analyze content/events driving August spike for replication  
3. **Noon-Time Response Protocol**: Deploy real-time monitoring and response team during 12:00–15:00  

### Mid-Term Strategies (1–3 Months)  
4. **Neutral-to-Positive Conversion Program**:  
   - Identify top neutral themes via keyword clustering  
   - Launch targeted re-engagement campaigns (e.g., polls, tutorials, incentives)  
5. **Platform Prioritization**:  
   - Allocate 40% of social budget to **Instagram**  
   - Standardize tagging to eliminate Facebook/Twitter duplicates  

### Long-Term Initiatives (3–12 Months)  
6. **Sentiment Early Warning System**:  
   - Set thresholds: Alert if Negative > 35% or Positive < 25% in any month  
7. **Seasonal Sentiment Forecasting Model**:  
   - Use August–December trends to predict Q1/Q2 sentiment waves  
8. **Cross-Platform Sentiment Benchmarking**:  
   - Establish quarterly KPIs: Aim for **40% Positive**, **<20% Negative**  

---


