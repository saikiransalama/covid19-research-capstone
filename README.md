# The Impact of COVID-19 Pandemic on Undergraduate Enrollment in the United States: A Quantitative Analysis

## Overview

This research project examines the profound impact of the COVID-19 pandemic on undergraduate enrollment patterns across U.S. colleges and universities from 2016 to 2022. Using comprehensive enrollment data and advanced statistical analysis, this study reveals significant regional variations in how institutions responded to the pandemic and identifies key factors influencing enrollment trends during this unprecedented period.

## Repository Contents

- **Codebase.ipynb**: Complete Jupyter notebook containing data preprocessing, statistical analysis, regression modeling, and visualizations.
- **cleaned_data.csv**: Final cleaned dataset with 30,488 observations across 50 states.
- **Research Paper.pdf**: Published research paper with comprehensive findings and methodology.

## Research Objectives

- Assess trends in undergraduate enrollment before, during, and after the COVID-19 pandemic
- Analyze the impact of the pandemic using regression models for pre-pandemic, pandemic, and post-pandemic periods
- Identify states and institutions most affected by enrollment changes
- Examine regional variations in enrollment patterns and institutional responses

## Key Findings

### Enrollment Trends Across Periods
- **Pre-pandemic (2016-2019)**: Average enrollment of 2,909.95 students
- **Pandemic (2020-2021)**: Average enrollment of 3,106.66 students  
- **Post-pandemic (2022)**: Average enrollment of 2,979.33 students

### State-Level Variations
**Top 5 States with Enrollment Growth:**
- Utah: +52.56%
- New Hampshire: +42.49%
- District of Columbia: +24.62%
- Arizona: +22.24%
- Colorado: +17.20%

**Top 5 States with Enrollment Decline:**
- Alaska: -21.10%
- Rhode Island: -11.73%
- Arkansas: -9.83%
- Wyoming: -6.12%
- Montana: -5.83%

### Statistical Analysis
The study employed Ordinary Least Squares (OLS) regression models to analyze enrollment patterns:

**Pre-Pandemic Model:**
```
Ei = -1.816 × 10⁵ + 89.43Yi + 2223.32Ai (R² = 0.036, p < 0.05)
```

**Pandemic Model:**
```
Ei = 1.68 × 10⁵ - 83.86Yi + 2410.16Ai (R² = 0.031, p < 0.05)
```

**Post-Pandemic Model:**
```
Ei = -0.712Yi + 2364.27Ai (R² = 0.03, p < 0.05)
```

Where:
- Ei = Undergraduate enrollment
- Yi = Year (temporal changes)
- Ai = Activity type (institutional variations)

## Methodology

### Data Description
- **Dataset**: Undergraduate enrollment data from U.S. universities (2016-2022)
- **Sample Size**: 30,488 observations across 50 states
- **Key Variables**: Academic year, institution ID, FTE enrollment, institution type, state location

### Data Preprocessing
- Removed non-U.S. institutions and irrelevant entries
- Handled missing values in state and institutional columns
- Implemented Google Maps API for state-level geocoding
- Categorized data into three distinct periods for comparative analysis

### Statistical Methods
- **Regression Analysis**: OLS models for each time period
- **Descriptive Statistics**: Mean enrollment comparisons across periods
- **Geographic Analysis**: State-level percentage change calculations
- **Visualization**: Trend analysis with confidence intervals

## How to Use

1. **Open `Codebase.ipynb`** in Jupyter Notebook or JupyterLab
2. **Install Required Libraries**: pandas, numpy, matplotlib, seaborn, statsmodels
3. **Run the Notebook**: Execute cells sequentially to reproduce the analysis
4. **Review Results**: Examine visualizations, regression outputs, and statistical summaries
5. **Reference the Research Paper**: For detailed methodology, findings, and discussion

## Key Insights

- **Regional Resilience**: States like Utah and New Hampshire demonstrated remarkable enrollment resilience during the pandemic
- **Institutional Adaptation**: Public institutions generally fared better than private institutions
- **Economic Impact**: The pandemic disrupted traditional enrollment patterns observed during previous economic recessions
- **Technology Role**: Online learning adoption varied significantly across states and institutions

## Societal Impact

This research provides valuable insights for:
- **Educators and Administrators**: Understanding enrollment patterns and institutional responses
- **Policymakers**: Developing strategies to support higher education during crises
- **Students and Families**: Understanding the broader context of enrollment changes
- **Future Research**: Identifying areas for further investigation into pandemic impacts

## Citation

If you use this work, please cite:

```
Salama, S. R. (2024). The Impact of COVID-19 Pandemic on Undergraduate Enrollment 
in the United States: A Quantitative Analysis. SSRN Electronic Journal.
```

## Author

**Saikiran Reddy Salama**  
University of North Texas  
1155 Union Cir, Denton, TX 76205, United States

---

*For questions, collaboration, or additional analysis, please contact the author.* 