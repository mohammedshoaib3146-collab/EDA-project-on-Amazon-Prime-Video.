# 🎬 Amazon Prime Video — Exploratory Data Analysis (EDA)

An exploratory data analysis project focused on understanding the content library of Amazon Prime Video using Python, data analysis libraries, and visualizations.

## 📌 Project Overview

This project explores the movies and TV shows available in the Amazon Prime Video dataset to identify patterns, trends, and insights related to content distribution, genres, production countries, release years, ratings, and cast and crew.

The goal is to transform raw data into meaningful insights through data cleaning, exploratory analysis, and data visualization.

## 🎯 Objectives

- Analyze the distribution of movies and TV shows.
- Identify popular genres and major content-producing countries.
- Explore content release trends over time.
- Examine IMDb ratings and other available rating metrics.
- Analyze directors, actors, and other cast and crew information.
- Discover patterns that can support data-driven content analysis.

## 🗂️ Dataset Description

The project uses two CSV files:

### 1. `titles.csv`

Contains information about movies and TV shows, including:

- Title and content type
- Release year
- Runtime
- Genres
- Production countries
- Age certification
- IMDb and TMDb ratings, where available

### 2. `credits.csv`

Contains cast and crew information, including:

- Person names
- Associated titles
- Roles, such as actor or director
- Character information, where available

*Note: Dataset columns and available information depend on the original data source.*

## 🛠️ Tools & Technologies

- **Python** — Programming and analysis
- **Pandas** — Data manipulation and cleaning
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization
- **Jupyter Notebook / Google Colab** — Analysis environment
- **GitHub** — Version control and project documentation

## 🔍 Project Workflow

1. **Data Loading:** Import the CSV datasets into Python.
2. **Data Understanding:** Inspect dataset dimensions, columns, and data types.
3. **Data Cleaning:** Examine missing values, duplicate records, and inconsistencies.
4. **Data Preparation:** Transform columns and prepare the data for analysis.
5. **Exploratory Data Analysis:** Investigate individual variables and relationships between variables.
6. **Data Visualization:** Create charts to identify trends and patterns.
7. **Insights & Interpretation:** Summarize findings from the analysis.

## 📊 Analysis Performed

The analysis explores the following areas, depending on data availability:

- Movies vs. TV shows distribution
- Titles released over the years
- Most frequently represented genres
- Content distribution by production country
- IMDb score distribution
- Runtime distribution
- Top directors and actors by associated titles
- Relationships between available ratings and other content attributes

## 💡 Key Insights

The analysis is designed to help answer questions such as:

- Which content type is more prevalent in the dataset: movies or TV shows?
- Which genres appear most frequently?
- Which countries contribute the most titles?
- How has the number of releases changed over time?
- What patterns can be observed in content ratings and runtime?
- Which directors and actors are associated with the most titles?

*Refer to the accompanying notebook for the actual findings, charts, and conclusions.*

## 🚀 Getting Started

### Prerequisites

Install Python 3 and the required libraries.

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Clone the Repository

```bash
git clone https://github.com/mohammedshoaib3146-collab/EDA-project-on-Amazon-Prime-Video.git
```

Navigate to the project directory:

```bash
cd EDA-project-on-Amazon-Prime-Video
```

### Run the Notebook

1. Open the repository in GitHub and locate the Jupyter Notebook (`.ipynb` file).
2. Download or clone the repository to your computer.
3. Open the notebook using Jupyter Notebook or upload it to Google Colab.
4. Ensure that `titles.csv` and `credits.csv` are available at the file paths referenced in the notebook.
5. Run the notebook cells sequentially to reproduce the analysis.

## 📁 Project Structure

The repository contains the analysis notebook and supporting datasets.

```text
EDA-project-on-Amazon-Prime-Video/
│
├── titles.csv
├── credits.csv
├── <your-eda-notebook>.ipynb
└── README.md
```

*Replace the notebook placeholder with your actual filename and adjust the structure above to match the files in your repository.*

## 📈 Project Outcomes

- Practiced data cleaning and preprocessing using Python.
- Applied exploratory data analysis techniques to a real-world content dataset.
- Developed data visualization and analytical interpretation skills.
- Improved the ability to communicate findings from structured data.

## 🔮 Future Improvements

- Build an interactive dashboard using Power BI or Tableau.
- Extend the analysis with SQL queries.
- Compare content trends across streaming platforms.
- Develop a recommendation system using content attributes.

## 👨‍💻 Author

**Mohammed Shoaib**

BCA Graduate | Aspiring Data Analyst

- **GitHub:** [mohammedshoaib3146-collab](https://github.com/mohammedshoaib3146-collab)
- **Project Repository:** [EDA Project on Amazon Prime Video](https://github.com/mohammedshoaib3146-collab/EDA-project-on-Amazon-Prime-Video)

---

⭐ If you find this project interesting, feel free to explore the repository and share your feedback.

*This project is intended for educational and analytical purposes. Amazon Prime Video is a trademark of Amazon; this project is not affiliated with or endorsed by Amazon.*
