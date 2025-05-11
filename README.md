# 🎬 JustWatch Scraper Analytics 📊

## 📌 Project Overview  
This project focuses on scraping data from [JustWatch India](https://www.justwatch.com/in), a platform that aggregates streaming availability for movies and TV shows. Using Python, we extract, clean, and analyze information such as titles, release years, IMDb ratings, and available streaming platforms.

The aim is to gain insights into recent content trends, popular titles, and streaming service offerings.

---

## 📁 Project Structure  

The project is organized into two main directories:

### 📂 `TV_shows_data/`
Contains all files related to scraping, cleaning, and analyzing TV show data.
- `Web_scrapping_tvshow.py`: Python script to scrape TV show data from JustWatch.
- `Tvshows_data.csv`: Raw scraped data for TV shows.
- `cleaned_tvshow_data.csv`: Cleaned and preprocessed TV show dataset.
- `Data_filtering_analysis.ipynb`: Jupyter Notebook with filtering and analysis on TV shows.

### 📂 `movies_data/`
Contains all files related to scraping, cleaning, and analyzing movie data.
- `Web_scrapping_movies.py`: Python script to scrape movie data from JustWatch.
- `movie_data.csv`: Raw scraped movie dataset.
- `cleaned_movie_data.csv`: Cleaned and preprocessed movie dataset.
- `Data_filtering_analysis.ipynb`: Jupyter Notebook with filtering and analysis on movies.

---

## 📊 Data Summary  

### 📺 TV Shows
- **Total entries**: 135  
- **Issues handled**:  
  - 12 missing IMDb ratings  
  - 60 missing streaming service values  
  - 15 duplicate entries removed  

### 🎥 Movies
- **Total entries**: 970  
- **Issues handled**:  
  - 32 missing IMDb ratings  
  - 151 missing streaming service values  
  - No duplicate entries

---

## 🔎 Data Filtering Criteria  
To focus on quality and relevance:
- Only titles released in the **last two years** are considered.
- Only titles with an **IMDb rating of 7 or higher** are retained.

---

## 📈 Data Analysis Highlights

### TV Shows:
- **Average IMDb Rating**: 6.9  
- Identified the **Top 5 highest-rated TV shows**.

### Movies:
- **Average IMDb Rating**: 7.5  
- Identified the **Top 5 highest-rated movies**.  
- Analyzed **streaming service distribution**.  
- Explored **release year trends** for recent titles.

---

## 💡 Key Insights  
- Streaming platforms vary widely in the quantity and quality of content offered.
- IMDb ratings show clear patterns in audience preferences.
- Recent titles (last two years) with high ratings are clustered around certain platforms and genres.

These insights can benefit entertainment companies, analysts, and consumers seeking high-quality content across platforms.
