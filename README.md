
# Mega Data Engineering Project

A simple demonstration project showing:
- ETL (DuckDB + Pandas)
- Big Data Processing (PySpark)
- Dashboard (Streamlit)

This project demonstrates a complete data engineering workflow, from raw data extraction to dashboard visualization. It showcases ETL pipelines, big data processing with Spark, and interactive visualizations — all designed to meet the requirements of a Senior Data Engineer role.

## Project Structure

| Notebook | Description |
|----------|-------------|
| `01_ETL.ipynb` | Extract, Transform, and Load multiple datasets from external sources. Demonstrates data cleaning, validation, and preparation. |
| `02_BigData.ipynb` | Load datasets into Spark DataFrames, perform data aggregation, joins, and transformations. Demonstrates handling large datasets efficiently. |
| `03_Dashboard.ipynb` | Visualize insights using `matplotlib`, `seaborn`, and `Plotly`. Includes static and interactive charts summarizing the datasets. |

## Datasets

- Data is pulled dynamically from online sources, no local CSV files required.  
- Sample datasets used:
  - [Air Travel Dataset](https://people.sc.fsu.edu/~jburkardt/data/csv/airtravel.csv)  
  - [Retail Addresses Dataset](https://people.sc.fsu.edu/~jburkardt/data/csv/addresses.csv)  

## How to Run

1. Open the notebooks in **[Google Colab](https://colab.research.google.com/)**.  
2. Run each notebook **sequentially** from top to bottom.  
3. All required Python packages are installed automatically in Colab.  

## Key Skills Demonstrated

- **ETL & Data Pipelines:** Python, Pandas, PySpark  
- **Big Data Processing:** Spark DataFrames, Joins, Aggregations  
- **Data Modeling & Cleaning:** Handling structured datasets efficiently  
- **Visualization & Dashboarding:** Matplotlib, Seaborn, Plotly  
- **Version Control & Collaboration:** GitHub repository management  

## Requirements

- pandas  
- pyspark  
- duckdb  
- matplotlib  
- seaborn  
- plotly  

## Optional Enhancements

- Include screenshots of charts and dashboard visualizations.  
- Add explanations of transformations and insights in each notebook.  
- Use this repo as a portfolio project to demonstrate Senior Data Engineer skills.
