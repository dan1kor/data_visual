# Data Analysis & Visualization Toolkit

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

Сборник практических упражнений для улучшения навыков работы с запросами к БД, обработке и визуализации с помощью Python.

## ✨ Особенности

*   **Практика SQL**: Запросы к БД через `sqlite3` для извлечения данных.
*   **Работа с Pandas**: Comprehensive data cleaning, transformation, and aggregation techniques.
*   **A/B Тестирование**: A complete example of hypothesis testing implementation (`ex04`).
*   **Визуализация**: Creation of insightful plots with `matplotlib` and `seaborn`.
*   **Jupyter-Based**: All exercises are in interactive notebooks for easy exploration and learning.

## 📁 Project Structure
data_analysis_visual/  
│  
├── sql_pandas/ # Database & Data Wrangling  
│ ├── data  
│ │  └── checking-logs.sqlite  
│ ├── ex00_first_select.ipynb  
│ ├── ex01_subquery.ipynb  
│ ├── ex02_joins.ipynb 
│ ├── ex03_aggs.ipynb  
│ └── ex04_ab-test.ipynb # Complete A/B test implementation  
│  
└── visual/ # Data Visualization  
  ├── data  
  │ ├── ab-test.csv
  │  └── checking-logs.sqlite  
  ├── ex01_first_select.ipynb  
  ├── ex02_subquery.ipynb  
  ├── ex03_joins.ipynb 
  ├── ex04_aggs.ipynb  
  └── ex05_ab-test.ipynb # Complete A/B test implementation  

## 🛠️ Tech Stack

*   **Languages**: Python
*   **Database**: SQLite (`sqlite3`)
*   **Data Processing**: Pandas, NumPy
*   **Visualization**: Matplotlib, Seaborn, Pandas Plotting
*   **Environment**: Jupyter Notebook


## 📘 Exercise Overview

*   **sql_pandas/**
        ex01: Basic SQL queries (SELECT, WHERE, JOIN).

        ex02: Data preprocessing with Pandas (handling missing values, filtering).

        ex03: Data aggregation and grouping (GROUP BY, pivot tables).

        ex04: A/B Testing – Full hypothesis testing pipeline from data preparation to conclusion.

*   **visual/**
        ex01: Foundation plots with Matplotlib (line, bar, scatter, histogram).

        ex02: Statistical and advanced plots with Seaborn (heatmaps, pairplots, distribution plots).

        ex03: Creating multi-plot dashboards and customizing aesthetics for storytelling

**Note**: This is a learning project. The examples are designed to be clear and educational, illustrating common data analysis workflows.