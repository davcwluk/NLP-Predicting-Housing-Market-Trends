# NLP-Predicting-Housing-Market-Trends

Overview
This dissertation, awarded a distinction grade as part of the MSc Data Analytics program at the University of Warwick, explores the application of Natural Language Processing (NLP) techniques for predicting housing market trends in Hong Kong and the United Kingdom. It integrates quantitative economic indicators with qualitative textual data to enhance traditional forecasting methods.

Objectives
The project addresses key research questions:
1. How does the accuracy of NLP models compare with traditional forecasting methods?
2. What are the performances of NLP models like SARIMAX, LSTM, BERT, and Lag-Llama for housing market analysis?
3. How do these models adapt to differing market conditions, such as the volatile Hong Kong market versus the stable UK market?

Models and Techniques
The dissertation employs:
- Quantitative Model: SARIMAX for baseline forecasting.
- Hybrid Models: Combining SARIMAX with NLP models.
- NLP Models:
  LSTM: Captures long-term dependencies in text data.
  FinBERT: A pre-trained BERT model fine-tuned for financial sentiment analysis.
  Lag-Llama: A probabilistic forecasting model for time series analysis using LLMs.

Key Results
- Hybrid models outperformed traditional SARIMAX, with significant error reduction across metrics (MAE, MSE, RMSE).
- NLP-enhanced models demonstrated higher adaptability in volatile markets like Hong Kong.
- Lag-Llama showcased advanced probabilistic forecasting capabilities, incorporating uncertainties effectively.

Data Sources
- Quantitative Data: GDP, housing price index, interest rates, and unemployment rates from official government and reputable sources.
- Qualitative Data: Market reports, social media, and forums, processed for sentiment analysis.

Tools and Technologies
- Programming Languages: Python
- Libraries: TensorFlow, PyTorch, NLTK, GluonTS
- Frameworks: Hugging Face for FinBERT, GluonTS for Lag-Llama
