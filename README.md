# Data-Doomsday

## Overview
This repository contains my solution for the Data Doomsday Challenge, where I analyze global disaster risk data to identify high-risk countries, correlate disaster frequencies, predict future disaster occurrences, and optimize resource allocation in the context of climate change and disaster preparedness.

The challenge uses two primary datasets:

1. **INFORM Risk Index** – Provides indicators of the risk levels of countries to various types of disasters, including natural hazards and environmental factors.

2. **EM-DAT Disaster Database** – Contains data on the frequency and impact of global disasters from 2000 to 2024.

## Project Objectives
1. **Risk Validation & Correlation Analysis:**
  Identify top high-risk countries based on INFORM Risk scores.
  Analyze disaster counts for top countries and correlate disaster frequency and affected population with INFORM risk scores.
  Predict disaster-prone countries using regression techniques on INFORM risk indicators.

2. **Predictive Modeling: Future Disaster Forecasting:**
  Predict disaster frequency for 2025 using moving averages.
  Use feature importance methods to identify the most predictive INFORM indicators for forecasting disaster types.
  Evaluate different feature selection methods to determine which subset of INFORM indicators performs best for disaster type prediction.

3. **Disaster Type-Specific Analysis:**
  Identify the most common global environmental risks based on disaster type frequency.
  Cluster countries by disaster type frequency and analyze regional similarities.
  Analyze discrepancies between high-risk predictions and actual disaster occurrences, considering factors such as underreporting, resilience policies, and emerging risks.

4. **Resource Allocation Optimization:**  
  Analyze aid distribution vs disaster impact to identify countries that are under-supported or over-supported.  
  Investigate the socioeconomic or geopolitical factors behind disparities in aid distribution.  
  Optimize resource allocation and compare the results with actual aid distributions, highlighting potential challenges to implementing new strategies.

5. **Climate Change & Disaster Risk Trends:**
  Analyze shifts in disaster frequency between 2000–2010 and 2011–2024 to understand the impact of climate change.
  Investigate climate-related factors contributing to increasing disaster frequency or INFORM risk scores.
  Identify emerging climate-related disaster hotspots and recommend proactive government responses.

6. **Policy & Government Readiness Assessment:**
  Analyze countries with high risk but low readiness and explain contributing factors.
  Propose investments or policy changes to reduce disaster vulnerability in high-risk areas with low infrastructure quality.
  Assess countries' disaster mitigation strategies and identify successful policies that reduce vulnerability.

## Key Findings
The **top 5 high-risk countries** were identified based on INFORM Risk scores, with disaster counts analyzed for the top 3 countries from the EM-DAT database.

A **heatmap** was generated to show the correlation between INFORM Risk scores and disaster frequency/affected population.

Predictive models were developed using **regression techniques** to forecast future disaster occurrences in 2025.

**Climate change** was identified as a contributing factor to increasing disaster frequency, with some regions emerging as **disaster hotspots** due to socio-environmental vulnerabilities.
