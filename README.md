# 📊 Amazon Prime Video – Exploratory Data Analysis (EDA)

---

## 📌 Project Name
**Amazon Prime Video: Exploratory Data Analysis (EDA)**

---

## 👩‍💻 Contributor
**Sneha M N**  
*(Individual Project)*

---

## 📁 Project Type
**Exploratory Data Analysis (EDA)**

---

## 📖 Project Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** on the Amazon Prime Video dataset. The dataset contains detailed information about movies and TV shows available on the platform, including ratings, genres, runtime, release year, cast, and popularity metrics.

The goal is to extract meaningful insights that help understand **content trends, audience preferences, and factors influencing content success**.

---

## 🎯 Objective
The main objective of this project is to:

- Analyze Amazon Prime Video content data  
- Identify patterns and trends in movies and TV shows  
- Understand relationships between ratings, votes, genres, and popularity  
- Extract actionable insights for business decision-making  

---

## 📂 Dataset Information

The project uses two datasets:

### 📌 1. Titles Dataset (`titles.csv`)
Contains information about movies and TV shows:
- `id`, `title`, `type`
- `description`, `release_year`
- `genres`, `production_countries`
- `runtime`, `seasons`
- `imdb_score`, `imdb_votes`
- `tmdb_popularity`, `tmdb_score`

---

### 📌 2. Credits Dataset (`credits.csv`)
Contains information about cast and crew:
- `person_id`
- `id` (linking key)
- `name`
- `character`
- `role` (Actor / Director)

---

## 🧹 Data Preprocessing & Cleaning

- Removed duplicate records  
- Handled missing values using:
  - Median imputation for ratings  
  - Placeholder values for categorical data  
- Dropped irrelevant columns (e.g., `imdb_id`)  
- Converted data types for analysis  
- Merged datasets using `id`  
- Exploded nested columns like `genres` and `production_countries`  

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Univariate Analysis
- Content type distribution (Movies vs TV Shows)  
- Release year trends  
- IMDb score distribution  
- Runtime analysis  
- Genre distribution  

---

### 🔹 Bivariate Analysis
- IMDb score vs TMDB popularity  
- Runtime vs IMDb score  
- Genre vs ratings  
- Director vs average ratings  
- Actor popularity analysis  

---

### 🔹 Multivariate Analysis
- Correlation heatmap  
- Pair plots for numerical features  
- Relationship between votes, ratings, and popularity  

---

## 📈 Key Insights

- Movies dominate the platform compared to TV shows  
- Most content is released after the year 2000  
- IMDb scores are mostly in the mid-range (5–7)  
- Popular genres include Drama, Comedy, and Action  
- Ratings and popularity are not strongly correlated  
- A few actors and directors dominate content production  
- Content production is uneven across countries  

---

## 💡 Business Insights

- Focus on highly rated and highly voted content  
- Invest in successful genres and directors  
- Promote high engagement movies for better visibility  
- Improve recommendation systems using data insights  
- Balance content diversity across genres and regions  

---

## 🛠️ Tools & Technologies Used

- Python 🐍  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Google Colab  

---

## 📊 Visualizations Used

- Bar Charts  
- Histograms  
- Scatter Plots  
- Box Plots  
- Pie Charts  
- Heatmaps  
- Pair Plots  

---

## 🚀 Conclusion

This project successfully transforms raw Amazon Prime Video data into meaningful insights. It highlights content trends, audience preferences, and key success factors that can help improve content strategy and platform performance.

---

## 🔗 GitHub Repository

👉 https://github.com/Snehamn24/Amazon-Prime-Video-EDA-and-Machine-Learning-Analysis.git

---
