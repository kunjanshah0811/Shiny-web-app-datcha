# 📊 Datcha

![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Shiny](https://img.shields.io/badge/Shiny-blue?style=for-the-badge&logo=rstudio&logoColor=white)

A **Shiny web app** for comparing two social media datasets collected at different points in time — detecting deletions, additions, and edits with rich visualizations.

---

## 🚀 Features

- **Deletion Analysis** - Posts removed between datasets
- **Addition Analysis** - New posts in the second dataset
- **Edit Analysis** - Changes in matching posts (Levenshtein distance)
- Word Frequency, Keyness, Topic Modeling & Sentiment Analysis

---

## 📦 Requirements

- R + Shiny
- Install packages listed in `global.R`

---

## ▶️ Run

```r
source("app.R")
```

---

## 📁 Data Format

Two CSV files, each with:
- An **ID column** (e.g. `id`, `tweet_id`, `post_id`)
- A **`text`** column containing post content

---

## 👥 Credits

Developed by **Dr. Yannik** & **Kunjan**
