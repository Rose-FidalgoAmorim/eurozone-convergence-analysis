# Economic Convergence in Selected Eurozone Economies (2000–2023)

## Project Overview

This project investigates whether five major Eurozone economies — **Belgium, France, Germany, Italy and Spain** — converged or diverged in terms of **GDP growth, inflation and unemployment** between **2000 and 2023**.

Although these countries share a common monetary framework under the **European Central Bank (ECB)**, their economic trajectories have significantly diverged over time. The objective of this analysis is to distinguish between:

- **Common cyclical patterns**, caused by shared economic shocks such as the 2008 financial crisis and the COVID-19 pandemic;
- **Structural differences**, reflected in persistent gaps in growth performance, inflation stability and labour-market outcomes.

The project combines:

- a **Python-based economic analysis notebook** for data preparation, exploration and statistical analysis;
- a **Power BI dashboard** for interactive data visualisation and business-oriented communication.

The final output provides both technical analysis and economic interpretation, with insights on convergence challenges within the Eurozone.

---

# Research Question

**To what extent did Belgium, France, Germany, Italy and Spain converge or diverge in GDP growth, inflation and unemployment between 2000 and 2023?**

---

# Project Objectives

The analysis aims to:

- Compare long-term economic performance across selected Eurozone economies;
- Identify similarities and differences in economic cycles;
- Analyse the impact of major crises;
- Evaluate inflation stability relative to the ECB's 2% target;
- Study structural differences in unemployment;
- Communicate economic insights through interactive dashboards.

---

# Project Outputs

This repository contains:

- Three raw World Bank indicator datasets;
- A complete Jupyter Notebook containing:
  - data cleaning;
  - transformation pipeline;
  - exploratory data analysis;
  - descriptive statistics;
  - correlation analysis;
  - SQL-based analysis;
  - economic interpretation;
- A four-page Power BI dashboard;
- Dashboard screenshots and PDF export;
- Documentation explaining methodology, findings and limitations.

---

# Technologies & Skills

## Tools

- Python
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
- Jupyter Notebook
- SQL (SQLite)
- Power BI
- Power Query
- DAX
- GitHub

## Skills Demonstrated

- Data cleaning and transformation
- Exploratory Data Analysis (EDA)
- Time-series analysis
- Cross-country economic comparison
- Statistical correlation analysis
- SQL querying
- Dashboard creation
- Data storytelling
- Business and policy-oriented insights
- Technical documentation

---

# Data

## Source

**World Development Indicators — World Bank**

The dataset is publicly available from the World Bank database.

## Period

**2000–2023**

## Countries Analysed

The main analysis focuses on five Eurozone economies:

- Belgium
- France
- Germany
- Italy
- Spain

The European Union aggregate is included in selected Power BI visualisations as a benchmark but excluded from country rankings and main conclusions.

---

# Indicators

| Indicator | Description | World Bank Code |
|---|---|---|
| GDP Growth | Annual percentage growth rate of GDP | NY.GDP.MKTP.KD.ZG |
| Inflation | Consumer price inflation (annual %) | FP.CPI.TOTL.ZG |
| Unemployment | Total unemployment rate (% of labour force) | SL.UEM.TOTL.ZS |

---

# Data Preparation

The original World Bank data was downloaded as three separate CSV files:

- GDP growth dataset
- Inflation dataset
- Unemployment dataset

The preparation pipeline included:

1. Removing World Bank metadata rows;
2. Selecting the relevant countries and years;
3. Reshaping datasets from wide format to long format;
4. Converting years and indicators into numerical formats;
5. Merging the three indicators using country and year;
6. Checking missing values and data consistency;
7. Creating a final analysis-ready dataset.

The final structure used for analysis:

| Country | Year | GDP Growth | Inflation | Unemployment |
|---|---|---|---|---|
| Belgium | 2000 | 3.72 | 2.54 | 6.59 |
| Germany | 2000 | 2.88 | 1.44 | 7.92 |
| Spain | 2000 | 5.20 | 3.43 | 13.79 |

---

# Key Findings

## GDP Growth

The five economies followed broadly similar economic cycles, particularly during major external shocks.

Main observations:

