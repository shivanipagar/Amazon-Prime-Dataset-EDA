# 📊 Amazon Prime Video Exploratory Data Analysis (EDA)

This project involves a detailed Exploratory Data Analysis (EDA) of an Amazon Prime Video dataset. The goal is to understand the structure, distribution, and relationships within the data, and to derive actionable insights using Python and data visualization tools.

## 🔍 Overview

The notebook walks through the following steps:

1. **Know Your Data**:
   - Library Imports
   - Dataset loading and first look
   - Dataset structure: rows, columns, info
   - Checking for duplicates and missing values

2. **Understanding Your Variables**:
   - Variable description and data types
   - Columns include: `id`, `title`, `type`, `description`, `release_year`, `age_rating`, `duration`, `genres`, `country`, `language`, `imdb_score`, and `imdb_votes`.

3. **Data Cleaning & Preparation**:
   - Handling missing values
   - Dropping/Imputing columns
   - Changing column types

4. **Exploratory Analysis**:
   - Distribution of content types
   - Top genres and most common release years
   - Content age rating distribution
   - IMDB ratings and vote patterns

5. **Visualizations**:
   - Count plots, bar charts, pie charts
   - Histograms for numerical columns
   - Correlation heatmaps

## 📁 Dataset

The dataset is assumed to be a CSV file containing information about content available on Amazon Prime Video. It includes metadata like title, type (movie/TV show), release year, genre, country, language, IMDB ratings, etc.

## 🛠️ Technologies Used

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📈 Insights

- The majority of Amazon Prime content consists of movies rather than TV shows.
- Most titles were released after 2010, indicating a focus on recent content.
- English is the predominant language of the content.
- The most popular genres include Drama and Comedy.
- IMDB scores are generally high, with many titles rated above 6.
- A significant portion of content is targeted at a general or family-friendly audience.

## ▶️ Getting Started

Clone the repo and run the notebook:

```bash
git clone https://github.com/your-username/amazon-prime-eda.git
cd amazon-prime-eda
jupyter notebook "Amazon Prime EDA.ipynb"

