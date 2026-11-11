# 🎬 Netflix Movies and TV Shows Data Analysis

## 📌 1. Project Overview

This project focuses on analyzing Netflix Movies and TV Shows data using Python.

The main objective of this project is to explore Netflix content, understand content distribution, analyze ratings, and identify the countries contributing the most content to Netflix.

I used Python libraries such as Pandas and Matplotlib to perform data cleaning, data analysis, and data visualization.

## 🎯 2. Project Objectives

The main objectives of this project are:

- Analyze the distribution of Movies and TV Shows.
- Identify the most common content ratings.
- Find the top 10 countries producing Netflix content.
- Analyze Netflix content ratings.
- Explore the year-wise addition of content.
- Understand the overall Netflix content distribution.

## 📂 3. Dataset Information

The project uses the Netflix Titles Dataset.

**Dataset Name:** netflix_titles.csv

**Dataset Size:**
- Total Records: 8,809
- Original Columns: 26
- Columns after removing unwanted columns: 12

### Dataset Columns:

| Column Name | Description |
|---|---|
| show_id | Unique ID of each show |
| type | Movie or TV Show |
| title | Title of the content |
| director | Director name |
| cast | Actors information |
| country | Country of production |
| date_added | Date added to Netflix |
| release_year | Original release year |
| rating | Content rating |
| duration | Movie or TV Show duration |
| listed_in | Genre category |
| description | Content description |

## 🛠️ 4. Tools & Technologies Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- GitHub

## 🧹 5. Data Cleaning & Preprocessing

The following data cleaning operations were performed:

1. Loaded the dataset using Pandas.
2. Removed unwanted columns (Unnamed columns).
3. Checked dataset information using info().
4. Checked missing values using isnull().sum().
5. Calculated the percentage of missing values.
6. Filled missing values in the date_added column with "unknown".
7. Extracted year from the date_added column.
8. Filled missing country values with "United States".
9. Filled missing rating values with "TV-MA".
10. Checked missing values again after cleaning.

## 📊 6. Exploratory Data Analysis (EDA)

The following analysis was performed:

### 1. Movies vs TV Shows
Analyzed the number of Movies and TV Shows available on Netflix.

### 2. Rating Analysis
Analyzed different content ratings available on Netflix.

### 3. Top 10 Countries
Identified the top 10 countries based on the number of Netflix titles.

### 4. Content Rating Percentage
Analyzed the percentage distribution of different content ratings.

### 5. Year-wise Content Addition
Analyzed the number of titles added to Netflix in different years.

## 📈 7. Data Visualization

Created the following visualizations using Matplotlib:

- Bar Chart – Number of Movies vs TV Shows.
- Line Chart – Rating Status.
- Horizontal Bar Chart – Top 10 Countries by Number of Shows.
- Pie Chart – Percentage of Content Ratings.

## 💡 8. Key Findings

- Netflix dataset contains 8,809 records.
- United States has the highest number of titles (2,819).
- India is the second-highest country with 972 titles.
- TV-MA is the most common content rating.
- 2019 has the highest number of titles added to Netflix (2,016).
- The dataset includes both Movies and TV Shows.

## 🏁 9. Conclusion

This project helped me understand how to perform data cleaning, exploratory data analysis, and data visualization using Python.

I learned how to handle missing values, analyze categorical data, extract information from date columns, and create meaningful visualizations.

This project improved my practical knowledge of Python, Pandas, and Matplotlib for Data Analytics.

## 👨‍💻 10. Author

**Chetan Warked**

Aspiring Data Analyst

**Skills:**
- Python
- Pandas
- Matplotlib
- SQL
- Excel
- Power BI
