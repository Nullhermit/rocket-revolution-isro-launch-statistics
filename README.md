# 🚀 Rocket Revolution: A Statistical Study of ISRO’s Launch Activities (2005–2025)

## Overview

**Rocket Revolution** is a data analysis project that studies the launch activities of the Indian Space Research Organisation (ISRO) between 2005 and 2025.

Using publicly available mission records from ISRO, the project applies statistical methods and data visualisation techniques to explore annual launch frequency, compare the usage of different launch vehicles, and examine patterns in India's launch activities over time.

The project demonstrates how historical space-mission data can be organised, analysed, and presented to derive meaningful insights using Python.

## Objectives

* Compile ISRO launch mission records for the period 2005–2025.
* Calculate annual launch counts and examine changes over time.
* Compare the frequency of use of different launch vehicles.
* Analyse recorded mission outcomes.
* Present findings through statistical summaries, tables, and visualisations.

## Key Features

📊 **Annual Launch Analysis**
Examines the number of launches conducted each year and visualises changes over the study period.

🛰️ **Launch Vehicle Comparison**
Compares the frequency of use of launch vehicles such as PSLV, GSLV Mk II, LVM3, and SSLV.

📈 **Data Visualisation**
Uses line charts, bar charts, and additional figures to communicate patterns in the dataset.

🔢 **Statistical Analysis**
Uses descriptive statistics and selected statistical tests to investigate launch frequency and changes over time.

✅ **Mission Outcome Analysis**
Examines recorded mission outcomes to provide an additional perspective on ISRO's launch activities.

## Dataset and Source

The project uses secondary data compiled from ISRO's official launch mission records.

**Primary source:** [ISRO — Launch Missions](https://www.isro.gov.in/ISRO_EN/LaunchMissions.html)

**Study period:** 1 January 2005 – 31 December 2025

The dataset includes information such as launch date, launch year, launch vehicle, and mission outcome where available.

Certain technology-demonstration records and suborbital missions may require separate classification when calculating launch statistics. These methodological decisions are documented in the analysis.

## Tools and Technologies

* **Python** — data analysis and computation
* **Pandas** — data organisation and manipulation
* **NumPy** — numerical operations
* **Matplotlib** — charts and visualisation
* **SciPy** — statistical testing
* **Jupyter Notebook** — interactive analysis

## Repository Structure

```text
rocket-revolution-isro-launch-statistics/
├── ISRO_Launch_Statistical_Study.ipynb
├── isro_launches_2005_2025.csv
├── isro_launch_study.py
├── figures/
├── tables/
└── README.md
```

*The figures, tables, CSV, and Python script are generated or used by the analysis workflow. The available files may vary depending on which outputs are included in the repository.*

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/rocket-revolution-isro-launch-statistics.git
cd rocket-revolution-isro-launch-statistics
```

Replace `YOUR-USERNAME` with your GitHub username.

### 2. Install the dependencies

```bash
pip install pandas numpy matplotlib scipy jupyter
```

### 3. Open the Jupyter Notebook

```bash
jupyter notebook ISRO_Launch_Statistical_Study.ipynb
```

Alternatively, open the notebook using [Google Colab](https://colab.research.google.com/) or Visual Studio Code.

Run the notebook cells in order to reproduce the analysis, tables, and charts. If the notebook contains the dataset directly, a separate CSV file may not be required to run it.

## Methodology

The analysis follows these general steps:

1. **Data collection:** Compile mission records from ISRO's official launch database.
2. **Data preparation:** Organise dates, launch years, vehicle categories, and outcome information.
3. **Descriptive analysis:** Calculate annual frequencies and summary statistics.
4. **Comparative analysis:** Examine launch vehicle usage and changes over time.
5. **Visualisation:** Create charts and tables to present the results.
6. **Interpretation:** Discuss observed patterns, limitations, and classification decisions.

## Scope and Limitations

This project focuses on historical data analysis and descriptive statistical methods. It does not involve satellite-image processing, machine learning, or complex predictive modelling.

The results depend on the completeness and classification of the source records. Mission counts and outcome statistics should therefore be interpreted according to the definitions used in the notebook.

## Expected Outcome

The project provides a statistical overview of ISRO's launch activities between 2005 and 2025. It illustrates how real-world space-science data can be used to examine trends, compare categories, and communicate findings through data visualisation.

## Acknowledgements

Data source: [Indian Space Research Organisation (ISRO)](https://www.isro.gov.in/)

This project was developed as an exploration of the intersection between space exploration, statistics, and data analytics.

---

**Project:** Rocket Revolution
**Domain:** Space Science and Data Analytics
**Study Period:** 2005–2025
**Language:** Python
