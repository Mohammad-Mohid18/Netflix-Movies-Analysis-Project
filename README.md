# 🎬 Netflix Movies & TV Shows Analysis

A comprehensive exploratory data analysis (EDA) project on the Netflix Movies and TV Shows dataset from Kaggle. This project uncovers trends, patterns, and insights about content types, countries, genres, release years, and more.

---

## 📁 Dataset

- **Source**: [Netflix Movies and TV Shows — Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Features**:
  - `type`, `title`, `director`, `cast`
  - `country`, `release_year`, `date_added`
  - `listed_in` (genres), `description`

---

## 📊 Key Analyses Performed

### 1. 🧹 Data Cleaning
- Removed duplicates and handled missing values
- Parsed multi-value columns like `country`, `cast`, `listed_in`
- Converted date fields and extracted insights from them

### 2. 📈 Descriptive Analysis
- Distribution of Movies vs TV Shows
- Unique countries, directors, and genres
- Shortest and longest movie titles
- Average duration of movies
- Word clouds for title and description keywords

### 3. ⏳ Time-Based Analysis
- Titles added per year and per month
- Movies vs TV Shows trend over the years
- Seasonality in content uploads

### 4. 🌍 Geographic Analysis
- Top 10 countries contributing to Netflix's catalog
- Movie/TV Show distribution by country
- Genre heatmap across top countries

### 5. 👤 People-Centric Analysis
- Top directors and actors/actresses
- Type-wise contributions of directors and cast
- Collaboration patterns

### 6. 🎭 Genre Analysis
- Most common genres overall
- Genre comparison between Movies and TV Shows
- Genre trends over the last 5 years

---

## 📌 Insights & Observations

- **Movies dominate** Netflix’s content library.
- **United States** produces the most content, followed by **India** and **United Kingdom**.
- **Drama, Comedy, and Documentary** are the most featured genres.
- Some **directors and actors** frequently appear in the catalog.
- **Content uploads spike** in certain months (seasonal patterns).

---

## 🛠️ Tools & Libraries

- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/netflix-analysis.git
   cd netflix-analysis
