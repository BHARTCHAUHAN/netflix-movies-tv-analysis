# netflix-movies-tv-analysis
📺 Netflix Movies &amp; TV Shows Analysis – Data Cleaning &amp; Visualization using Python


# 📺 Netflix Movies & TV Shows Analysis

## 📌 Project Overview

This project explores and analyzes the **Netflix dataset**, which contains information about movies and TV shows available on the platform. The workflow is divided into two parts:

1. **Data Cleaning** → Handling missing values, duplicates, and preparing a structured dataset.
2. **Data Visualization** → Creating meaningful charts and extracting insights about Netflix’s content library.

---

## 📂 Files in this Repository

* **`cleaned_netflix_move_data.ipynb`** → Notebook for data cleaning and preprocessing.
* **`netflix_charts.ipynb`** → Notebook for data visualization and insights.
* **`netflix_titles.csv`** → Original dataset (source).
* **`cleaned_netflix_data.csv`** → Cleaned dataset ready for analysis.

---

## 🛠️ Technologies Used

* **Python**
* **Pandas** → Data cleaning and manipulation
* **Matplotlib & Seaborn** → Static data visualization
* **Plotly Express** → Interactive data visualization

---

## 🔑 Key Steps

### 1. Data Cleaning (`cleaned_netflix_move_data.ipynb`)

* Loaded raw dataset `netflix_titles.csv`
* Checked dataset info & missing values
* Removed null values and duplicates
* Standardized columns
* Exported **`cleaned_netflix_data.csv`**

### 2. Data Visualization (`netflic_charts.ipynb`)

* Loaded cleaned dataset
* Visualized:

  * Movies vs TV Shows distribution
  * Top countries producing content
  * Year-wise trend of Netflix releases
  * Most common genres/categories

---

## 📊 Insights

* Netflix has a larger share of **Movies** compared to TV Shows.
* The USA and India contribute the most content to Netflix’s library.
* A sharp increase in content releases is seen after 2015.
* Drama, Comedy, and Documentary are among the most popular genres.

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/BHARTCHAUHAN/netflix-analysis.git
   cd netflix-analysis
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook and run the notebooks in order:

   * `cleaned_netflix_move_data.ipynb`
   * `netflic_charts.ipynb`

---

## 📌 Future Improvements

* Add machine learning models for predicting movie success.
* Perform sentiment analysis on descriptions.
* Build an interactive dashboard using Streamlit or Dash.

---

## 📜 Dataset Source

The dataset is available on (https://www.kaggle.com/datasets/shivamb/netflix-shows).
