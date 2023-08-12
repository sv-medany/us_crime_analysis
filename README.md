
# United States - Crime Rates Analysis (1960 - 2014)

This project involves the analysis of crime rates data in the United States from 1960 to 2014 using Python and the Pandas library.

## Project Overview

This analysis aims to explore and analyze crime rates data in the United States from 1960 to 2014. The dataset is obtained from a specified source and is utilized to perform various operations and calculations. The primary objectives of this project are:

- Import the necessary libraries for data analysis.
- Import the crime rates dataset from a provided URL.
- Examine the data types of the columns in the dataset.
- Convert the 'Year' column to the datetime64 type for time series analysis.
- Set the 'Year' column as the index of the dataframe.
- Delete the 'Total' column from the dataframe.
- Group the years by decades and calculate the sum of crime-related columns for each decade.
- Determine the total crime rates for each decade and find the most dangerous decade to live in the US.

## Analysis Steps

1. Import the required libraries, including Pandas and NumPy.
2. Import the crime rates dataset from a given URL.
3. Examine the data types of the columns in the dataset.
4. Convert the 'Year' column to the datetime64 type for time series analysis.
5. Set the 'Year' column as the index of the dataframe.
6. Delete the 'Total' column from the dataframe.
7. Group the years by decades and calculate the sum of crime-related columns.
8. Avoid summing the 'Population' column, as it would lead to erroneous results.
9. Calculate the total crime rate for each decade.
10. Determine the most dangerous decade based on the highest total crime rate.

## Repository Structure

```
US-Crime-Rates-Analysis/
│
├── crime_analysis.ipynb  # Jupyter Notebook containing analysis code
└── readme.md             # Project overview and details
```

## Usage

1. Clone the repository using: `git clone https://github.com/your-username/US-Crime-Rates-Analysis.git`
2. Navigate to the repository: `cd US-Crime-Rates-Analysis`
3. Open the `crime_analysis.ipynb` notebook to access the detailed analysis steps and results.

## Acknowledgments

- Special thanks to the source that provided the crime rates dataset for this analysis.
- Appreciation to the creators and contributors of the Pandas and NumPy libraries for empowering data analysis.

---
