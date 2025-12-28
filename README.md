# Multi-Year-Chicago-Crime-Database-Design-ETL-and-Analytics
## Project Overview
This project focuses on the **design, ETL processing, and analytical exploration of multi-year Chicago crime data** . It demonstrates how raw, large-scale public safety data can be transformed into a structured analytical database and used to uncover long-term crime trends and patterns.
The project covers **database design, data ingestion, cleaning, transformation, SQL-style analytics, and visualization, following an end-to-end data engineering and analytics workflow**.
## Objectives
- Design a structured database for multi-year Chicago crime data

- Build ETL pipelines to clean and transform raw crime records

- Perform analytical queries to identify crime trends and patterns

- Visualize long-term changes in crime occurrence and arrest rates

- Demonstrate end-to-end data engineering and analytics skills

## Analytical & ETL Approach
### Stage 1: Database Design & Data Ingestion

#### Notebook: Multi-Year Chicago Crime Database Design, ETL, and Analytics Part1.ipynb

- Designed a normalized schema for Chicago crime data

- Ingested raw crime records spanning multiple years

- Cleaned and standardized columns (dates, locations, crime types)

- Handled missing and inconsistent values

- Prepared structured tables suitable for analytical queries

### Stage 2: ETL Processing & Feature Engineering

- Transformed raw data into analysis-ready formats

- Created derived features such as:
  
  1. crime year, month, and day
  2. Arrest indicators
  3. Crime category grouping

- Ensured data integrity and consistency across years

- Optimized data for querying and aggregation

### Stage 3: Analytics & Visualization

#### Notebook: Multi-Year Chicago Crime Database Design, ETL, and Analytics Part2.ipynb

- Performed analytical queries to explore:

    1. Year-over-year crime trends
    2. Arrest vs non-arrest patterns
    3. Crime type distributions

- Conducted trend analysis across multiple years
- Visualized results using Python to support data-driven insights

## Key Insights & Findings

- Identified long-term trends in total crime counts across years
- Observed changes in arrest rates relative to crime occurrence
- Highlighted differences in crime patterns by category and time
- Demonstrated how structured ETL enables scalable analytics on public safety data

## Tools & Technologies

- **Programming Language:** Python

- **Libraries:** pandas, NumPy, matplotlib, seaborn

- **Data Engineering:** ETL pipelines, schema design

- **Analytics:** Aggregation, trend analysis, visualization

- **Environment:** Jupyter Notebook

## Repository Structure
```
chicago-crime-etl-analytics/
├── notebooks/
│   ├── Multi-Year Chicago Crime Database Design, ETL, and Analytics Part1.ipynb
│   └── Multi-Year Chicago Crime Database Design, ETL, and Analytics Part2.ipynb
|   |__ README.md
├── README.md
├── requirements.txt
└── .gitignore
```
## How to Run the Project

- Clone the repository:
  ```
git clone https://github.com/your-username/chicago-crime-etl-analytics.git

```
- Install dependencies
```
pip install -r requirements.txt

```
- Launch Jupyter Notebook
```
jupyter notebook
```
- Run notebooks in order:
```
- Multi-Year Chicago Crime Database Design, ETL, and Analytics Part1.ipynb

- Multi-Year Chicago Crime Database Design, ETL, and Analytics Part2.ipynb
```
