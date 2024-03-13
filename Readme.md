
# Netflix Data Analysis

This Python code performs analysis on Netflix titles data from a CSV file.

## Overview
The code does the following:

- Imports necessary libraries: pandas, numpy, matplotlib, seaborn
- Reads in Netflix titles data from a CSV file 
- Handles any duplicate rows 
- fill the Missing data
- Structure problems
- Handle Mismatch number of records
- Calculates proportion of titles that are Netflix originals
- Gets counts of titles by type (Movie, TV Show, etc)
- Finds most common genres
- Visualizes distribution of content ratings
- Prints out key statistics like number of titles, % that are originals
- Generates visualizations:
    - Bar chart of titles by type
    - Bar chart of top genres
    - Histogram of ratings 
    - Bar chart of titles by type

## Requirements
The code requires the following Python libraries:

- pandas
- numpy 
- matplotlib
- seaborn

It also requires the `netflix_titles.csv` dataset in the same directory.

## Usage
To run the analysis:

```
python netflix_analysis.py
```

It will print statistics and display visualization plots.

## Output
Key outputs include:

- Printed statistics about the Netflix catalog
- Matplotlib plots:
    - Counts of titles by type
    - Most common genres
    - Distribution of ratings
    - Counts of titles by type
