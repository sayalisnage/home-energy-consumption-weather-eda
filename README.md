# Exploratory Data Analysis on Home Energy Consumption and Weather Data

A data science project aimed at posing a statistical question and using a dataset to prove or disprove a hypothesis. This project investigates home energy consumption patterns in relation to weather data, demonstrating a comprehensive workflow of data cleaning, exploratory data analysis, hypothesis testing, and regression modeling to draw meaningful conclusions about energy usage and efficiency.

---

## Project Overview
Home energy consumption and efficiency analysis has gained immense popularity with the main objective of reducing C02 emissions, energy costs, and improving overall home efficiency. This project focuses on analyzing the consumption patterns of electrical loads in a household and how they are influenced by weather. By performing a thorough exploratory data analysis and a series of statistical tests, this project seeks to answer a central hypothesis and contribute to a better understanding of how to manage energy consumption based on weather patterns.

---

## Data Sources
Kaggle Dataset: A time-series dataset containing detailed home energy consumption and generation data, along with local weather conditions.

Features: Total energy consumption, energy generation (solar), individual appliance consumption, temperature, humidity, wind speed, and cloud cover.

Source: Kaggle

---

## Methodology
This project follows a structured methodology to explore the dataset and test the hypothesis.

### Data Cleaning and Preparation:
- The dataset was loaded and initial exploration was performed using Python libraries.
- Invalid values were handled and duplicates were removed.
- Fields such as Furnace 1 and Furnace 2 were combined for a consolidated view.
- The time field was formatted into a datetime object, and new features like year, month, and weekday were created to facilitate time-series analysis.

### Exploratory Data Analysis (EDA):
- Single Variable Analysis: Histograms, PMFs (Probability Mass Functions), and CDFs (Cumulative Distribution Functions) were created to understand the distributions of key variables, such as energy consumption. This included comparing different scenarios within a single variable (e.g., consumption on weekdays vs. weekends).
- Multi-Variable Analysis: Scatter plots were used to visualize the relationships between two variables, analyzing correlation and causation while considering covariance, Pearson's correlation, and non-linear relationships.

### Statistical Modeling and Hypothesis Testing:
- Hypothesis Testing: A formal test was conducted on the project's central hypothesis using a statistical method covered in the course.
- Regression Analysis: A regression model was developed to analyze the impact of one or more explanatory variables (like temperature or humidity) on a dependent variable (such as total energy consumption).
  
---

## Key Findings
- Seasonal Patterns: The analysis found a slight difference in energy generation between winter and summer, with slightly more generation in winter due to clearer skies.
- Correlation: A strong correlation was found between energy consumption and various weather conditions.
- Appliance Usage: The analysis highlights how specific appliance-level consumption, particularly for systems like the furnace, significantly impacts overall energy usage and demand.
- Hypothesis Validation: The project was able to use statistical methods to either prove or disprove the initial hypothesis regarding home energy consumption patterns.

---

## Limitations and Assumptions
- The dataset is limited to a single household, which may affect the generalizability of the findings to a broader population.
- The data for solar generation lacks details on the specific type of solar source (e.g., solar panels vs. outdoor lighting), making some conclusions limited to assumptions.
- The analysis is focused on a specific time period and does not account for changes in appliance efficiency, household behavior, or unforeseen events.

---

## Ethical Considerations
This project acknowledges the importance of privacy in household data collection and analysis. The data used is from a publicly available source, and the analysis is focused on a technical understanding of energy patterns rather than individual behavior.

---

## Technology Stack
Programming Language: Python

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Tools: Jupyter Notebook

---

## Contact
For questions or collaboration, please reach out via [E-mail](mailto:sayalinage@gmail.com) or connect on [LinkedIn](https://www.linkedin.com/in/sayali-nage-34303b136/)
