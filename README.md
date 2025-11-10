# YouTube Data Science Channels Analysis

This project demonstrates data collection, preprocessing, and exploratory data analysis (EDA) using YouTube API on popular Data Science channels.

[Notebook link on Google Drive](https://colab.research.google.com/drive/1AVoRSeNRPeIrSgm9Jbo0nO-4OgX5sN7m?usp=sharing)

---

## Project Overview

The goal of this project is to explore patterns and insights from the top Data Science YouTube channels by analyzing video statistics and user comments. This helps understand content performance, trends, and engagement.

### Key Features

1. **Data Collection via YouTube API**
   - Fetch channel statistics (subscribers, views, total videos).
   - Extract video metadata (title, description, tags, views, likes, comments, duration, etc.).
   - Retrieve top comments for each video.

2. **Data Preprocessing & Feature Engineering**
   - Convert data types and parse dates.
   - Calculate additional features: like/comment ratios, title length, number of tags, day of week.
   - Filter channels for focused analysis (e.g., Sentdex).

3. **Exploratory Data Analysis (EDA)**
   - Visualization of channel popularity and video statistics.
   - Analyze relationships: likes/comments vs views, video duration, title length, number of tags.
   - Identify trending topics using word clouds from video titles and comments.
   - Sentiment analysis on comments using VADER.

---

## Repository Contents

- **YouTube_API_EDA.ipynb** – main Jupyter notebook with API calls, preprocessing, and EDA.
- **video_data.csv** – collected video metadata.
- **comments_data.csv** – collected comments data.
- **sentdex_video_df.csv** – filtered data for Sentdex channel.
- **sentdex_comments_df.csv** – filtered comments for Sentdex channel.

---

## Skills Demonstrated

- API integration and data crawling (YouTube Data API v3)
- Data cleaning, preprocessing, and feature engineering
- Exploratory Data Analysis (visualizations, correlations, word clouds)
- Basic sentiment analysis on textual data

---

## Requirements

- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, nltk, isodate, wordcloud, google-api-python-client, scikit-learn

---

## Usage

1. Clone the repository.
2. Open `YouTube_API_EDA.ipynb` in Jupyter or Colab.
3. Run the notebook sequentially to fetch data, preprocess, and visualize insights.
