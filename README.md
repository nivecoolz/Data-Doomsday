# Data-Doomsday

Overview
This repository contains my solution for the Data Doomsday Challenge, where I analyze global disaster risk data to identify high-risk countries, correlate disaster frequencies, predict future disaster occurrences, and optimize resource allocation in the context of climate change and disaster preparedness.

The challenge uses two primary datasets:

INFORM Risk Index – Provides indicators of the risk levels of countries to various types of disasters, including natural hazards and environmental factors.

EM-DAT Disaster Database – Contains data on the frequency and impact of global disasters from 2000 to 2024.

Project Objectives
Risk Validation & Correlation Analysis:

Identify top high-risk countries based on INFORM Risk scores.

Analyze disaster counts for top countries and correlate disaster frequency and affected population with INFORM risk scores.

Predict disaster-prone countries using regression techniques on INFORM risk indicators.

Predictive Modeling: Future Disaster Forecasting:

Predict disaster frequency for 2025 using moving averages.

Use feature importance methods to identify the most predictive INFORM indicators for forecasting disaster types.

Evaluate different feature selection methods to determine which subset of INFORM indicators performs best for disaster type prediction.

Disaster Type-Specific Analysis:

Identify the most common global environmental risks based on disaster type frequency.

Cluster countries by disaster type frequency and analyze regional similarities.

Analyze discrepancies between high-risk predictions and actual disaster occurrences, considering factors such as underreporting, resilience policies, and emerging risks.

Resource Allocation Optimization:

Analyze aid distribution vs disaster impact to identify countries that are under-supported or over-supported.

Investigate the socioeconomic or geopolitical factors behind disparities in aid distribution.

Optimize resource allocation and compare the results with actual aid distributions, highlighting potential challenges to implementing new strategies.

Climate Change & Disaster Risk Trends:

Analyze shifts in disaster frequency between 2000–2010 and 2011–2024 to understand the impact of climate change.

Investigate climate-related factors contributing to increasing disaster frequency or INFORM risk scores.

Identify emerging climate-related disaster hotspots and recommend proactive government responses.

Policy & Government Readiness Assessment:

Analyze countries with high risk but low readiness and explain contributing factors.

Propose investments or policy changes to reduce disaster vulnerability in high-risk areas with low infrastructure quality.

Assess countries' disaster mitigation strategies and identify successful policies that reduce vulnerability.

Bonus: Creativity & Visualization:

Create a short retro-style "mission briefing" or cutscene explaining key disaster risks in a selected country.

Design a retro game-inspired interface for visualizing disaster risk data.

Build a storytelling experience (e.g., playable narrative, comic panel, or timeline animation) to demonstrate the impact of preparedness levels and risk scores on disaster outcomes.

Project Structure
bash
Copy
Edit
.
├── data/
│   ├── emdat.csv            # EM-DAT Disaster Database
│   ├── inform_risk.csv      # INFORM Risk Index
├── notebooks/
│   ├── 01_data_cleaning.ipynb   # Data cleaning and preparation notebook
│   ├── 02_exploratory_analysis.ipynb  # EDA & trend analysis
│   ├── 03_modeling.ipynb     # Modeling and predictions (regression, feature selection)
│   ├── 04_visualization.ipynb # Visualizations and dashboard
├── src/
│   ├── data_preprocessing.py   # Data cleaning and preprocessing functions
│   ├── feature_engineering.py  # Feature extraction and transformation functions
│   ├── modeling.py            # Model training and evaluation scripts
│   ├── visualization.py       # Visualization functions (heatmaps, charts, etc.)
├── results/
│   ├── disaster_analysis.pdf   # Summary of disaster analysis and findings
│   ├── predictive_model_results.csv # Results from predictive models
├── README.md                   # This file
└── requirements.txt             # Python package dependencies
Requirements
To run this project, you will need to install the following Python packages:

pandas

numpy

scikit-learn

matplotlib

seaborn

plotly

tensorflow (for predictive modeling)

jupyter (for running notebooks)

Install the dependencies by running:

bash
Copy
Edit
pip install -r requirements.txt
Setup and Usage
Clone this repository:

bash
Copy
Edit
git clone https://github.com/yourusername/data-doomsday-challenge.git
cd data-doomsday-challenge
Prepare the environment:

Create a virtual environment and activate it:

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run Notebooks:

Open the Jupyter notebooks to explore the analysis and modeling steps:

bash
Copy
Edit
jupyter notebook
Navigate through the notebooks and run the cells to generate insights and predictions.

Key Findings
The top 5 high-risk countries were identified based on INFORM Risk scores, with disaster counts analyzed for the top 3 countries from the EM-DAT database.

A heatmap was generated to show the correlation between INFORM Risk scores and disaster frequency/affected population.

Predictive models were developed using regression techniques to forecast future disaster occurrences in 2025.

Climate change was identified as a contributing factor to increasing disaster frequency, with some regions emerging as disaster hotspots due to socio-environmental vulnerabilities.
