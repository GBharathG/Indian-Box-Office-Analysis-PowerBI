# Indian Box-Office Analysis | Power BI Dashboard

## Project Overview

This project presents an interactive **Power BI dashboard for analyzing Indian film and box-office performance**.

The analysis explores movie releases, budgets, worldwide collections, IMDb ratings, genres, languages, directors, actors, film industries, OTT platforms, runtime, overseas collections, and seasonal release patterns.

The dashboard was developed to answer key business and analytical questions related to film performance and identify patterns that influence box-office success.

---

## Objectives

The main objectives of this project are to:

- Analyze overall Indian film and box-office performance
- Track total films, budgets, collections, and IMDb ratings
- Identify the top-performing films by worldwide collection
- Analyze annual film release patterns
- Compare first-day collections with worldwide collections
- Evaluate genre performance using IMDb ratings
- Analyze the relationship between film budgets and worldwide collections
- Identify directors associated with high-performing films
- Analyze language-wise film performance
- Compare OTT platform performance
- Examine the relationship between lead actors and IMDb ratings
- Compare different Indian film industries
- Identify seasonal and monthly box-office patterns
- Analyze runtime in relation to box-office performance and IMDb ratings
- Examine overseas collection performance
- Identify films achieving high returns with relatively low budgets
- Analyze the relationship between IMDb ratings and commercial performance

---

## Dashboard

The Power BI dashboard contains multiple pages covering the required analytical questions.

### Key KPIs

The main dashboard provides the following KPIs:

| KPI | Value |
|---|---:|
| Total Films | 604 |
| Total Budget | 34.65K Crores |
| Total Worldwide Collection | 79.88K Crores |
| Average IMDb Rating | 6.44 |

---

## Key Dashboard Visuals

### 1. Top 10 Films by Worldwide Collection

A comparison of the highest-grossing films based on worldwide box-office collection.

The dashboard highlights films such as:

- Dangal
- Baahubali 2: The Conclusion
- RRR
- K.G.F: Chapter 2
- Jawan
- Pathaan
- Kalki 2898-AD
- Bajrangi Bhaijaan
- Animal
- Secret Superstar

---

### 2. Annual Film Release Trends

A year-wise analysis of the number of films released.

This helps identify changes in film production and release volumes across different years.

---

### 3. Budget and Worldwide Collection Analysis

The dashboard examines the relationship between:

- Film Budget
- Worldwide Collection

This helps identify films that generated substantial collections relative to their production budgets.

---

### 4. IMDb Rating Analysis

Film ratings are analyzed across different dimensions such as:

- Genre
- Actors
- Directors
- Film industries
- Languages

This provides a view of audience/critic rating patterns across the Indian film industry.

---

### 5. Language Analysis

The dashboard compares film performance across different languages and identifies languages associated with higher box-office performance.

---

### 6. Film Industry Comparison

Different Indian film industries are compared using metrics such as:

- Number of films
- Worldwide collection
- Average IMDb rating
- Budget
- Box-office performance

---

### 7. OTT Platform Analysis

The project analyzes films available across different OTT platforms and examines their popularity and performance.

---

### 8. Director and Actor Analysis

The dashboard examines the performance of directors and lead actors using metrics such as:

- Average IMDb rating
- Worldwide collection
- Number of films
- Box-office performance

---

### 9. Seasonal and Monthly Trends

Film performance is analyzed across different months and periods to identify potential seasonal patterns in box-office performance.

---

### 10. Overseas Collection Analysis

The project analyzes overseas collections to identify films with strong international box-office performance.

---

## Tools & Technologies

- **Power BI Desktop**
- **Power Query**
- **DAX**
- **Microsoft Excel**

---

## Data Modeling

The Power BI model uses a structured dimensional approach with tables including:

- `Boxoffice_Fact`
- `Boxoffice_Fact (2)`
- `Calendar`
- `Director_dim`
- `Genre_dim`
- `Language_dim`

The model supports analysis across multiple dimensions such as:

- Time
- Directors
- Genres
- Languages
- Film performance

---

## Dashboard Features

- KPI Cards
- Bar Charts
- Line Charts
- Comparative Analysis
- Year-wise Trends
- Top N Analysis
- Interactive Filtering
- Cross-filtering
- Dimensional analysis
- DAX-based calculations
- Power Query data transformation

---

## Key Questions Addressed

The dashboard addresses 18 analytical questions covering:

1. Film KPIs such as total films and total budget
2. Top 10 films by worldwide collection
3. Annual release patterns
4. First-day vs worldwide collections
5. Genre performance based on IMDb ratings
6. Budget vs worldwide collection relationship
7. Director performance
8. Language trends
9. OTT platform performance
10. Lead actor performance
11. Film industry comparison
12. Seasonal box-office patterns
13. Consistently high-performing actors
14. Runtime vs box-office/IMDb rating
15. Overseas collection performance
16. High-return films with relatively low budgets
17. IMDb rating vs box-office performance
18. Performance comparison across industries

---

## Insights

The dashboard provides an interactive view of Indian film performance and enables users to explore relationships between production investment, audience ratings, domestic and international collections, film characteristics, and industry-level performance.

The analysis can be used to understand:

- Which films generated the highest worldwide collections
- How film release volumes changed over time
- How budgets relate to box-office collections
- How ratings vary across genres and other dimensions
- How different languages and industries perform
- Which films demonstrate strong returns relative to their budgets
- How overseas markets contribute to overall performance
- Whether release timing and seasonality are associated with box-office outcomes

---

## Project Structure

```text
Indian-Box-Office-Analysis-PowerBI/
│
├── Indian_Box_Office_Analysis.pbix
├── README.md
│
├── Dataset/
│   └── Indian_Box_Office_Data.xlsx
│
└── Screenshots/
    ├── dashboard-overview.png
    ├── top-films.png
    └── insights.png
