# Career Preparedness Analysis

A comprehensive analysis of implicit and explicit factors driving career preparedness across global regions and industry sectors.

## Project Overview

This project analyzes primary research data assessing behavioral science-informed readiness factors that influence career preparedness. The study examines both emotional/psychological and workplace/functional categories using dual measurement approaches:

- **Implicit measures**: Reaction-time based fast choice tests (0-100 scale)
- **Explicit measures**: Traditional Likert-scale agreement scores

## Data Structure

- **Sample size**: 4,211 respondents across 6 global regions
- **Variables**: 97 total variables including demographics, personality traits, and latent factors. Some preparedness measures were constructed, but these were deprecated.
- **Regions**: France, DACH (Germany/Switzerland), Spain, USA, Italy, United Kingdom
- **Sectors**: Financial Services, Technology, Pharmaceutical, Energy

## Key Research Questions

1. What drives feelings of preparedness for career advancement?
2. Do people differ in what they report implicitly versus explicitly?
3. Do these differences vary by region and demographic factors?

## Pipeline Structure

```
├── data/                          # Raw and processed datasets
├── notebooks/                     # Analysis notebooks
│   ├── data_cleaning.ipynb       # Data preprocessing and quality checks
│   ├── factor_analysis_dimension_reduction.ipynb  # Factor extraction
│   ├── predicting_preparedness.ipynb  # Global driver analysis
│   ├── analysing_global_drivers.ipynb  # Country-level modeling
│   └── segmented_analysis.ipynb  # Audience segmentation
├── results/                       # Output visualizations and models
└── sources/                       # Reference materials
```

## Methodology

- **Factor Analysis**: Dimensional reduction of survey constructs
- **Hierarchical Regression**: Testing incremental predictive value
- **Cross-Cultural Validation**: Country-level model comparison
- **Behavioral Segmentation**: Identifying distinct audience profiles

## Key Outcomes

1. Global driver identification and comparison (implicit vs explicit)
2. Country-level factor importance analysis
3. Behavioral audience segmentation with profiles
4. Predictive models with validation metrics 
