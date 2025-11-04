# lab-1
This lab applies data analysis and cleaning techniques using Python’s Pandas library on the IMDB-Movie-Data.csv dataset of 1,000 films. It focuses on mastering key steps in data preprocessing, transformation, filtering, and visualization for real-world analytical workflows.
# 🎬 IMDB Movie Data Analysis — Lab 1  

## 📘 Overview  
This lab focuses on exploring and cleaning movie data using **Python’s Pandas** library.  
The dataset (*IMDB-Movie-Data.csv*) contains 1,000 movies, including title, genre, director, year, runtime, rating, votes, revenue, and metascore.  
The goal is to apply **data preprocessing, transformation, filtering, and visualization** techniques for real-world analytical workflows.  

---

## ⚙️ Tools and Libraries  
- **Python 3**  
- **Pandas** — for data manipulation and analysis  
- **Matplotlib** — for data visualization  
- **Google Colab** — as the working environment  

---

## 🧩 Steps Performed  
1. **Data Loading & Inspection**  
   - Imported dataset using `pd.read_csv()`  
   - Reviewed structure using `.head()`, `.info()`, and `.shape()`  

2. **Data Cleaning**  
   - Removed duplicates with `drop_duplicates()`  
   - Filled missing revenue values with the mean  
   - Renamed columns for consistency (e.g., `Runtime (Minutes)` → `runtime`)  

3. **Descriptive Statistics**  
   - Used `.describe()` to calculate averages, min/max, and standard deviations  
   - Analyzed most common genres using `.value_counts()`  

4. **Filtering & Subsetting**  
   - Extracted data for specific directors (e.g., *Ridley Scott*, *Christopher Nolan*)  
   - Filtered high-rated movies (rating ≥ 8.6)  
   - Combined multiple conditions for custom queries  

5. **Feature Engineering**  
   - Created a new column `rating_category` classifying movies as “good” or “bad”  

6. **Visualization**  
   - Plotted scatter (rating vs. revenue), histogram (ratings), and boxplot (revenue) using Matplotlib  

---

## 📊 Results & Visuals  
*(Insert your screenshots below — one per plot)*  

- **Scatter Plot:** Revenue vs Rating  
  > ![scatter_plot](path/to/scatter.png)  

- **Histogram:** Ratings Distribution  
  > ![histogram](path/to/histogram.png)  

- **Boxplot:** Revenue Distribution  
  > ![boxplot](path/to/boxplot.png)  

---

## 🧠 Insights  
- Higher-rated movies tend to earn more and receive more votes.  
- *Action* and *Sci-Fi* genres are the most common and often high-performing.  
- Handling missing data improves analysis accuracy and visual clarity.  

---

## 🏁 Conclusion  
This lab demonstrates how to **clean, analyze, and visualize** a real-world dataset using Pandas.  
It builds strong foundational skills in data analytics, preparing for advanced machine learning and business intelligence applications.  
