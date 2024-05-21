# Customer Data Pre-processing and Visualization

## 1.0 Executive Summary
This project preprocesses and transforms customer data from a flat CSV format into structured JSON formats suitable for analysis. The tasks include data cleaning, error correction, and conversion to nested JSON structures using Python. The cleaned data is exported to `processed.json`, `retired.json`, and `employed.json` files. Metrics like "Salary-Commute" are calculated, and visualizations are created using Pandas and Seaborn to provide insights into customer demographics and behaviors.

## 2.0 Problem Statement
The initial flat structure and errors in the provided CSV customer data made it unsuitable for analysis. The goal was to transform this data into a structured and clean format to enable better data-driven decision-making and enhance customer management strategies.

## 3.0 Project Plan

| Phase                    | Timeline  | Milestones                                                              |
|--------------------------|-----------|-------------------------------------------------------------------------|
| Data Assessment          | Week 1-2  | Initial data reading and cleaning                                       |
| Data Transformation      | Week 3-4  | Converting flat data structures into nested structures                  |
| Error Correction         | Week 5    | Identifying and correcting errors (e.g., dependents column)             |
| Data Export              | Week 6    | Exporting cleaned data to JSON formats (`processed.json`, `retired.json`, `employed.json`) |
| Visualization & Analysis | Week 7    | Generating univariate and multivariate plots, calculating additional metrics like "Salary-Commute" |
| Final Review             | Week 8    | Final review and documentation                                          |

## 4.0 Solution Description

### Data Processing Tasks

- **Reading the CSV file**: Use Python's CSV library for initial data reading and cleaning.
- **Transforming flat data structures**: Convert data into nested JSON structures to represent entities like vehicles, credit cards, and addresses.
- **Handling errors in the dependents column**: Identify and correct errors to ensure data accuracy.
- **Exporting processed data**: Export cleaned data to `processed.json`, `retired.json`, and `employed.json` files.
- **Identifying and flagging problematic credit card entries**: Create a `remove_ccard.json` file for flagged entries.
- **Calculating the "Salary-Commute" metric**: Evaluate customer salary efficiency based on commute distance.

### Data Visualization Tasks

- **Calculating mean salary and median age**: Use Pandas to derive key metrics.
- **Creating univariate plots**: Generate plots for age distribution, dependents, and age by marital status using Seaborn.
- **Creating multivariate plots**: Visualize commute distance vs. salary, age vs. salary, and age vs. salary by dependents.
- **Providing functionality to save plots**: Enable saving of plots in preferred formats (e.g., PNG, JPEG).

## 5.0 Results

- **Processed Data**: Successfully created and validated multiple JSON outputs, enabling easier data handling and querying.
- **Error Handling**: Corrected errors and flagged problematic entries, ensuring data accuracy.
- **Visual Insights**: Generated meaningful visualizations to provide valuable insights into customer demographics and behaviors.

## 6.0 Conclusion
This project transformed a complex customer dataset into structured and clean JSON outputs suitable for in-depth analysis. The effective handling of data quality issues and the creation of meaningful visualizations highlight the ability to manage and analyze complex data efficiently, supporting informed business decisions and enhanced customer management strategies.
