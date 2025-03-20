# **Stock Sentiment Analysis**

## **Overview**
Stock Sentiment Analysis is a machine learning project that predicts stock price movements based on financial news sentiment. The project integrates **web scraping**, **natural language processing (NLP)**, **ensemble models** like **XG Boost** and **deep learning models** like **LSTM, GRU, BiLSTM** to assess how market sentiment influences stock prices.

## **Folder Structure**
```
Stock_Sentiment_Analysis/
│── company.csv      # data of news headlines
│── company_stock_prices.csv # data for stock prices
│── merged_data_company.csv # merged data(of stock prices and news headlines) for the given company
│── README.md             # Project documentation
│── requirements.txt      # List of dependencies
│── Stock_Sentimental_Analysis.ipynb  # Main notebook with full implementation
```

## **Features**
* **News Scraping** → Fetches financial news articles from Google News RSS.  
* **Stock Data Extraction** → Retrieves historical stock prices from Yahoo Finance.  
* **Text Preprocessing** → Cleans and tokenizes financial news using NLP techniques.  
* **Sentiment Analysis** → Uses **VADER** and **BERTopic** for sentiment classification.  
* **Feature Engineering** → Generates word embeddings using **Word2Vec**.  
* **Supervised Learning Models** → Predicts stock movement using **LSTM, GRU, BiLSTM, and XGBoost**.  
* **Performance Evaluation** → Compares models to determine the most effective approach.  

## ** Installation & Cloning**
### 1 **Clone the Repository**
```bash
git clone https://github.com/your-repo/Stock_Sentiment_Analysis.git
cd Stock_Sentiment_Analysis
```

### 2 **Install Dependencies**
```bash
pip install -r requirements.txt
```

### 3 **Run the Jupyter Notebook**
```bash
jupyter notebook
```

## **Model Comparisons**
| **Model**  | **Pros** | **Cons** |
|------------|-------------|---------------|
| **LSTM**  | Captures long-term dependencies | Slower, needs more data |
| **GRU**   | Faster than LSTM, similar performance | Can lose long-term patterns |
| **BiLSTM** | Captures patterns in both directions | Computationally expensive |
| **XGBoost** | Fast and works well with tabular data | Doesn't handle sequential data well |

## **Usage**
Run the notebook to:
1. **Scrape financial news** 
2. **Extract stock price data** 
3. **Calculate sentiment scores** 
4. **Train models (LSTM, GRU, BiLSTM, XGBoost)** 
5. **Evaluate performance** 



