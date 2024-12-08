
# Stock Sentiment Prediction

## Project Overview
This project predicts stock sentiment by analyzing discussions on Reddit. It combines web scraping, sentiment analysis, and machine learning to classify posts as positive or negative/neutral, providing valuable insights into stock market trends.

Key steps include:
- Scraping data from Reddit subreddits like `r/stocks` using `asyncpraw`.
- Preprocessing and cleaning text data to prepare it for analysis.
- Using VADER sentiment analysis to extract sentiment scores.
- Training an XGBoost classifier to predict sentiment based on features like sentiment scores, post popularity, and recency.
- Evaluating the model with metrics like accuracy, precision, recall, and F1-score.

## Project File
- `CapX.ipynb`: Colab notebook containing all the steps of the project, including:
  - Data scraping
  - Preprocessing
  - Sentiment analysis
  - Model training and evaluation
  - Results visualization and insights


## Setup Instructions
Follow these steps to set up and run the project locally:

1. Clone the repository:
```bash
git clone <https://github.com/sathwikavardhineedi/Stock-Sentiment-Analysis/tree/main>
cd StockSentimentPrediction
```

2. Install dependencies:
Ensure you have Python 3.8 or later installed. Install the required libraries:
```bash
pip install -r requirements.txt
```

3. Open the colab notebook:
```bash
colab notebook CapX.ipynb
```

4. Follow the steps in the notebook:
   - Run the cells sequentially to scrape data, preprocess it, train the model, and evaluate its performance.

---

## Results
- **Accuracy**: Achieved 90% accuracy on the test set.
- **New Data Performance**:
  - Accuracy: 80%-100% depending on data.
  - Precision, Recall, and F1-Score: Evaluated and displayed in the notebook.

Confusion matrix and other evaluation metrics are included in the results section of the notebook.

---

## Challenges and Improvements
### Challenges:
- Balancing data between positive and negative sentiment posts.
- Handling noisy data from social media discussions.

### Future Improvements:
- Integrate additional data sources (e.g., Twitter, Telegram).
- Enhance text processing using advanced NLP techniques like BERT.
- Develop a real-time dashboard for sentiment tracking.


## License
This project is licensed under the [MIT License](LICENSE).


