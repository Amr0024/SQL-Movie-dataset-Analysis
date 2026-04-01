# 🎬 MovieLens SQL Analysis Project

## 🔍 Overview
This project analyzes user movie ratings using **SQL inside a Jupyter Notebook**. It explores how users rate movies, which movies are most popular, and rating behavior patterns.

The focus is on **SQL-driven data analysis**, not machine learning.

---

## 📂 Dataset
- MovieLens 100K Dataset  
- Link: https://files.grouplens.org/datasets/movielens/ml-100k.zip  

Contains:
- User IDs
- Movie IDs
- Ratings (1–5 scale)
- Timestamps

---

## 🛠️ Tools & Technologies
- Python 🐍  
- SQLite  
- SQL (core analysis)  
- ipython-sql  
- pandas  
- matplotlib  

---

## 📌 Project Workflow

### 1. Data Preparation
- Loaded raw dataset
- Structured it into a SQLite database

### 2. SQL Analysis Performed
- Average rating across all movies
- Most rated (popular) movies
- Highest-rated movies (with minimum reviews filter)
- Most active users
- Rating distribution
- User rating behavior patterns

### 3. Visualization
- Rating distribution chart using matplotlib

---

## 📊 Key Insights
- A small number of movies receive most ratings
- High-rated movies often require a minimum number of reviews to be meaningful
- User activity varies significantly (some users rate far more than others)
- Ratings are not evenly distributed (bias toward higher scores)

---

## 🚀 Outcome
This project demonstrates how SQL can be used as a powerful tool for **real-world analytical thinking inside a notebook environment**.

---

## 📁 Files
- `movie_sql_analysis.ipynb` → Main analysis notebook
- `movies.db` → SQLite database (optional, can be regenerated)

---

## 👤 Author
Amr N
