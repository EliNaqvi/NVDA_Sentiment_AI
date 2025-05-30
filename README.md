#  NVDA Sentiment-Based Stock Movement Predictor

This project uses **OpenAI's GPT model** to analyze the sentiment of daily headlines and explore how it correlates with **NVIDIA (NVDA)** stock price changes. This information can be used to make informed decisions, and take trades accordingly. 

---

##  What It Does

-  Pulls 30 days of NVDA stock data from Yahoo Finance  
-  Analyzes simulated financial headlines using **GPT-4 sentiment analysis**  
-  Compares sentiment scores to daily **price change percentages**  
-  Visualizes the correlation between sentiment and stock movement  

---

##  Requirements

- Python 3.x  
- An [OpenAI API key](https://platform.openai.com/account/api-keys)
- (MUST PASTE YOUR OPENAI API KEY INTO SCRIPT WHERE IT SAYS "openai.api_key = "your-api-key-here"")
- Install dependencies:
  ```bash

  pip install openai yfinance matplotlib pandas


The notebook produces a scatter plot showing how the sentiment of news headlines might relate to short-term price movements for NVDA.

Replace this line with your actual plot once you run the notebook:
![Sentiment vs Price Change Plot](your image_path_here)
