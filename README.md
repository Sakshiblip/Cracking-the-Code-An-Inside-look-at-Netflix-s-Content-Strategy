[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sakshiblip/Cracking-the-Code-An-Inside-look-at-Netflix-s-Content-Strategy/blob/main/netflix's_content_strategy.ipynb)

# Cracking the Code: An Inside Look at Netflix's Content Strategy 🎬

This repository contains a comprehensive data analysis project exploring Netflix's global content library. By leveraging data visualization and exploratory data analysis (EDA) techniques, this project uncovers the patterns and strategies used by Netflix to maintain its position as a leading streaming service.

## 📌 Project Overview
The goal of this project is to analyze the Netflix dataset to understand:
* The balance between **Movies** and **TV Shows**.
* Content production trends over the last decade.
* Geographical distribution of content (top producing countries).
* Popular genres and content ratings across different regions.
* Common themes in content descriptions using natural language processing (WordClouds).

## 🚀 Key Features
* **Data Cleaning:** Handling missing values in directors, cast, and country fields.
* **Time-Series Analysis:** Tracking the growth of content additions from 2008 to 2021.
* **Comparative Analysis:** Side-by-side comparison of Movies vs. TV Shows.
* **Rating Distribution:** Breakdown of content maturity levels (TV-MA, TV-14, etc.).
* **Visual Storytelling:** Interactive and static plots using Seaborn and Matplotlib.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:**
    * `Pandas`: Data manipulation and cleaning.
    * `NumPy`: Numerical computations.
    * `Matplotlib` & `Seaborn`: Advanced data visualization.
    * `WordCloud`: Text data visualization for content descriptions.

## 📊 Sample Insights
* **Content Volume:** The library is predominantly composed of Movies, though TV Shows have seen a significant increase in recent years.
* **Global Leaders:** Analysis shows the United States as the top content producer, followed closely by India for movies.
* **Release Cycles:** Identification of peak months for content releases on the platform.

## 📁 Dataset
The analysis is performed on the **Netflix Movies and TV Shows** dataset, which includes metadata for all content available on the platform as of 2021.
* **Source:** Kaggle / Netflix
* **Key Columns:** `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in` (genres).

## 📖 How to Use
1.  **Clone the Repo:**
    ```bash
    git clone [https://github.com/your-username/netflix-content-strategy.git](https://github.com/your-username/netflix-content-strategy.git)
    ```
2.  **Install Dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn wordcloud
    ```
3.  **Run the Notebook:**
    Open `netflix's_content_strategy.ipynb` in Google Colab or Jupyter Notebook and run the cells sequentially.

---
*Developed as part of a Data Science Portfolio project.*
