# 📊 Netflix Content Analysis

## 📁 Project Overview

This project is a data analysis case study on the Netflix dataset, focusing on understanding the type of content available, trends over the years, and various content-related attributes.

---

## 📦 Dataset

* **Source**: Netflix Dataset (CSV)
* **Columns** include:

  * `show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`.

---

## 🔧 Tools & Libraries Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 🔍 Exploratory Data Analysis

### ✅ Basic Operations

* Checked data structure, missing values, duplicates.
* Cleaned `date_added` column and converted to datetime.

### 📈 Insights Extracted

1. **Content Type Distribution**

   * Majority content is **Movies**, followed by **TV Shows**.

2. **Year-wise Trend**

   * Number of content additions peaked in 2019–2020.

3. **Top Countries**

   * **United States** produces the highest amount of content.
   * Visualization of content count by country.

4. **Ratings Distribution**

   * Analyzed common ratings like **TV-MA**, **TV-14**, **R**.

5. **Duration Analysis**

   * Movies: Duration in minutes
   * TV Shows: Number of seasons

6. **Top Genres**

   * Explored most frequent categories listed in the `listed_in` field.

7. **Director & Actor Popularity**

   * Most frequent directors and cast members in Netflix content.

---

## 📊 Visualizations

* Bar plots for type, release year trends
* Count plots for ratings
* Horizontal bar plots for countries, genres, and actors

---

## 📌 Conclusion

* Netflix’s catalog is movie-heavy.
* The platform had aggressive content additions around 2018–2020.
* Content is globally distributed but US-centric.
* Ratings and duration vary significantly between movies and TV shows.

---

## 🧹 Data Cleaning

* Removed duplicates.
* Converted data types where appropriate.
* Handled null values in `director`, `cast`, `country`.

---

## ✍️ Author

* **Sharmeen Khan**
