# Amazon Prime Content Intelligence Dashboard | Tableau

An interactive **Tableau dashboard for analyzing the Amazon Prime Video content catalog**, with a focus on content mix, genres, ratings, release-year trends, and geographic distribution.

The goal is simple: turn a large catalog dataset into a visual analysis that makes **content patterns easy to compare and explore**.

## 🔗 Live Dashboard

**[View the interactive dashboard on Tableau Public](https://public.tableau.com/app/profile/bhaskar.nakka4980/viz/AmazonprimeAnalysis_17871481548780/AMAZONCONTENTINTELLIGENCEDASHBOARD)**

## 📸 Dashboard Preview

![Amazon Prime Content Intelligence Dashboard](images/AMAZON%20%20CONTENT%20INTELLIGENCE%20DASHBOARD.png)

![Amazon Prime Overview Dashboard](images/Amazon%20%20Overview%20Dashboard.png)

## What the analysis covers

The dashboard lets users explore:

- **Content mix** — Movies vs. TV Shows
- **Genre distribution** — which categories dominate the catalog
- **Ratings** — how titles are distributed across content ratings
- **Release trends** — how title volume varies by release year
- **Geographic distribution** — countries contributing titles to the catalog
- **Catalog diversity** — how the content mix varies across major dimensions

## Business questions

The dashboard is designed to answer questions such as:

- Is the catalog more heavily weighted toward Movies or TV Shows?
- Which genres and ratings have the largest representation?
- How does content volume change across release years?
- Which countries contribute the most titles?
- What does the overall catalog composition look like?

## Dashboard views

### Content Overview

Provides high-level KPIs and comparisons for total titles, Movies, TV Shows, countries, genres, and ratings.

### Release Trends

Shows how the number and distribution of titles changes across release years.

### Genre Analysis

Compares genre representation to highlight dominant and less-represented categories.

### Ratings Analysis

Explores the distribution of titles across audience/content ratings.

### Geographic Analysis

Examines country-level contribution and the geographic diversity of the catalog.

## Dataset

This project uses the **Amazon Prime Titles dataset** in CSV format.

Key fields include:

`show_id` · `type` · `title` · `director` · `cast` · `country` · `date_added` · `release_year` · `rating` · `duration` · `listed_in` · `description`

The dataset is included in the repository for reproducibility.

## Tech stack

- **Tableau** — dashboard development, visualization, and analysis
- **CSV** — source dataset
- **Git & GitHub** — version control and project hosting

## Skills demonstrated

- Exploratory Data Analysis
- Business Intelligence
- KPI Design
- Trend Analysis
- Geographic Analysis
- Interactive Dashboard Design
- Data Storytelling

## Repository structure

```text
amazon-prime-dashboard/
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

## Scope & limitation

This is an **analytics portfolio project** based on the supplied Amazon Prime titles dataset. The analysis describes that dataset and should not be treated as a complete or current representation of Amazon Prime Video's live catalog.

## Author

**Bhaskar Nakka** · [GitHub](https://github.com/bhaskar-nb) · [LinkedIn](https://www.linkedin.com/in/bhaskar-nakka-43a701259/)
