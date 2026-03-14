# World Happiness Index - EDA Dashboard

An exploratory data analysis (EDA) project on the 2019 World Happiness Report using Python, pandas, matplotlib and seaborn.

## Project Overview
This is my second Python project, built as part of my journey towards becoming an AI/ML Engineer.
The goal is to explore what factors make countries happy using data visualization and correlation analysis.

## Dataset
- Source: [Kaggle World Happiness Report](https://www.kaggle.com/datasets/unsdsn/world-happiness)
- 156 countries
- Year: 2019
- Features: GDP per capita, Social support, Healthy life expectancy, Freedom, Generosity, Perceptions of corruption

## Questions Explored
1. Which are the Top 10 happiest countries?
2. Does GDP per capita affect happiness score?
3. Does freedom affect happiness?
4. Which factor correlates most with happiness?
5. Do healthier countries tend to be happier?

## Key Findings
- Nordic countries (Finland, Denmark, Norway) dominate the top 10 happiest countries
- GDP per capita has the strongest correlation with happiness (0.79)
- Social support and healthy life expectancy are equally important (0.78)
- Generosity has almost no correlation with happiness (0.08)
- Richer countries tend to have better health outcomes (0.84 correlation)

## Libraries Used
- pandas
- matplotlib
- seaborn

## How to Run
1. Clone this repo
2. Install dependencies: `pip install pandas matplotlib seaborn`
3. Open `happiness.ipynb` in VSCode or Jupyter
4. Run all cells in order

## What I Learned
- How to perform EDA on a real world dataset
- How to create and interpret correlation heatmaps
- How to find patterns and tell a story with data
- Visualization best practices with matplotlib and seaborn
