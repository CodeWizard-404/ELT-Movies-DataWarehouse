# Movie Data Warehouse and Analysis Project

## Project Overview
This project demonstrates the end-to-end process of building a **Data Warehouse** for movie data analysis. It includes the following:
1. **ETL Process**: Extract, Transform, and Load data using Talend.
2. **Data Warehouse Design**: A star schema implemented in a relational database.
3. **Power BI Dashboard**: Visualizations and KPIs for insights into movie data.

## Features
- **ETL Jobs**:
  - Data extraction from IMDb datasets.
  - Transformation and cleansing using Talend.
  - Loading into a relational database.

- **Data Warehouse**:
  - Star schema design with fact and dimension tables.
  - Optimized for movie data analysis.

- **Power BI Dashboard**:
  - Visualizations for top genres, directors, and production companies.
  - KPIs such as revenue trends, average ratings, and vote counts.

## Technologies Used
- **ETL Tool**: Talend Open Studio
- **Database**: MySQL/PostgreSQL (or your database choice)
- **Visualization Tool**: Power BI
- **Source Data**: IMDb datasets in TSV format

## Getting Started
1. **Prerequisites**:
   - Install [Talend Open Studio](https://www.talend.com/products/talend-open-studio/).
   - Set up a relational database (MySQL/PostgreSQL).
   - Install Power BI Desktop.

2. **Steps to Run**:
   - **ETL**:
     1. Import the Talend jobs from `/ETL_Jobs`.
     2. Execute jobs to populate the database.
   - **Power BI**:
     1. Open `MovieDashboard.pbix` in Power BI Desktop.
     2. Connect to your database and refresh the data.

## Visualizations
### Example Screenshots
1. **Dashboard Overview**:
   ![Dashboard Overview](PowerBI_Dashboard/screenshots/dashboard_overview.png)
2. **Genre Analysis**:
   ![Genre Analysis](PowerBI_Dashboard/screenshots/genre_analysis.png)

## Dataset Information
Source: [IMDb Datasets](https://www.imdb.com/interfaces/)

- **Files Used**:
  - `title.akas.tsv`
  - `title.basics.tsv`
  - `title.crew.tsv`
  - `title.principals.tsv`
  - `title.ratings.tsv`

