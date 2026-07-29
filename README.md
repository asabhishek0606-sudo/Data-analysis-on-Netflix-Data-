# 🎬 Movie Dataset Analysis & Visualization

A complete Exploratory Data Analysis (EDA) project performed on a movie dataset using **Python, Pandas, NumPy, Matplotlib, and Seaborn**. The project focuses on data preprocessing, feature engineering, data visualization, and extracting meaningful insights from movie data.

---

## 📌 Project Overview

This project demonstrates the complete workflow of a Data Analysis project:

- Data Loading
- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Data Visualization
- Business Insights

The dataset contains information about thousands of movies including release year, popularity, ratings, vote count, genres, and more.

---

## 📂 Dataset Information

**Dataset:** `mymoviedb.csv`

### Columns

- Release_Date
- Title
- Overview
- Popularity
- Vote_Count
- Vote_Average
- Original_Language
- Genre
- Poster_Url

---

# 🛠 Technologies Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 📚 Python Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

---

# 🔄 Data Preprocessing

The following preprocessing steps were performed:

- Loaded the dataset using Pandas
- Checked duplicate values
- Generated statistical summary
- Converted `Release_Date` into Year
- Removed unnecessary columns
    - Overview
    - Original_Language
    - Poster_Url
- Categorized Movie Ratings into:
    - Not Popular
    - Below Average
    - Average
    - Popular
- Removed missing values
- Split multiple genres into individual genres
- Converted Genre into Categorical Data Type

---

# 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

### ✅ Genre Distribution

- Identified the most common movie genres.

### ✅ Vote Average Distribution

- Categorized movies based on ratings.

### ✅ Highest Popular Movie

- Found the movie with the maximum popularity.

### ✅ Lowest Popular Movie

- Found the movie with the minimum popularity.

### ✅ Release Year Distribution

- Analyzed the distribution of movie release years.

---

# 📈 Visualizations

The project includes several visualizations such as:

- Genre Count Plot
- Vote Average Distribution
- Release Year Histogram
- Popularity Analysis

Libraries Used:

- Matplotlib
- Seaborn

---

# 📌 Key Insights

- Drama is the most frequent movie genre.
- Most movies fall into the **Average** and **Popular** rating categories.
- **Spider-Man: No Way Home** has the highest popularity score.
- Older movies are fewer compared to modern releases.
- Genre explosion allows better genre-wise analysis.

---

# 📁 Project Structure

```
Movie-Data-Analysis/
│
├── mymoviedb.csv
├── Movie_Analysis.ipynb
├── README.md
```

---

# ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/movie-data-analysis.git
```

2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open the Jupyter Notebook

```bash
jupyter notebook
```

4. Run all cells.

---

# 📊 Skills Demonstrated

- Data Cleaning
- Data Wrangling
- Data Preprocessing
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Data Visualization
- Data Interpretation
- Statistical Analysis
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

# 🚀 Future Improvements

- Interactive Dashboard using Power BI
- Tableau Dashboard
- Movie Recommendation System
- Machine Learning Model for Rating Prediction
- Streamlit Web Application

---

# 👨‍💻 Author

**Abhishek Sharma**

- MCA Student
- Aspiring Data Analyst
- Python | SQL | Excel | Power BI | Pandas | NumPy | Matplotlib | Seaborn

---
