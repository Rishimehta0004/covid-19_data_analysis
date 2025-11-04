# COVID-19 Analysis and Prediction — Data Science Case Study

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

A comprehensive data analysis and machine learning project examining COVID-19 trends globally and within India. This repository contains exploratory data analysis, visualizations, state-wise analysis, and predictive models for case growth and hospital resource planning.

## 📊 Project Overview

- **Global Analysis**: Tracks COVID-19 progression across countries with comparative trends
- **India-Focused**: Deep-dive state-wise analysis of cases, recoveries, and deaths
- **Predictions**: Forecasting models for case growth and hospital bed requirements
- **Resources**: Health facility analysis including testing labs and hospital capacity

## 📁 Repository Structure

```
.
├── Covid 19 Analysis.ipynb       # Main notebook with all analysis
├── csv files/                    # Raw data files
│   ├── covid_19_data.csv
│   ├── covid_19_india.csv
│   ├── india_cases.csv
│   └── ...
├── requirements.txt              # Python dependencies
├── environment.yml               # Conda environment (optional)
├── CONTRIBUTING.md               # Contribution guidelines
├── CODE_OF_CONDUCT.md           # Community standards
└── .github/                      # GitHub workflows and templates
```

## 🚀 Quick Start

### Prerequisites
- Python 3.8+ or Conda
- Jupyter Notebook or JupyterLab

### Installation

**Option 1: Using pip**
```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

**Option 2: Using conda**
```bash
conda env create -f environment.yml
conda activate covid-analysis
```

### Running the Notebook

```bash
jupyter notebook "Covid 19 Analysis.ipynb"
```

Then navigate through the cells to explore the analysis. The notebook is self-contained and loads all required CSV files from the repository root.

## 📚 Notebook Contents

1. **Introduction**: Global overview of COVID-19 impact
2. **Country-by-Country Analysis**: China, Italy, USA, South Korea, UK, Germany, Japan, Australia
3. **Lockdown Impact**: Assessment across major countries
4. **India Deep-Dive**: State-wise trends and health facility analysis
5. **Predictions**: Growth forecasts and resource requirements
6. **Conclusions**: Key findings and insights

## 📋 Data Files

All CSV files are included in the repository:
- `covid_19_data.csv` — Global COVID-19 statistics
- `covid_19_india.csv` — India-specific data by date
- `india_cases.csv` — Individual case tracking (India)
- `IndividualDetails.csv` — Demographic details
- `AgeGroupDetails.csv` — Age-wise breakdown
- `HospitalBedsIndia.csv` — Hospital capacity by state
- `ICMRTestingLabs.csv` — Testing lab locations and capacity
- `statewise_tested_numbers_data.csv` — State-wise testing data

## 🔧 Development

### Code Style
Code follows Python best practices. Consider using:
```bash
pip install black isort flake8
black .
isort .
```

### Pre-commit Hooks (Optional)
```bash
pip install pre-commit
pre-commit install
pre-commit run --all-files
```

## 🤝 Contributing

Contributions are welcome! Please see `CONTRIBUTING.md` for guidelines.

## 📄 License

This project is licensed under the MIT License — see `LICENSE` for details.

## 📝 Citation

If you use this analysis in your work, please cite:

```
Sharma A. et al. (2022) Covid-19—Analysis and Prediction—A Case Study Using Machine Learning. 
In: Tavares J.M.R.S., Dutta P., Dutta S., Samanta D. (eds) Cyber Intelligence and Information Retrieval. 
Lecture Notes in Networks and Systems, vol 291. Springer, Singapore. 
https://doi.org/10.1007/978-981-16-4284-5_31
```

## ❓ Questions?

Open an issue or check existing discussions in the repository.

---

**Last Updated**: November 2025
**Data Snapshot**: November 2020
