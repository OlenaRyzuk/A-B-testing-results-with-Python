# Survey Data Analysis

## Description
This repository contains an analysis of survey data, including:
- Measures of central tendency (mean, median)
- Compensation analysis (`ConvertedCompYearly`) by country
- Distribution of education levels among respondents
- Relationships between work experience (`WorkExp`), programming languages, and compensation

## Technologies Used
- Python (pandas, numpy, matplotlib/seaborn)
- Jupyter Notebook
- GitHub for version control

## Project Structure
/project-folder
│
├─ data/ # raw and cleaned data
│ ├─ survey_results.csv
│ └─ ...
│
├─ notebooks/ # analysis notebooks
│ └─ survey_analysis.ipynb
│
├─ scripts/ # helper scripts
│ └─ data_cleaning.py
│
├─ README.md # this file
└─ requirements.txt # dependencies
## How to Run
1. Clone the repository:  
```bash
git clone https://github.com/yourusername/project-name.git
Install required packages:
pip install -r requirements.txt
Open the notebook:
jupyter notebook notebooks/survey_analysis.ipynb
Follow the notebook to explore the data and visualizations.
Key Findings
- Among respondents who program in Python, mean and median compensation varies by country.
- The top 5 respondents with the highest compensation have education levels of Bachelor’s degree (2) and Doctorate (3).
- Relationships between work experience and compensation were observed.
