# Task 3: Exploratory Data Analysis (EDA) Using Python

## 1. Problem Statement

The objective of this task is to perform Exploratory Data Analysis (EDA) on the Netflix dataset to identify trends, patterns, and relationships in the data. The analysis includes summary statistics, correlation analysis, missing-value inspection, and visualizations to understand the distribution of Netflix movies and TV shows.

## 2. Dataset Details

- **Dataset Name:** Netflix Movies and TV Shows
- **Source:** Kaggle
- **File Name:** `netflix_titles.csv`
- **Dataset Link:** https://www.kaggle.com/datasets/shivamb/netflix-shows

The dataset contains information about movies and TV shows available on Netflix, including their titles, directors, cast, countries, release years, ratings, durations, and genres.

### Important Columns

| Column Name | Description |
|---|---|
| show_id | Unique identifier for each title |
| type | Movie or TV Show |
| title | Name of the title |
| director | Director's name |
| cast | Actors and actresses |
| country | Country associated with the title |
| date_added | Date added to Netflix |
| release_year | Year the title was released |
| rating | Content rating |
| duration | Movie duration or number of seasons |
| listed_in | Genre or category |
| description | Description of the title |

## 3. Tools and Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 4. Approach

The following steps were performed during the analysis:

1. **Load Dataset:** Imported the Netflix dataset using Pandas.
2. **Inspect Data:** Examined the first few rows, dataset dimensions, column names, data types, and missing values.
3. **Summary Statistics:** Generated descriptive statistics to understand the dataset.
4. **Content Type Analysis:** Compared the number of movies and TV shows using a count plot.
5. **Release Year Analysis:** Created a line chart to explore the distribution of titles across release years.
6. **Country Analysis:** Created a bar chart showing the top 10 countries contributing Netflix content.
7. **Correlation Analysis:** Calculated correlations between numerical columns and visualized them using a heatmap where applicable.
8. **Trend Analysis:** Compared movie and TV show counts across release years.

## 5. Visualizations Created

- **Content Type Distribution:** Compares movies and TV shows.
- **Release Year Trend:** Shows the distribution of titles by release year.
- **Top 10 Countries:** Displays countries with the highest numbers of titles.
- **Correlation Heatmap:** Shows correlations between available numerical variables.
- **Movies vs. TV Shows Trend:** Compares movie and TV show distributions across release years.

## 6. Results and Observations

- Movies make up a larger share of titles than TV shows in the analyzed dataset.
- The release-year analysis helps identify periods with a greater number of titles.
- Country-wise analysis highlights the countries contributing the most content.
- Comparing movies and TV shows reveals differences in their release-year distributions.
- Missing-value analysis identifies columns that may need further preprocessing.
- Correlation analysis helps explore relationships between numerical variables.

*Note: Actual findings depend on the dataset version and should be verified against the notebook output.*

## 7. Conclusion

This task demonstrates how Exploratory Data Analysis can be used to understand a real-world dataset. Summary statistics, missing-value inspection, correlation analysis, and visualizations were used to explore Netflix content and identify meaningful patterns. The analysis provides a foundation for further data cleaning and data visualization.

## 8. Project Structure

```text
Task-3-Netflix-EDA/
├── netflix_titles.csv
├── Netflix_EDA.ipynb
└── README.md
```

*Note: Update the filenames to match the files in your repository. Include the dataset only if required by your submission instructions.*
