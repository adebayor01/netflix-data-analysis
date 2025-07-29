# 📊 Netflix Movies & TV Shows Data Analysis

This project explores the Netflix Movies and TV Shows dataset, focusing on data cleaning, feature engineering, and insightful visualizations using Python. The dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows).

---

## Dataset Overview

- **Total Records**: 7,964 titles
- **Columns**: 16 (including type, genre, duration, country, date added, etc.)
- **Source**: Netflix catalog metadata

---

## Technologies Used

- Python
- Google Colab
- Pandas & NumPy
- Matplotlib & Seaborn

---

## Project Workflow

### 1. Data Cleaning
- Filled missing values in `director`, `cast`, `country`, `rating`
- Converted `date_added` to `datetime` and extracted `year_added`, `month_added`
- Cleaned text columns and standardized formatting
- Parsed `duration` into `duration_int` and `duration_type`

### 2. Exploratory Data Analysis (EDA)
- ✅ Distribution of Movies vs TV Shows
- ✅ Content added by year
- ✅ Top producing countries
- ✅ Most common content ratings (TV-MA, PG, etc.)
- ✅ Top 10 genres across Netflix
- ✅ Movie duration distribution

---

## 📊 Key Insights

- 🎬 **Movies** dominate the Netflix catalog
- 🇺🇸 **United States** has the highest number of titles
- 🗓️ Most content was added in **2019**
- 🎭 Top genres include **International Movies**, **Dramas**, and **Comedies**
- ⏱️ Most movies run between **80–100 minutes**
- 🚫 Majority of content is rated **TV-MA** (mature audiences)

---

## Files Included

- `netflix_analysis.ipynb` – Cleaned notebook with full analysis
- `cleaned_netflix_data.csv` – Final cleaned dataset

---

## 🚀 Future Work (Optional Ideas)
- Build a dashboard using Streamlit or Plotly Dash
- Group ratings into child/teen/adult categories
- Predict content popularity based on metadata

---

## Author

**Oyekola Samuel Oluwasogo**  
[GitHub](https://github.com/adebayor01) | [Email](mailto:oyekolas01@gmail.com)

---

⭐ If you like this project, consider starring the repo and checking out my other work.
