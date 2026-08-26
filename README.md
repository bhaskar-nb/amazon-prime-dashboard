# Amazon Prime Content Intelligence Dashboard | Tableau

An interactive **Tableau dashboard analyzing the Amazon Prime Video titles dataset** to understand catalog composition, genre and rating distribution, release trends, and geographic content patterns.

The project turns a large content catalog into a practical analytical view for comparing **what the catalog contains, how it has changed over time, and where its titles come from**.

## Live Dashboard

**[View the interactive dashboard on Tableau Public](https://public.tableau.com/app/profile/bhaskar.nakka4980/viz/AmazonprimeAnalysis_17871481548780/AMAZONCONTENTINTELLIGENCEDASHBOARD)**

## Dashboard Preview

![Amazon Prime Content Intelligence Dashboard](images/AMAZON%20%20CONTENT%20INTELLIGENCE%20DASHBOARD.png)

![Amazon Prime Overview Dashboard](images/Amazon%20%20Overview%20Dashboard.png)

## Why this project matters

Streaming catalogs contain thousands of titles, but raw catalog records are difficult to compare at a glance. This dashboard turns those records into a structured view of **content mix, audience ratings, genre concentration, release trends, and geographic distribution**.

It is designed to support fast exploration rather than make claims about Amazon Prime Video's current business performance.

## What the dashboard analyzes

- **Content mix** — Movies vs. TV Shows
- **Genre distribution** — representation of major content categories
- **Ratings** — distribution across content and audience ratings
- **Release trends** — title volume across release years
- **Geographic distribution** — countries represented in the catalog
- **Catalog composition** — how the mix varies across key dimensions

## Business questions

- Is the catalog more heavily weighted toward Movies or TV Shows?
- Which genres and ratings have the largest representation?
- How does title volume change across release years?
- Which countries contribute the most titles?
- What patterns stand out in the overall catalog composition?

## Dashboard Views

### Content Overview

High-level KPIs comparing total titles, Movies, TV Shows, countries, genres, and ratings.

### Release Trends

Shows how title volume varies across release years and helps identify periods with stronger catalog representation.

### Genre Analysis

Compares genre representation to identify dominant and less-represented categories.

### Ratings Analysis

Explores how titles are distributed across content ratings.

### Geographic Analysis

Examines country-level contribution to the catalog and its geographic diversity.

## Dataset

This project uses the **Amazon Prime Titles** dataset in CSV format.

Key fields include:

`show_id` · `type` · `title` · `director` · `cast` · `country` · `date_added` · `release_year` · `rating` · `duration` · `listed_in` · `description`

The dataset is included in the repository for reproducibility.

## Tech Stack

- **Tableau** — dashboard development, visualization, and analysis
- **CSV** — source dataset
- **Git & GitHub** — version control and project hosting

## Skills Demonstrated

- Exploratory Data Analysis
- Business Intelligence
- KPI Design
- Trend Analysis
- Geographic Analysis
- Interactive Dashboard Design
- Data Storytelling

## Repository Structure

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

## Scope & Limitation

This is an **analytics portfolio project** based on the supplied Amazon Prime titles dataset. The findings describe that dataset and should not be treated as a complete or current representation of Amazon Prime Video's live catalog, current strategy, audience behavior, or business performance.

## Author

**Bhaskar Nakka** · [GitHub](https://github.com/bhaskar-nb) · [LinkedIn](https://www.linkedin.com/in/bhaskar-nakka-43a701259/)
