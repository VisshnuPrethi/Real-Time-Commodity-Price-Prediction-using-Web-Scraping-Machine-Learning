# Real-Time-Commodity-Price-Prediction-using-Web-Scraping-Machine-Learning
Project Overview

This project implements an end-to-end data pipeline to collect, store, process, and analyze near real-time commodity price data. Data is scraped from the TradingEconomics commodities website, stored in a PostgreSQL database, transformed using SQL and Python, and used to train machine learning models for price prediction.

The project demonstrates a real-world integration of web scraping, data engineering, and predictive analytics following industry-style workflows.

Tech Stack

- Programming Language: Python

- Web Scraping: Requests, BeautifulSoup

- Database: PostgreSQL

- Data Processing: Pandas, NumPy

- Machine Learning: Scikit-learn

- Visualization: Power BI

Project Workflow

Scrape near real-time commodity prices from TradingEconomics

Store raw and processed data in PostgreSQL

Clean and normalize data (currency, units, dates)

Perform feature engineering for time-series analysis

Train and evaluate multiple ML models

Select the best-performing model using evaluation metrics

Database Design

- PostgreSQL Tables

- commodities – commodity metadata

- commodity_prices – historical price data

Designed with primary and foreign keys to support efficient time-series queries.

Machine Learning Models

- Linear Regression

- Random Forest Regressor


Evaluation Metrics

- MAE

- MSE

- R² Score

Key Outcomes

Automated real-time data ingestion pipeline

Structured and scalable data storage using PostgreSQL

Improved prediction performance using time-series features

Identified best-performing model through comparative analysis

Limitations

Dependent on website structure

Limited external macroeconomic indicators

Near real-time data availability varies by commodity

Future Enhancements

Schedule scraping using Airflow or Cron

Add macroeconomic indicators

Apply advanced time-series models (ARIMA, LSTM)

Deploy dashboards using Power BI or Streamlit

Author

Visshnu Prethi Manjere Kumar
Master’s in Data Science & Computer Science
