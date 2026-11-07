# Titanic Survival – Exploratory Data Analysis

This project explores the Titanic passenger dataset to find out which factors were most closely linked to survival.

## Question

Who was more likely to survive the Titanic disaster, and which features are most strongly associated with survival?

## Dataset

The Titanic dataset built into the Seaborn library: 891 passengers with age, sex, ticket class, fare, port of embarkation and a survival flag.

## What I Did

- Loaded the data and inspected its structure with `shape`, `info` and `describe`
- Found and handled missing values: dropped the `deck` column (about 77% missing), filled `age` with the median and `embarked` with the mode
- Plotted survival by sex, ticket class and age
- Calculated survival rates with `groupby`
- Built a correlation heatmap to see how the numeric columns relate

## Key Findings

- About 74% of women survived, compared with about 19% of men
- About 63% of first-class passengers survived, compared with about 24% of third-class passengers
- Young children had a relatively higher chance of survival
- Sex and ticket class are the features most strongly linked to survival

## Tools Used

Python, Pandas, Matplotlib, Seaborn, Google Colab

## How to Run

1. Download the notebook (`titanic_eda.ipynb`)
2. Open it in Google Colab or Jupyter Notebook
3. Run all cells in order

## Next Steps

Build a Logistic Regression model on this data to predict passenger survival.

## Author

Akash | GitHub: add your username here
