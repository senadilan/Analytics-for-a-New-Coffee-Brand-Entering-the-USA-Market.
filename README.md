# ☕ U.S. Coffee Market Entry Analysis

## Overview
This project builds a data-driven model to identify the best U.S. cities for opening a premium coffee shop.

It combines:
- Demographics (Census)
- Competition (NAICS)
- Consumer behavior (Yelp)

---

##  Research Question
Which U.S. cities have:
- High demand
- Strong purchasing power
- Manageable competition?

---

## 
Methodology

### Demand Index
- Income (40%)
- Population (30%)
- Yelp activity (30%)

### Competition Index
- Café density (70%)
- Price/quality proxy (30%)

### Opportunity Score
Opportunity = D - 0.6 * C

---

##  Key Insights
- Income is the strongest driver
- High competition reduces opportunity
- High engagement markets are more attractive

---

##  Machine Learning
- K-Means Clustering
- k = 4 (business-driven choice)
- Segmented cities into market types

---

##  Results
Top cities include:
- San Francisco
- Los Angeles
- San Jose

---

##  Authors
- Musa Yüksel
- Sena Dilan Çakır
