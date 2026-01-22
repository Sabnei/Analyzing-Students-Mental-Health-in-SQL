# Analyzing Students' Mental Health in SQL

## Project Overview
This project focuses on analyzing the mental health of international students. We utilize **SQL** for data querying and **Python** (Pandas, Plotly/Seaborn) for visualization and deeper analysis.

Key areas of focus include:
- **Depression Scores (PHQ-9)**
- **Social Connectedness (SCS)**
- **Acculturative Stress (ASISS)**

## The Data
This survey was conducted in **2018** at an international Japanese university and the associated study was published in **2019**. It was approved by several ethical and regulatory boards.

The study found that international students have a higher risk of mental health difficulties compared to the general population, and that social connectedness and acculturative stress are predictive of depression.

### Key Definitions
- **Social Connectedness**: Measure of belonging to a social group or network.
- **Acculturative Stress**: Stress associated with learning about and integrating into a new culture.

[See paper for more info, including data description](https://www.mdpi.com/2306-5729/4/3/124)

## Prerequisites
- Python 3.9+
- Jupyter Notebook / Lab
- PostgreSQL Database

## Installation
1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Ensure your PostgreSQL database is running and accessible (see `docker-compose.yml` if using Docker).

## Usage
1. Open the notebook:
   ```bash
   jupyter lab notebooks/analysis.ipynb
   ```
2. Run the cells to load data, connect to the database, and perform the analysis.