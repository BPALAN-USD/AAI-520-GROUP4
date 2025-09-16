# 📰 Financial News Bias Detector

## 📌 Scope
The **Financial News Bias Detector** is designed to identify overly bullish or bearish bias in financial news reporting and assess its accuracy relative to actual market outcomes.  
Biased reporting can mislead investors, amplify herd behavior, and create inefficiencies in financial markets.  

This project introduces an **agentic AI workflow** that:  
- Processes financial news articles from **NewsAPI** and **Kaggle datasets**  
- Applies **sentiment analysis** to classify news as bullish, bearish, or neutral  
- Compares sentiment with **stock price movements** (via Yahoo Finance)  
- Routes articles through specialized agents (bullish/bearish)  
- Uses an **evaluator–optimizer** framework to refine bias detection accuracy  
- Generates **bias-adjusted news summaries** highlighting potential exaggeration or misalignment  

Ultimately, the system helps investors cut through clickbait and biased reporting, offering a more balanced view of financial news.  

### 🔄 Workflow
1. **Fetch news articles** (NewsAPI, Kaggle)  
2. **Preprocess text & sentiment analysis**  
3. **Routing** → bullish news → bullish agent; bearish news → bearish agent  
4. **Compare sentiment vs. stock price movement** (Yahoo Finance)  
5. **Generate bias-adjusted summaries**  
6. **Evaluator–optimizer refinement** for accuracy tracking  

---

## 🚀 Features (To be added)
-   

---

## 🏗️ Architecture (To be detailed)
- Agents (bullish, bearish, evaluator–optimizer)  
- Data pipeline (NewsAPI, Kaggle, Yahoo Finance)  
- Model training & refinement  

---

## 📂 Datasets
- [NewsAPI](https://newsapi.org/)  
- [Kaggle Financial News datasets](https://www.kaggle.com/datasets)  
- [Yahoo Finance](https://finance.yahoo.com/)  


# Install dependencies
pip install -r requirements.txt
