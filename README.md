![Python](https://img.shields.io/badge/Tool-Python-blue) ![Pandas](https://img.shields.io/badge/Tool-Pandas-lightblue) ![NumPy](https://img.shields.io/badge/Tool-NumPy-orange) ![Matplotlib](https://img.shields.io/badge/Tool-Matplotlib-red) ![Seaborn](https://img.shields.io/badge/Tool-Seaborn-teal) ![Scikit--learn](https://img.shields.io/badge/Tool-Scikit--learn-yellow) ![Jupyter](https://img.shields.io/badge/Tool-Jupyter-orange)  ![Excel](https://img.shields.io/badge/Data-Excel-green)  ![Completed](https://img.shields.io/badge/Status-Completed-success)



# 🎬 Netflix Recommendation System

This project implements a **Recommendation System** using the Netflix dataset.
It suggests movies/shows to users based on their preferences, viewing history, and similarity with other users/items.

---

## 📌 Project Overview

* Built using **Jupyter Notebook (Python)**
* Uses **Collaborative Filtering & Content-Based Filtering** approaches
* Dataset: Netflix Movies/Shows dataset (from Kaggle)
* Goal: Provide personalized recommendations to improve user experience

---

## ⚙️ Tech Stack & Libraries

* **Python**
* **Pandas** – Data processing
* **NumPy** – Mathematical operations
* **Matplotlib / Seaborn** – Data visualization
* **Scikit-learn** – ML models & similarity metrics
* **Jupyter Notebook**

---

## 📂 Files in this Repository

* `Netflix_Recommendation.ipynb` – Main Jupyter Notebook with code & results
* `netflix_titles.csv` – Dataset used for training/testing
* `README.md` – Project documentation

---

## 🔍 Key Steps Implemented

1. **Data Collection & Cleaning**

   * Loaded Netflix dataset from Kaggle
   * Removed duplicates, handled missing values

2. **Exploratory Data Analysis (EDA)**

   * Visualized genre distribution, ratings, release years
   * Insights into most popular genres & countries

3. **Recommendation Models**

   * **Content-Based Filtering**: recommends similar movies based on genre, description, etc.
   * **Collaborative Filtering**: uses user-item interactions (ratings, preferences)

4. **Evaluation**

   * Cosine similarity, correlation metrics
   * Sample recommendations for test users

---

## 🎯 Results

* Content-Based: Suggests movies similar to the one user liked
* Collaborative: Suggests movies based on other users with similar tastes
* Hybrid model gives better accuracy & diversity

---

## 🚀 How to Run

   
1. Install required libraries:

     bash
   `pip install -r requirements.txt`

2. Open Jupyter Notebook:

     bash
   `jupyter notebook`
   
3. Run `Netflix_Recommendation.ipynb`

---

## 📊 Sample Output

✅ Example: If a user liked *"Inception"*, the model suggests:

* Interstellar
* The Prestige
* Shutter Island
* Tenet

