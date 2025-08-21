<<<<<<< HEAD
# Reddit Sentiment Analysis

This project performs sentiment analysis on Reddit subreddits using two models:
- VADER: A rule-based sentiment analysis tool.
- BERT: A deep learning model using the Hugging Face `transformers` library.

# Features
- Scrapes Reddit comments using `praw`
- Analyzes sentiment using both VADER and BERT
- Visualizes sentiment distributions
- Modular code for easy expansion


# Tech Stack
- Python
- `praw`
- `vaderSentiment`
- `transformers`
- `matplotlib`, `pandas`

# Project Structure
```
├── sentiment_analysis.ipynb     # Main notebook
├── sentiment_utils.py           # Helper functions
├── data/                        # Optional sample data
├── results/                     # Visualizations
```

# How to Run
1. Clone the repo
2. Set up a `.env` file with Reddit API credentials (use `.env.example` as a template)
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the notebook:
    ```bash
    jupyter notebook sentiment_analysis.ipynb
    ```

## 🔐 .env Format
```env
CLIENT_ID=your_client_id
CLIENT_SECRET=your_client_secret
USER_AGENT=your_user_agent
```

## 🧪 Future Ideas
- Compare more sentiment models
- Analyze specific political or niche subreddits
- Build a dashboard using Streamlit

## 📌 Author
Ekam –  | [https://github.com/Ekam334] |
=======
# Reddit-Sentiment-Analysis
>>>>>>> 380e508f15a389c95909d721086bd7d3c65dd82e
