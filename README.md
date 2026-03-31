# IBM Applied Data Science Capstone: SpaceX Predictive Analysis

**[View Course on Coursera](https://in.coursera.org/learn/applied-data-science-capstone)**

## Project Overview
This repository contains my capstone project for the IBM Applied Data Science professional certificate. It demonstrates the complete, end-to-end data science methodology applied to a real-world business scenario. 

**Objective:** Assuming the role of a Data Scientist for a competing aerospace startup, the primary goal of this project is to predict whether the SpaceX Falcon 9 first stage will land successfully. This predictive model helps estimate the cost of a launch, providing crucial competitive intelligence.

## Methodology & Project Structure
The project follows a standard data science pipeline. Below is the breakdown of the repository files aligned with each phase of the project:

| Phase | Associated Files | Description |
| :--- | :--- | :--- |
| **Data Collection** | `jupyter-labs-spacex-data-collection-api.ipynb`<br>`jupyter-labs-webscraping.ipynb` | Extracting historical launch data using the official SpaceX API and web scraping techniques (BeautifulSoup). |
| **Data Wrangling** | `labs-jupyter-spacex-Data wrangling.ipynb` | Cleaning, formatting, and preparing the raw datasets (`.csv` files) for analysis. |
| **EDA & SQL** | `eda-dataviz.ipynb`<br>`jupyter-labs-eda-sql-coursera.ipynb` | Performing Exploratory Data Analysis (EDA) using Pandas and writing SQL queries to extract key insights. |
| **Interactive Visualization** | `lab_jupyter_launch_site_location.ipynb`<br>`spacex_dash_app.py` | Building interactive maps (Folium) to analyze launch sites and creating a dynamic dashboard using Plotly Dash. |
| **Machine Learning** | `SpaceX_Machine Learning Prediction_Part_5.ipynb` | Training and evaluating classification models (Logistic Regression, SVM, Decision Trees, KNN) to predict landing success. |
| **Executive Summary** | `IBM-DataScience-SpaceX-Capstone-Spacex-ppt.pdf` | The final presentation detailing methodology, results, and actionable conclusions for stakeholders. |

## Datasets
The `csv` files included in this repository (`Spacex.csv`, `dataset_part_1.csv`, `spacex_web_scraped.csv`, etc.) represent the data at various stages of cleaning and processing throughout the pipeline.

## Technologies Used
* **Languages:** Python, SQL
* **Libraries:** Pandas, NumPy, Scikit-Learn, BeautifulSoup
* **Visualization:** Matplotlib, Seaborn, Folium, Plotly Dash
* **Environments:** Jupyter Notebook
