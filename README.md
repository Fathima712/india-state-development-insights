[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Fathima712/india-state-development-insights/blob/main/DEVELOPMENT_INSIGHT_DASHBOARD.ipynb)
# India State/UT Development Insights Dashboard

# Project Overview

This project analyzes development indicators across Indian States/UTs using selected data from the National Family Health Survey (NFHS-5).

The analysis focuses on four major development dimensions:

- Education
- Digital Inclusion
- Infrastructure
- Health

The project transforms selected indicators into comparable dimension scores and combines them into an overall development score to support descriptive comparison across 36 States/UTs.



# Objectives

The main objectives of this project are to:

- Analyze development indicators across Indian States/UTs.
- Compare educational outcomes between States/UTs.
- Examine digital inclusion indicators such as internet usage and mobile phone access.
- Evaluate infrastructure-related indicators.
- Analyze selected health indicators.
- Create dimension-level development scores.
- Calculate an overall development score.
- Rank States/UTs based on the composite score.
- Identify the strongest and weakest development dimensions for each State/UT.
- Present the findings through an interactive analytical dashboard.



# Dataset

The project uses selected State/UT-level indicators from:

**National Family Health Survey – NFHS-5**

The original dataset contains multiple demographic, socioeconomic, health and development indicators.

A selected subset of indicators was used for this project based on the four analytical dimensions.



# Development Dimensions

 1. Education

Selected indicators include:

- Women aged 15–49 who are literate
- Men aged 15–49 who are literate
- Women aged 15–49 with 10 or more years of schooling
- Men aged 15–49 with 10 or more years of schooling

 2. Digital Inclusion

Selected indicators include:

- Women aged 15–49 who have ever used the internet
- Men aged 15–49 who have ever used the internet
- Women aged 15–49 who have a mobile phone that they themselves use

 3. Infrastructure

Selected indicators include:

- Population living in households with electricity
- Population living in households with an improved drinking-water source
- Population living in households using an improved sanitation facility
- Households using clean fuel for cooking
- Households with members covered under a health insurance/financing scheme

 4. Health

Selected indicators include:

- Institutional births
- Children aged 12–23 months who are fully vaccinated
- Infant mortality rate



# Methodology

The project follows the following workflow:

```text
Raw NFHS-5 Dataset
        ↓
Data Cleaning
        ↓
Indicator Selection
        ↓
Data Transformation
        ↓
Dimension-Level Scoring
        ↓
Overall Development Score
        ↓
State/UT Ranking
        ↓
Development Gap Analysis
        ↓
Interactive Dashboard

 Data Source

National Family Health Survey (NFHS-5), 2019–21  
International Institute for Population Sciences (IIPS) and Ministry of Health & Family Welfare, Government of India.

Source: https://iipsindia.ac.in/content/india-and-stateuts-fact-sheets
