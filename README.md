# Big Data Analytics: marketing analytics for Pakistani brands

Course projects for **Big Data Analytics** at the University of Management and Technology (UMT), Lahore, by **Usama Hanif** (BS Artificial Intelligence).

Each project tackles a real marketing question for Pakistani brands and comes with its own repository, a live dashboard and a short report. The projects build on each other: customer sentiment from Project 1 drives the ad messaging in Project 2.

## Projects

| # | Project | Marketing question | Dashboard | Code |
|---|---|---|---|---|
| 1 | **Footwear brand sentiment analysis** (Borjan, Servis, Ndure) | What do customers really say about each brand, and what do they praise or complain about? | [Live dashboard](https://pk-footwear-sentiment-analysis-kuphdsqeabs38rt56yt7nm.streamlit.app/) | [Repository](https://github.com/usamahanif349/pk-footwear-sentiment-analysis) |
| 2 | **Digital ad budget optimizer** (Borjan, Servis, Ndure) | Where should each brand spend its next Rs. 1,000,000 on ads, who should it target, what should it say and when? | [Live dashboard](https://pk-footwear-budget-optimizer.streamlit.app/) | [Repository](https://github.com/usamahanif349/pk-footwear-budget-optimizer) |
| 3 | *Coming soon:* social audience and campaign intelligence | Which audience needs and content patterns are hidden in social media comments? | – | – |

## Project highlights

**1. Sentiment analysis**
- 881 real YouTube comments and Google Maps reviews in English, Roman Urdu and Urdu
- Brand scorecards and aspect analysis (price, quality, comfort, size, design, staff, delivery)
- Classic models compared with a multilingual transformer (XLM-R), plus a PySpark vs Pandas benchmark

**2. Ad budget optimizer**
- A marketing plan per brand: where to spend, who to target, what to say and when to push
- Ad copy in English and Roman Urdu, a 2027 campaign calendar, a goal planner and a downloadable pitch pack
- Tested against a known true optimum (99.8%+ of the best revenue), with limitations documented
- Pandas vs Hadoop MapReduce vs Spark benchmark on up to 100 million rows

## Tools

Python, Pandas, scikit-learn, Hugging Face Transformers, SciPy, PySpark, Hadoop Streaming, Plotly, Streamlit, Google Colab

## Contact

[LinkedIn](https://www.linkedin.com/in/usama-hanif-8956bb1b0)
