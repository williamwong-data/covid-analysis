# COVID-19 Data Analysis (Singapore with Comparative Reference)

## Executive Summary

This project performs a time-series analysis of COVID-19 case data in Singapore, with the objective of characterizing cumulative growth, daily incidence patterns, and underlying temporal trends. The analysis applies data cleaning, transformation, and visualization techniques to extract interpretable insights from raw case data.

In addition to univariate analysis, a comparative visualization is included to provide contextual benchmarking against another country, enabling relative interpretation of scale and variability in case trajectories.

## Problem Statement

The objective of this analysis is to:
	- Understand cumulative growth of COVID-19 cases over time
	- Characterize daily case variability and identify trends
	- Detect wave-like patterns and temporal shifts
	- Provide contextual comparison across regions
  
## Approach

1. **Data Preparation**
    - Loaded time-series dataset
	- Standardized date formatting
	- Handled missing and inconsistent values
	- Derived cumulative and daily case metrics

2. **Exploratory Data Analysis**
    - Analysed cumulative case progression
	- Examined daily fluctuations and volatility
	- Identified peaks, trends, and inflection points

3. **Visualization**
    - Generated time-series plots for total and daily cases
	- Applied smoothing techniques to reduce noise
	- Created comparative visualization for contextual reference

## Key Findings

    •	Singapore’s cumulative COVID-19 cases reached approximately **3 million by end-2024**, with the most rapid growth observed between mid-2022 and early 2023
	•	Raw daily case data exhibits significant volatility, with a peak **exceeding 130,000 cases in October 2022**, obscuring underlying trends without smoothing
	•	The 7-day smoothed trend reveals **at least five distinct infection waves** between 2020 and 2024, with wave magnitude increasing initially before stabilizing post-2023
	•	Singapore’s total case count (~3M) represents **approximately 3% of the USA’s total (~105M)**, broadly consistent with population differences while showing comparable wave dynamics

  ## Key Visualisations

### Singapore: Total COVID-19 Cases
![Singapore Total Cases](visuals/sg_total_cases.png)

### Singapore: Daily New Cases (Raw)
![Singapore Daily Cases](visuals/sg_daily_cases_raw.png)

### Singapore: Daily New Cases (Smoothed)
![Singapore Smoothed Daily Cases](visuals/sg_daily_cases_smoothed.png)

### Country Comparison (Trend Reference)
![Comparison](visuals/comparison.png)

## Tools & Technologies

	•	Python
	•	Pandas
	•	Matplotlib
	•	Jupyter Notebook

## Skills Demonstrated

	•	Time-series data analysis
	•	Data cleaning and preprocessing
	•	Feature derivation (cumulative vs daily metrics)
	•	Data visualization and storytelling
	•	Comparative analysis across datasets
	•	Interpretation of noisy real-world data

## How To Run

```
git clone https://github.com/williamwong-data/covid-analysis.git
cd covid-analysis
jupyter notebook
```

## Project Structure

```
covid-analysis/
├── notebooks/
├── visuals/
├── sql/
├── README.md
└── .gitignore
```

## Future Improvements

	•	Extend analysis to additional countries for broader comparison
	•	Incorporate per-capita normalization for more meaningful comparisons
	•	Build interactive dashboards using Plotly or Tableau
	•	Automate data ingestion and scheduled update

## Data Source

*Our World in Data — COVID-19 Dataset. Accessed 2024.*

*https://ourworldindata.org/covid-cases*

## Author

**William Wong**

## Portfolio Note

This project demonstrates practical application of data analysis workflows, including data preprocessing, exploratory analysis, and visualization. It reflects the ability to derive insights from time-series data and communicate findings in a structured and interpretable manner.
