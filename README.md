# Netflix Data Analysis 

A data analysis project developed for the AI Programming course at Taibah University.

This project explores the streaming content landscape using a subset of the Netflix Titles Dataset (netflix_titles_subset.csv). The goal is to perform data processing, cleaning, analysis, and visualization to uncover patterns and trends in movies and TV shows available on Netflix.

# Project Files

* Netflix_Data_Analysis.ipynb — Jupyter Notebook containing the complete data processing, analysis, and visualizations.
* netflix_titles_subset.csv — Dataset used for the analysis.

# Team Members

* Sara Aljohani — Data Validation, Grouping/Aggregating, Normalization, Line/Bar Charts, Heatmaps
* Arwa Almahyawi — Text Tokenization, Correlation, Histogram
* Afnan Lutfullah — Data Reformatting, Central Values, Scatter Plot, Pie Chart
* Jory Alhindi — Missing Values, Duplicate Removal, Common Words, Normalization, Pie Chart

# Data Processing Workflow

To prepare the dataset for analysis, we implemented an Object-Oriented Programming (OOP) pipeline that includes:

1. Validation: Flagged invalid, non-numeric, or out-of-range release years.
2. Reformatting: Processed the listed_in (genres) and country columns into structured fields.
3. Deduplication: Removed duplicate movie and TV show titles.
4. Missing Values: Replaced empty values with "Unknown" to maintain consistency.
5. Type Conversion: Converted date_added from text to a proper datetime format.
6. String Cleaning: Removed text such as "min" and "Season" from the duration column to enable numerical analysis.

# Data Analysis & Insights

The analysis produced several findings from the dataset subset used in this project:

* Content Distribution: The dataset contains more Movies (353) than TV Shows (191).
* Average Duration: The mean movie duration is approximately 106 minutes, while the median TV show duration is 2 seasons.
* Top Countries: The United States, United Kingdom, and India appear most frequently as content-producing countries.
* Frequent Keywords: Common words in descriptions were identified through text tokenization and frequency analysis.
* Correlation: A slight negative correlation (-0.27) was observed between content duration and release year.

# Data Visualization

The project uses several visualization techniques to explore and communicate the results:

* Heatmaps & Missingno Matrices: Visualized dataset completeness before and after data cleaning.
* Bar Charts & WordClouds: Showed the most common genres and keywords.
* Pie Charts: Illustrated the distribution of content types and maturity ratings.
* Histograms & Scatter Plots: Explored movie duration distributions and the relationship between duration and release year.
* Line Graphs: Displayed trends in the number of titles released over time.

# Technologies Used

* Language: Python 3
* Environment: Jupyter Notebook
* Libraries: pandas, numpy, matplotlib, seaborn, missingno, wordcloud

# How to Run

1. Clone or download this repository.
2. Open Netflix_Data_Analysis.ipynb using Jupyter Notebook or JupyterLab.
3. Make sure the required Python libraries are installed.
4. Run the notebook cells in order.

# Course Information

* Course: AI Programming
* University: Taibah University
