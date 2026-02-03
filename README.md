# stock-market-news-sentiment-analysis
Stock Market Sentiment Analysis using NLP and machine learning to extract sentiment from financial news as a risk and decision support signal. Compared Word2Vec and Sentence Transformer embeddings with RF and NN models using a time based split. Sentence Transformer + NN achieved best test F1 ~0.75 with stable generalization for ERM use cases.

## Objective
Use AI to extract market sentiment from stock related news to support investment and risk monitoring decisions.

## Data
Historical financial news articles linked to a NASDAQ listed company, labeled as Positive, Neutral, or Negative sentiment.

## Method
Compared Word2Vec and Sentence Transformer embeddings with Random Forest and Neural Network classifiers. Used a time based 80/20 split and F1 score to address class imbalance and prevent lookahead bias.

## Results
Sentence Transformer + Neural Network achieved the strongest out of sample performance with F1 ~0.75 and stable generalization.

## Model Risk Considerations
Data bias, class imbalance, sentiment ambiguity, and potential model drift. Sentiment should be treated as a supporting signal, not a trading rule.

## ERM and Governance Use
Can be used as an early warning or contextual risk signal to augment analyst judgment, scenario analysis, and market risk monitoring.

## Next Steps
Fine tune sentence transformers, improve Neutral class detection, and aggregate sentiment signals to reduce noise.

## Quick links
- Notebook: [Open](notebooks/stock_sentiment_analysis.ipynb)
- Slides: [Open](Presentation Project_1_Stock Market Sentiment Analysis.pdf)