- All countries experienced significant contractions during the 2008 financial crisis and the COVID-19 pandemic.
- Spain recorded the strongest GDP contraction in the dataset, reaching **-10.94% in 2020**.
- Italy showed the weakest long-term growth performance, with an average annual GDP growth rate of approximately **0.56% between 2000 and 2023**.
- Despite similar cycles, countries displayed persistent differences in long-term growth capacity.

The results suggest that a shared monetary environment does not automatically lead to economic convergence.

---

## Inflation

Inflation patterns were relatively similar across countries, especially during the low-inflation period of the 2010s.

Key observations:

- Inflation remained close to or below the ECB target for most of the decade before increasing sharply after 2021.
- During the 2022 inflation shock:
  - France recorded approximately **5.2% inflation**;
  - Germany recorded approximately **6.9%**;
  - Italy, Spain and Belgium exceeded **8%**;
  - Belgium reached approximately **9.6%**, the highest value in the sample.

France and Germany displayed the most stable inflation performance over the entire period.

---

## Unemployment

Unemployment represents the strongest evidence of structural divergence between countries.

Key findings:

- Spain experienced persistent unemployment challenges, reaching approximately **26% in 2013**.
- Germany significantly improved its labour market performance, reaching unemployment levels close to **3% in 2023**.
- Italy experienced long-term labour market difficulties, particularly after the Eurozone sovereign debt crisis.
- France and Belgium remained in an intermediate position.

The results indicate that economic growth alone does not fully explain unemployment differences. Structural factors such as labour-market institutions, skills mismatch and employment policies appear to play an important role.

---

# Cross-Indicator Analysis

The correlation analysis and GDP growth–unemployment comparison show that short-term economic growth does not fully explain labour-market outcomes.

Main observations:

- GDP growth and unemployment do not display a strong relationship in this sample.
- Spain maintained high unemployment even during periods of positive GDP growth.
- Germany achieved lower unemployment across different economic conditions.

These results suggest that structural characteristics influence labour-market performance.

**Important limitation:** these relationships are descriptive. Correlation does not imply causation.

---

# Power BI Dashboard

The project includes a four-page interactive Power BI dashboard designed to communicate the main economic insights.

## Dashboard Overview

![Overview Dashboard](images/overview.png)

The overview page presents:

- Average GDP growth;
- Average inflation;
- Average unemployment;
- Country filtering;
- Main comparative indicators.

---

## GDP Growth Dashboard

![GDP Growth Dashboard](images/gdp-growth.png)

This page analyses:

- Annual GDP growth evolution;
- Country comparison;
- European Union benchmark;
- Average GDP ranking;
- Impact of major crises.

---

## Inflation Dashboard

![Inflation Dashboard](images/inflation.png)

This page presents:

- Inflation trends by country;
- ECB 2% target reference;
- European Union comparison;
- Inflation stability comparison.

---

## Unemployment Dashboard

![Unemployment Dashboard](images/unemployment.png)

This page focuses on:

- Unemployment evolution;
- Cross-country comparison;
- Labour-market divergence;
- Long-term structural differences.

---
# Business and Policy Implications

## Labour Market Divergence

The persistent differences in unemployment rates highlight that economic growth alone is not sufficient to guarantee labour-market convergence.

The analysis suggests the importance of:

- Active labour-market policies;
- Skills development and education;
- Better matching between workers and employers;
- Reducing labour-market segmentation;
- Country-specific institutional reforms.

Spain and Italy illustrate that strong recovery phases can coexist with persistent unemployment challenges.

---

## Growth and Productivity

Italy's weak long-term GDP growth highlights deeper structural challenges beyond short-term economic cycles.

Potential areas for improvement include:

- Productivity growth;
- Innovation and investment;
- Human capital development;
- Business dynamism;
- Administrative efficiency.

Long-term economic performance depends not only on macroeconomic stability but also on structural competitiveness.

---

## Fiscal Coordination in the Eurozone

The existence of a common monetary policy means that Eurozone countries cannot independently adjust interest rates to country-specific shocks.

The results highlight the importance of:

- Coordinated fiscal policies;
- European investment mechanisms;
- Risk-sharing instruments;
- Maintaining fiscal buffers during economic expansions.

