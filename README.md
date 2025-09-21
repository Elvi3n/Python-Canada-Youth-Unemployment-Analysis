# Canada Youth Unemployment Analysis
## Project Overview

This project investigates the trends and characteristics of youth unemployment in Canada (ages 15–24), using official labour market datasets spanning ~1978–2025. The goal is to highlight how economic downturns, structural changes disproportionately affect young workers.

```
Python-Canada-Youth-Unemployment-Analysis/
├── data/              
├── cleaned_data/      
├── notebooks/         
├── reports/           
├── requirements.txt   
├── LICENSE
├── README.md 
```

## Motivation

Research shows youth are especially vulnerable in labour markets:

- Entry-level jobs (≤ 1 year experience) declined sharply in 2024 (Government of Canada, 2024).

- Youth unemployment currently exceeds the overall unemployment rate, with one of the largest gaps in decades (Gridneff, 2025).

- Growing AI adoption may be eroding entry-level roles by automating tasks historically performed by junior staff (Violino, 2025).

## Dataset Compilation

Open, authoritative sources from Statistics Canada:

- Labour force by age group, monthly, seasonally adjusted
    - Table 14-10-0287-02 (https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1410028701&pickMembers%5B0%5D=1.1&pickMembers%5B1%5D=3.1&pickMembers%5B2%5D=4.1&pickMembers%5B3%5D=5.1&cubeTimeFrame.startMonth=01&cubeTimeFrame.startYear=1976&cubeTimeFrame.endMonth=08&cubeTimeFrame.endYear=2025&referencePeriods=19760101%2C20250801)

- Duration of unemployment, monthly, seasonally adjusted
    - Table 14-10-0342-01 (https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1410034201&pickMembers%5B0%5D=1.1&pickMembers%5B1%5D=3.2&pickMembers%5B2%5D=4.1&pickMembers%5B3%5D=5.1&cubeTimeFrame.startMonth=01&cubeTimeFrame.startYear=1976&cubeTimeFrame.endMonth=08&cubeTimeFrame.endYear=2025&referencePeriods=19760101%2C20250801)

**Download Options > CSV - Download entire table**

## Scope & Frequency

Temporal coverage: monthly (~1978–2025, depending on overlap across datasets).

Age group: 15–24 (the most consistent youth definition in Canadian labour force data).

## Methods

- Data preprocessing and cleaning with pandas / numpy

- Exploratory Data Analysis (matplotlib)

- Time series exploration of unemployment rates and participation rates

- Correlation analysis between participation and unemployment

- Visualization of unemployment duration (short- vs. long-term)

## Key Results

- Youth unemployment rate has risen sharply since 2022, reaching ~14.5% in 2025, which double the national average of .

- Excluding the COVID-19 shock, gap vs. adult unemployment is at its widest since 2010 .

- Unemployment duration: proportion of youth unemployed 27+ weeks has grown steadily, showing signs of structural job search frictions.

<img width="1493" height="990" alt="unemploymentComparasion" src="https://github.com/user-attachments/assets/7a1dd6e1-9a0b-4f9e-bf87-a1a669cf4bba" />

## Set up

1) Clone the repo:

    git clone https://github.com/Elvi3n/Python-Canada-Youth-Unemployment-Analysis.git
   
    cd canada-youth-unemployment

3) Create & activate virtual environment:

    python -m venv .venv
   
    .\.venv\Scripts\activate   # (Windows)
   
    source .venv/bin/activate  # (Mac/Linux)

4) Install requirements:

    pip install -r requirements.txt

5) Run Notebook


## License

MIT License (free to use with attribution).
