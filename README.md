# 📊 Earnings Call Sentiment vs Market Reaction

Understanding how management tone influences market behaviour — this project analyzes earnings call transcripts using NLP to evaluate whether sentiment signals can explain short-term stock price movements.

---

## 🚨 The Problem

Earnings calls contain rich qualitative signals, but translating this unstructured narrative into actionable insights is challenging. Traditional analysis often overlooks how subtle shifts in tone, optimism, or caution influence investor perception.

This creates a gap where:
- valuable sentiment signals remain underutilized  
- decision-making relies heavily on quantitative metrics alone  
- the link between narrative and market reaction remains unclear  

---

## 💡 The Solution

This project applies a dual-model sentiment analysis approach to extract and evaluate narrative signals from earnings calls. A finance-specific model (FinBERT) is compared with a large language model (DeepSeek) to understand how different approaches interpret tone.

By combining model outputs with human-annotated data and aligning sentiment trends with market movements, the analysis provides a structured way to interpret qualitative financial communication.

---

## 📊 Business Impact

The findings highlight that sentiment can enhance decision-making when used alongside traditional financial indicators. While it does not directly predict stock movement, it offers valuable context around market expectations, guidance, and investor sentiment.

This enables:
- better interpretation of earnings narratives  
- improved investment and risk assessment  
- stronger decision-support systems for financial analysis  

---

## 🛠️ How it was done

The project uses earnings call transcripts from Apple, Amazon, and NVIDIA, analyzed at a paragraph level to capture contextual meaning. Over 700 samples were manually annotated to create a reliable benchmark.

Sentiment was extracted using FinBERT and DeepSeek, and evaluated using accuracy, macro-F1, and confusion matrices. An event study approach (±2 days) was then used to compare sentiment trends with stock price movements, supported by market data from yFinance.

---

## 📄 Full Case Study

👉 [View Report](./ResearchProjectReport.pdf)
