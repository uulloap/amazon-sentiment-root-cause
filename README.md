# Amazon Marketplace: NLP Sentiment & Root-Cause Analysis

![Python](https://img.shields.io/badge/Language-Python-3776AB.svg)
![Topic](https://img.shields.io/badge/Domain-E--commerce-orange.svg)
![Method](https://img.shields.io/badge/Method-NLP_/_Sentiment_Analysis-green.svg)

## 📌 Project Overview
This project processes a massive dataset of **2.1 million Amazon reviews** to look beyond 1-star ratings and uncover the "why" behind customer dissatisfaction. By utilizing Natural Language Processing (NLP), the pipeline extracts granular descriptors and categorizes negative feedback into actionable operational buckets.

## 📊 Business Problem
Star ratings are lagging indicators. To maintain a competitive edge, Amazon stakeholders need to identify whether dissatisfaction stems from product quality (Factory), logistics (Shipping/Handling), or service (Returns/Refunds).



## 🛠️ Technical Stack
- **Language:** Python
- **Libraries:** `NLTK`, `VADER (SentimentIntensityAnalyzer)`, `Pandas`, `Matplotlib`, `WordCloud`
- **Techniques:** Tokenization, Stop-word removal, Part-of-Speech (POS) Tagging, Keyword-based Issue Classification.

## 🚀 Key Features
- **Big Data Processing:** Efficiently handled 2M+ records using a modular, class-based Python pipeline.
- **Level-B Sentiment Analysis:** Isolated adjectives through POS tagging to identify specific descriptors (e.g., "flimsy", "malfunctioned") driving low scores.
- **Root-Cause Classification:** Engineered a logic-based engine to bucket reviews into: **Factory Defects, Shipping Issues, Handling Damage, and Refund/Return hurdles.**
- **Visual Analytics:** Generated category-specific Word Clouds and sentiment heatmaps to highlight post-2014 satisfaction trends.

## 📈 Key Insights & Results
- **Category Risk:** Identified **Video, Books, and Office Products** as having the highest disproportionate rates of factory-related defects.
- **Trend Discovery:** Detected an "emerging neutrality" trend since 2014, suggesting a growing gap between product descriptions and customer expectations.
- **Operational Impact:** Mapped specific keywords to shipping delays, providing a roadmap for regional logistics optimization.



## 📂 Project Structure
```text
├── data/               # Data dictionary and schema information
├── src/                # AmazonFullPipeline Python scripts
├── output/             # Word clouds and sentiment distribution plots
├── Final_Report.pdf    # Executive summary and strategic recommendations
└── README.md           # Project documentation
