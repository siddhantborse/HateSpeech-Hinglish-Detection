# Hate Speech Detection and Analysis in Indian Social Media (Hinglish)

This project is a prototype system to detect and analyze hate speech from Indian social media comments, particularly focusing on Hinglish — a hybrid of Hindi and English often used online. The project includes scraping, preprocessing, classification using ML models, and visual analytics.

## 🔍 Objectives

- Detect hate speech in Hinglish and regional Indian languages.
- Classify comments into non-hate, hate, and extreme hate.
- Visualize trends over time and geographical patterns of hate speech.
- Explore ML/NLP limitations in handling code-mixed data.

## 📁 Project Structure

- `notebooks/`: Main Jupyter Notebook with preprocessing, model training, evaluation, and visualizations.
- `data/`: Datasets used (from Mendeley and YouTube scraping).
- `scripts/`: Python script to scrape YouTube comments using YouTube API.
- `visualizations/`: Heatmap showing geographical distribution (demo purpose).
- `docs/`: Project proposal and final report.

## 📊 Dataset Sources

- Mendeley Hate Speech Dataset: [Link](https://data.mendeley.com/datasets/snc7mxpj6t/1)
- Web-scraped YouTube data (Dhruv Rathee political video)

## 📦 Requirements

Install dependencies with:

```bash
pip install -r requirements.txt


---

### 📦 `requirements.txt`

```txt
pandas
numpy
scikit-learn
nltk
matplotlib
seaborn
langdetect
folium
google-api-python-client

