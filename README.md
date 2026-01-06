### Pulse: Market Sentiment Analyzer

### Overview

Pulse is an NLP-based system that analyzes public stock market discussions to detect sentiment trends, explain sentiment drivers, and support market analysis.

### Features

- Reddit-based stock discussion ingestion
- Text preprocessing pipeline
- FinBERT sentiment analysis
- Interactive Streamlit dashboard
- Sentiment spike alerts
- Keyword explainability
- Sentiment comparison views

### Project Structure

```
Pulse_Project/
├── ingestion/
├── preprocessing/
├── model/
├── dashboard/
├── data/
├── requirements.txt
├── .env

```

### How to Run

```bash
pip install -r requirements.txt
python ingestion/reddit_json_scraper.py
python ingestion/merge_data.py
python preprocessing/apply_cleaning.py
python model/apply_sentiment.py
streamlit run dashboard/app.py

```

### Model

- ProsusAI FinBERT
- Transformer-based financial sentiment classifier

### Disclaimer

This project uses publicly available data for academic and educational purposes only.

---

### Author

Jayaprakash Srinivasan
