# Performing-EDA-on-Global-Terrorism-Dataset

This repository contains code and data for analyzing the Global Terrorism Database. The Global Terrorism Database is an extensive dataset that records information about terrorist incidents worldwide.

## Dataset

The dataset used for this analysis is available in the following URL: [Dataset CSV](https://tinyurl.com/43edcbf5).
It contains 1,81,691 rows and 135 columns.

## Data Preprocessing

- The dataset is loaded into a Pandas DataFrame.

- Columns with specific data types are defined using `dtype_dict`.

- Columns 'Casualties' and 'Attack' are created to calculate the total casualties per incident and combine multiple attack types.

## Analysis

1. **Country with the Most Attacks**:
   - The country that faced the most attacks is identified using Pandas.

2. **Country with the Most Severe Loss**:
   - The country with the most severe loss is determined by summing casualties per country.

3. **Number of Attacks per Country**:
   - A bar chart is generated to visualize the number of attacks per country.

4. **Total Casualties per Country**:
   - Another bar chart is created to visualize the total casualties per country.

## Dependencies

- Python 3
- Pandas
- Matplotlib
- Seaborn
