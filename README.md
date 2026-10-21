# 📡 Telco Brand Sentiment Sentinel

> **Live Application**: [https://bongamanzini.github.io/telco-sentiment-sentinel/](https://bongamanzini.github.io/telco-sentiment-sentinel/)

A real-time natural language processing (NLP) sentiment monitor and "Anger Index" engine tracking South African telecommunications providers (Rain, Telkom, Vodacom, MTN, Vumatel) across social media to detect infrastructure outages before official network operational centers (NOCs) broadcast acknowledgments.

---

## 🎯 The Informatics & Brand Reputation Angle

- **The Problem**: South African telecommunications operators and ISPs often fail to detect localised fiber cuts, 5G tower battery depletion during load shedding, and billing double-debits until thousands of angry customers flood support queues.
- **The Informatics Solution**:
  - Scrapes unstructured complaints from Twitter/X and review platforms.
  - Computes a domain-specific **Anger Index (0 to 100)** utilizing VADER sentiment scoring and South African telco fault lexicons (*"red light flashing"*, *"no signal"*, *"cut fibre"*).
  - Flags early-warning outage spikes before helpdesk channels get overwhelmed.

---

## 🛠️ Features

- **Live Anger Index Leaderboard**: Continuously ranks ISPs by customer dissatisfaction and outage risk.
- **Outage Cluster Detection**: Correlates geographic indicators (e.g. Sandton, Soweto, Randburg, Durban) with sudden spikes in network downtime tweets.
- **Interactive NLP Sandbox**: Allows typing or pasting any customer complaint to compute its Anger Index and severity classification.
- **Dual Deployment**: Python CLI processing engine + responsive GitHub Pages web dashboard.

---

## 💻 Tech Stack

- **NLP Engine**: Python 3, VADER, RegEx
- **Frontend**: HTML5, Vanilla JavaScript (ESNext), Tailwind CSS
- **Deployment**: GitHub Pages (Web) & Python CLI

---

## 🚀 Quick Start (Python CLI)

```bash
# Run NLP sentiment analysis
python3 telco_sentiment_analyzer.py
```

---

## 👨‍💻 Author

**Bonga Manzini**  
BSc Informatics – University of South Africa (UNISA)  
Portfolio: [https://bongamanzini.github.io/portfolio/](https://bongamanzini.github.io/portfolio/)
