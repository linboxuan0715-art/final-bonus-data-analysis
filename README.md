# Global Life Expectancy and Economic Development Analysis

## Project Overview

This project analyzes the relationship between life expectancy, GDP per capita, population, continent, and time using the Gapminder dataset.

The goal of this project is to complete a basic data science workflow in a Jupyter Notebook, including data loading, data cleaning, exploratory data analysis, visualization, and interpretation of findings. The notebook is designed to be opened through a public URL and can be restarted and run from beginning to end without requiring viewers to manually download or upload any files.

## Research Questions

1. How has global life expectancy changed over time?
2. Is there a relationship between GDP per capita and life expectancy?
3. Which continents show higher or lower average life expectancy?
4. How do population and economic development differ across regions?

## Data Source

This project uses the Gapminder dataset from Plotly's public dataset repository.

The dataset includes country-level information such as:

- Country
- Year
- Population
- Continent
- Life expectancy
- GDP per capita

The dataset is loaded directly through a URL, so viewers do not need to manually download or upload any files.

Dataset URL:

https://raw.githubusercontent.com/plotly/datasets/master/gapminderDataFiveYear.csv

## Methods

The analysis follows a complete data science workflow:

1. Data loading  
2. Initial data inspection  
3. Missing value checking  
4. Feature engineering  
5. Descriptive statistics  
6. Trend analysis  
7. Continent-level comparison  
8. Correlation analysis  
9. Static data visualization  
10. Interactive data visualization  

The project uses the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn
- plotly

## Key Findings

1. Global life expectancy increased substantially from 1952 to 2007.

2. GDP per capita and life expectancy show a positive relationship, especially when GDP per capita is viewed on a logarithmic scale.

3. All continents experienced improvement in life expectancy, but regional inequality remained visible in the latest year of the dataset.

4. Population size matters when interpreting global trends because highly populated countries have greater influence on population-weighted global averages.

5. Economic development is strongly associated with health outcomes, but GDP per capita alone does not fully explain differences in life expectancy across countries and continents.

## Conclusion

This project shows that global life expectancy improved significantly over time and that countries with higher GDP per capita generally tend to have higher life expectancy.

However, the relationship between income and health outcomes is not perfectly linear. After a certain level of economic development, additional income appears to have a smaller relationship with life expectancy. Regional differences also remain important, suggesting that healthcare access, education, infrastructure, political stability, public health systems, and other social factors may also influence life expectancy.

Overall, the analysis demonstrates how data science methods can be used to explore global development patterns and communicate insights through both statistical summaries and visualizations.

## Limitations and Future Work

This analysis has several limitations.

First, the dataset only covers selected years from 1952 to 2007, so it does not reflect more recent global changes. Second, the analysis focuses mainly on correlation, so it cannot prove that GDP per capita directly causes higher life expectancy. Third, important variables such as healthcare quality, education, inequality, political stability, and public health policy are not included in the dataset.

For future work, this project could be extended by adding more recent data and additional social, economic, and institutional indicators. A more advanced statistical model could also be used to examine which factors best predict life expectancy.

## How to Run

Open the Jupyter Notebook through Google Colab and run all cells from top to bottom.

Colab Notebook:

[Open the notebook in Google Colab](https://colab.research.google.com/github/linboxuan0715-art/final-bonus-data-analysis/blob/main/final_bonus_analysis.ipynb)

GitHub Repository:

https://github.com/linboxuan0715-art/final-bonus-data-analysis