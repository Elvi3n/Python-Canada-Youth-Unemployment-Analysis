# Canada Youth Unemployment Analysis
## Project Overview

This project investigates the trends and characteristics of youth unemployment in Canada (ages 15–24), using official labour market datasets spanning ~1978–2025. The goal is to highlight how economic downturns, structural changes disproportionately affect young workers.

## Motivation

Research shows youth are especially vulnerable in labour markets:

- Entry-level jobs (≤ 1 year experience) declined sharply in 2024 (Government of Canada, 2024).

- Youth unemployment currently exceeds the overall unemployment rate, with one of the largest gaps in decades (Gridneff, 2025).

- Growing AI adoption may be eroding entry-level roles by automating tasks historically performed by junior staff (Violino, 2025).

## Dataset Compilation

Open, authoritative sources from Statistics Canada:

Labour force by age group, monthly, seasonally adjusted
Table 14-10-0287-02 (https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1410028702)

Duration of unemployment, monthly, seasonally adjusted
Table 14-10-0342-01 (https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1410034201)

## Scope & Frequency

Temporal coverage: monthly (~1978–2025, depending on overlap across datasets).

Age group: 15–24 (the most consistent youth definition in Canadian labour force data).

## Methods

Data preprocessing and cleaning with pandas / numpy

Exploratory Data Analysis (matplotlib)

Time series exploration of unemployment rates and participation rates

Correlation analysis between participation and unemployment

Visualization of unemployment duration (short- vs. long-term)

## Results (Highlights)

Youth unemployment rate has risen sharply since 2022, reaching ~14.5% in 2025, which double the national average of .

Gap vs. adult unemployment is at its widest since 2010 (excluding the COVID-19 shock).

Unemployment duration: proportion of youth unemployed 27+ weeks has grown steadily, showing signs of structural job search frictions.

(Insert a key figure or GIF here, e.g., line plot of youth vs. adult unemployment, stacked duration area chart, correlation scatterplot.)

## How to Run

Clone the repo:

git clone https://github.com/<your-username>/canada-youth-unemployment.git
cd canada-youth-unemployment


Create & activate virtual environment:


python -m venv .venv
.\.venv\Scripts\activate   # (Windows)
source .venv/bin/activate  # (Mac/Linux)


Install requirements:

pip install -r requirements.txt


Open Jupyter Notebook:

jupyter notebook


Run Canada_Youth_Unemployment_Analysis.ipynb.


## License

MIT License (free to use with attribution).
