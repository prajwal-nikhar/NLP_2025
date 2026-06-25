# AirPods Pro 2 — Sentiment Analysis & Customer Intelligence

**Group 14:** Giridhar Sharma · Prajwal Vijay Nikhar · Ritik Tibrewal · Rohan Jain

A comprehensive Big Data study evaluating 8,300 customer reviews using NLP techniques to identify product strengths, weaknesses, and actionable business strategies.

---

## Project Overview

| Attribute | Details |
|-----------|---------|
| Dataset | 8,300 customer reviews |
| Features | Rating, review text, verified purchase status, likes/dislikes metadata |
| Sentiment Split | Positive: 7,500 · Negative: 635 · Neutral: 165 |
| Pipeline | Data Cleaning → EDA → Sentiment Classification → LDA Topic Modeling → K-Means Clustering |

---

## Methodology

- **Data Cleaning:** Preprocessing raw review text for NLP tasks
- **EDA:** Exploratory analysis of rating distributions and review patterns
- **Sentiment Classification:** Labeling reviews as positive, negative, or neutral
- **LDA Topic Modeling:** Discovering latent themes across the review corpus
- **K-Means Clustering:** Grouping reviews by behavioral and sentiment patterns

---

## Key Feature Insights

| Feature | Customer Feedback |
|---------|------------------|
| Noise Control | Highly praised for ANC quality and Transparency mode clarity |
| Hearing Aid Mode | Described as life-changing for users with hearing loss; some firmware-related issues reported |
| Audio Quality | Deep bass and clear sound noted — suitable for music production |
| Design & Fit | Comfortable for most via Fit Test; small controls difficult for users with dexterity issues |

---

## Critical Observations

**Counterfeit Concerns**
- Significant cluster of 1-star reviews reporting fake or refurbished units from third-party sellers
- Users noted mismatched serial numbers between device and packaging

**Logistics & Fulfillment Issues**
- Multiple low ratings attributed to delivery problems: empty boxes, tampered packaging, poor customer service resolution
- Primarily linked to Walmart fulfillment channel

**Technical Glitches**
- Reported issues: audio pops, connectivity drops, occasional unreliability in USB-C variant vs previous Lightning model

---

## Tech Stack

`Python` `Pandas` `NLTK` `SpaCy` `Scikit-Learn` `Gensim (LDA)` `BERTopic` `Matplotlib` `Seaborn` `WordCloud`
