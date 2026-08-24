# Amazon Prime Content Intelligence Dashboard | Tableau

An interactive Tableau dashboard that analyzes the **Amazon Prime Video content catalog** to reveal patterns in content type, genres, ratings, countries, and release years.

The project turns a large entertainment dataset into an easy-to-explore view of **catalog composition and content trends**.

## 🔗 Live Dashboard

**[View the interactive dashboard on Tableau Public](https://public.tableau.com/app/profile/bhaskar.nakka4980/viz/AmazonprimeAnalysis_17871481548780/AMAZONCONTENTINTELLIGENCEDASHBOARD)**

## 📸 Dashboard Preview

![Amazon Prime Content Intelligence Dashboard](images/AMAZON%20%20CONTENT%20INTELLIGENCE%20DASHBOARD.png)

![Amazon Prime Overview Dashboard](images/Amazon%20%20Overview%20Dashboard.png)

## Why this project matters

A content library is more useful when you can quickly see **what it contains, how it is distributed, and how that mix changes over time**.

This dashboard helps explore:

- How the catalog is split between **Movies and TV Shows**
- Which **genres and ratings** are most represented
- How content volume changes across **release years**
- Which **countries** contribute the most titles
- How diverse the overall catalog is across major content dimensions

## Key questions answered

- Does the catalog lean more toward Movies or TV Shows?
- Which genres have the highest representation?
- Which content ratings appear most frequently?
- How has the volume of titles changed over time?
- Which countries contribute the most content?
- What does the overall catalog mix look like?

## Dashboard views

### Content overview
High-level KPIs and comparisons for total titles, Movies, TV Shows, countries, genres, and ratings.

### Release trends
Shows how the distribution of titles changes across release years and highlights periods with higher content volume.

### Genre analysis
Compares genre representation to identify dominant and less-represented content categories.

### Ratings analysis
Examines audience-rating distribution and differences across the catalog.

### Geographic analysis
Explores country-level contribution to the content library and its geographic diversity.

## Dataset

This project uses the **Amazon Prime Titles dataset** in CSV format.

Key fields include:

`show_id` · `type` · `title` · `director` · `cast` · `country` · `date_added` · `release_year` · `rating` · `duration` · `listed_in` · `description`

The dataset is included in the repository for reproducibility.

## Tech stack

- **Tableau** — data visualization, dashboard development, and analysis
- **CSV** — source dataset
- **Git & GitHub** — version control and project hosting

## Skills demonstrated

- Exploratory Data Analysis
- Business Intelligence
- Data Visualization
- KPI Design
- Trend Analysis
- Geographic Analysis
- Interactive Dashboard Design
- Data Storytelling

## Repository structure

```text
Amazon Prime Analysis/
│
├── data/
│   └── amazon_prime_titles.csv
│
├── images/
│   ├── AMAZON  CONTENT INTELLIGENCE DASHBOARD.png
│   └── Amazon  Overview Dashboard.png
│
├── tableau/
│   └── Amazon prime Analysis.twbx
│
└── README.md
```

## Notes

This is an **analytics portfolio project** based on the supplied Amazon Prime titles dataset. The findings describe the dataset and should not be treated as a complete or current representation of Amazon Prime Video's live catalog.

## Author

**Bhaskar Nakka** · [GitHub](https://github.com/bhaskar-nb) · [LinkedIn](https://www.linkedin.com/in/bhaskar-nakka-43a701259/)