These mechanisms can help reduce divergence during asymmetric crises.

---

## Inflation Management

Inflation responses differed significantly across countries after 2021.

This demonstrates that a single monetary policy can have different effects depending on national economic structures.

Complementary national fiscal measures may therefore help address country-specific inflation pressures while maintaining overall monetary stability.

---

# SQL Analysis

To complement the Python analysis, the project includes SQL queries using SQLite.

The SQL analysis covers:

## Average Economic Indicators by Country

Comparison of:

- Average GDP growth;
- Average inflation;
- Average unemployment.

## Best and Worst GDP Performances

Identification of:

- Maximum GDP growth;
- Minimum GDP growth;
- Average performance.

## Inflation Target Analysis

Measurement of:

- Number of years above the ECB 2% inflation target;
- Average inflation during above-target years.

## Crisis Analysis

Comparison of major economic shocks:

- 2008 Financial Crisis;
- COVID-19 crisis.

The analysis shows that:

- COVID-19 produced the largest immediate GDP contraction;
- The 2008 crisis generated longer-lasting labour-market effects, especially in Spain.

---

# Repository Structure

```
eurozone-convergence-analysis/

│
├── eurozone_analysis.ipynb
│
├── API_NY.GDP.MKTP.KD.ZG_DS2_en_csv_v2_57.csv
├── API_FP.CPI.TOTL.ZG_DS2_en_csv_v2_285.csv
├── API_SL.UEM.TOTL.ZS_DS2_en_csv_v2_33398.csv
│
├── dashboard/
│   ├── eurozone_dashboard.pbix
│   └── eurozone_dashboard.pdf
│
├── images/
│   ├── overview.png
│   ├── gdp-growth.png
│   ├── inflation.png
│   └── unemployment.png
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

# How to Explore the Project

## Jupyter Notebook

The complete analysis is available in:

```
eurozone_analysis.ipynb
```

The notebook contains:

- Data preparation;
- Exploratory analysis;
- Visualisations;
- SQL queries;
- Economic interpretation.

The notebook is saved with outputs, allowing the analysis to be viewed directly on GitHub.

---

## Power BI Dashboard

The interactive dashboard can be opened with Power BI Desktop:

```
dashboard/eurozone_dashboard.pbix
```

A PDF export is also available:

```
dashboard/eurozone_dashboard.pdf
```

---

# How to Reproduce the Analysis

Clone the repository:

```bash
git clone https://github.com/[YOUR_USERNAME]/eurozone-convergence-analysis.git
```

Navigate to the project folder:

```bash
cd eurozone-convergence-analysis
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
eurozone_analysis.ipynb
```

Run all cells from the beginning.

The notebook and CSV files must remain in their original structure unless file paths are modified.

---

# Limitations

Several limitations should be considered:

- The study focuses on five Eurozone economies and does not represent the entire Eurozone.
- Only three macroeconomic indicators are analysed.
- The analysis is descriptive and does not establish causal relationships.
- Correlations may be influenced by common shocks and omitted variables.
- Period averages can hide important differences between economic phases.
- National indicators may hide regional and sectoral disparities.
- Formal econometric convergence tests were not performed.
- The analysis ends in 2023 and does not include more recent developments.

---

# Future Extensions

Possible improvements include:

- Adding productivity and GDP per capita indicators;
- Including public debt and investment variables;
- Expanding the sample to additional Eurozone countries;
- Performing formal beta and sigma convergence tests;
- Running panel regression models with country fixed effects;
- Analysing different economic periods separately:
  - pre-2008;
  - financial crisis;
  - sovereign debt crisis;
  - COVID-19;
  - post-COVID inflation period.

---

# Author

## Rose Fidalgo Amorim

Economics and Management student specialising in Applied Economics, with an interest in quantitative analysis, economic research and data analytics.

## Areas of Interest

- Data Analytics
- Business Intelligence
- Applied Economics
- Economic Research
- Quantitative Methods

---

# Contact

Feel free to explore the repository and connect for discussions about economics, data analysis and business intelligence projects.
---
**LinkedIn:** https://www.linkedin.com/in/rose-amorim-2287923a3/
**GitHub:** https://github.com/Rose-FidalgoAmorim
