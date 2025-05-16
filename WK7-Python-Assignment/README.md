# PythonWeek7 Assignment

This project analyzes and visualizes survey data using Python, pandas, matplotlib, and seaborn.

## Files

- `Week7.py`: Main Python script for data loading, cleaning, analysis, and visualization.
- `PythonWeek7-Assignment.ipynb`: Jupyter notebook version (if available).
- `todays_data.csv`: Input dataset (not included in this repository).

## Features

- Loads survey data from a CSV file.
- Cleans data by removing rows with missing "Academic Level".
- Analyzes distributions of academic level, gender, and country.
- Visualizes data with:
  - Bar chart of academic level distribution
  - Pie chart of gender distribution
  - Countplot of academic level by gender
  - Bar chart of top 10 countries represented

## Requirements

- Python 3.x
- pandas
- matplotlib
- seaborn

Install dependencies with:

```sh
pip install pandas matplotlib seaborn
```

## Usage

1. Place your `todays_data.csv` file in the project directory.
2. Run the script:

```sh
python Week7.py
```

3. View the output and visualizations.

## Notes

- Update the path to `todays_data.csv` in `Week7.py` if your data file is located elsewhere.
- The script prints basic analysis results and displays several plots.
