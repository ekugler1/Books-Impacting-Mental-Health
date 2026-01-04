
# Mental Health Book Publications and Suicide Rates Analysis

## Project Overview
This project explores the relationship between the number of mental health–related books published over time and suicide rates in the United States. The motivation behind this analysis was to examine how cultural indicators of mental health awareness—represented by book publications—align with changes in suicide rates across different historical periods.

By combining data from a public book database and U.S. government health statistics, this project aims to understand broader social trends related to mental health awareness, access to resources, and public well-being.

## Research Question
Is there a relationship between trends in mental health–related book publications and suicide rates in the United States over time?

## Data Sources
- **Open Library API**  
  Used to collect data on books related to mental health, focusing on publication year.
- **CDC / Data.gov Suicide Rate Dataset**  
  Used to obtain historical suicide rate estimates in the United States.

Both datasets were publicly available and accessed via APIs.

## Methodology
- Queried the Open Library Search API for English-language books related to mental health
- Extracted and cleaned publication year data
- Aggregated the number of mental health books published per year
- Cleaned and processed CDC suicide rate data
- Merged datasets by year for comparative analysis
- Visualized trends using line plots and scatter plots

This analysis focuses on **temporal trends** rather than causal inference.

## Key Visualizations
- Number of mental health books published over time
- Suicide rates in the United States over time
- Combined scatter plot showing trends in book publications and suicide rates across years

These visualizations highlight periods of clustering that may reflect broader social, cultural, or political contexts.

## Findings
- Mental health book publications show a general increase over time, with notable growth in the late 20th and early 21st centuries.
- Suicide rates fluctuate significantly across decades, suggesting the influence of multiple external factors.
- Certain periods show lower suicide rates coinciding with higher numbers of mental health book publications, while other periods show higher suicide rates with fewer publications.

While these patterns do **not imply causation**, they suggest that periods of increased mental health awareness and resource availability may align with improved mental health outcomes.

## Interpretation & Implications
The results highlight the importance of cultural and informational resources in shaping mental health awareness. Periods with low publication counts and high suicide rates may indicate gaps in public discourse or access to mental health resources. Conversely, periods with increased publication activity may reflect greater societal attention to mental health issues.

This project provides a foundation for further research incorporating additional contextual variables such as economic conditions, media influence, or public health interventions.

## Tools & Technologies
- Python
- Requests
- Pandas
- NumPy
- Matplotlib

## Project Format
This project is presented as a static HTML report exported from a Python-based analysis to emphasize clarity, accessibility, and interpretability of results.

## Notes
This analysis is exploratory and intended to identify trends rather than establish causal relationships. All data used in this project was obtained from publicly available sources.
