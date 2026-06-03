 

---

# 📊 Netflix Exploratory Data Analysis (EDA)

*A deep dive into Netflix’s global content catalog using Python, Pandas, and Matplotlib.*

---

## 🚀 Project Overview

This project performs a **comprehensive exploratory data analysis (EDA)** on the Netflix Movies & TV Shows dataset.
It reveals insights about genre distribution, release year trends, country contributions, content ratings, and more.

The goal is to understand **how Netflix structures its library**, identify patterns, and visualize key trends using data science techniques.

---

## 📁 Dataset

* **File:** `netflix_titles.csv`
* **Source:** Kaggle (Netflix Movies and TV Shows Dataset)
* **Rows:** 8,807
* **Columns:** 12
* **Features include:**

  * Title, Director, Cast
  * Country
  * Release year
  * Added date
  * Rating
  * Duration
  * Listed in (Genres)

---

## 🧪 Technologies Used

| Category        | Tools                |
| --------------- | -------------------- |
| Programming     | Python               |
| Data Analysis   | Pandas, NumPy        |
| Visualization   | Matplotlib, Seaborn  |
| Notebook        | Jupyter Notebook     |
| Version Control | Git & GitHub Desktop |

---

## 📈 Key Insights

### ✔️ Content Type Distribution

* Netflix has **more Movies than TV Shows**.

### ✔️ Top Genres

A bar chart was generated showing the **Top 10 Genres by Content Count**, including genres like:

* International Movies
* Dramas
* Comedies
* International TV Shows
* Documentaries
* Action & Adventure

---

## 🔍 Main Analysis Performed

### 1️⃣ **Missing Values Analysis**

* Checked null values across all columns
* Cleaned & standardized dates

### 2️⃣ **Content Type Breakdown**

* % Movies vs % TV Shows
* Year-wise growth trend

### 3️⃣ **Genre Distribution**

* Extracted & counted genres
* Identified top categories

### 4️⃣ **Country-wise Content Production**

* Top content-producing countries
* U.S., India, and U.K. dominate

### 5️⃣ **Ratings Analysis**

* Content maturity levels (PG, TV-MA, etc.)

### 6️⃣ **Time Series of Release Years**

* Historical release trends
* Spike in content around 2017–2020

---

## 📉 Visualizations Included

* Bar Charts (Genres, Ratings, Countries)
* Pie Charts (Movies vs Shows)
* Heatmaps (Missing Values)
* Line Charts (Content over Years)

---

## 🗂️ Folder Structure

```
📦 Netflix-EDA
 ┣ 📜 README.md
 ┣ 📊 Netflix_Exploratory_Data_Analysis.ipynb
 ┣ netflix_titles.csv
 ┗ (All generated plots)

```

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/netflix-eda.git
cd netflix-eda
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Open the notebook

```bash
jupyter notebook
```

---

## 🧠 Skills Demonstrated

* Data Cleaning
* Feature Engineering
* Descriptive Statistics
* Data Visualization
* Exploratory Data Analysis
* Git & GitHub workflow

---

## 📌 Future Improvements

* Build an interactive dashboard using **Power BI**
* Perform sentiment analysis on descriptions
* Cluster content based on keywords
* Predict Netflix content trends using ML models

---

## ❤️ Acknowledgements

Dataset provided by **Kaggle**.
Analysis & visualizations by **Praneeth Radeesha**.

---

