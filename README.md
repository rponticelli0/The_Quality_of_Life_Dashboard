# Cost of Living Analysis Project

## **PLEASE RUN EACH NOTEBOOKS IN SEQUENTIAL ORDER***

This repository contains a set of Jupyter notebooks aimed at analyzing the cost of living factors to determine their impact on overall expenses. Through data cleaning, preprocessing, feature engineering, and machine learning techniques, the project explores relationships between various economic indicators and the total cost of living.

## Table of Contents

1. **Data Cleaning and Preparation**
   - [`1_col_data_cleaning.ipynb`](./1_col_data_cleaning.ipynb): Prepares and cleans the cost of living data for further analysis.
   - [`2_salary_data_cleaning.ipynb`](./2_salary_data_cleaning.ipynb): Cleans and processes salary data relevant to the study.

2. **Data Integration**
   - [`3_join_files.ipynb`](./3_join_files.ipynb): Joins multiple datasets for a unified view of key metrics.

3. **Handling Missing Data**
   - [`4_fix_missing_data.ipynb`](./4_fix_missing_data.ipynb): Identifies and addresses missing values in the datasets.

4. **Feature Engineering**
   - [`5_pop_pct_diff_county.ipynb`](./5_pop_pct_diff_county.ipynb): Calculates population percentage differences for counties.
   - [`6_create_pct_diff_binary.ipynb`](./6_create_pct_diff_binary.ipynb): Creates binary variables to capture critical patterns in the data.

5. **Modeling**
   - [`7_linear_regression.ipynb`](./7_linear_regression.ipynb): Develops and evaluates linear regression models to understand the influence of individual factors on the total cost of living.
   - [`8_binary_classification.ipynb`](./8_binary_classification.ipynb): Implements binary classification models to predict outcomes based on cost of living data.


## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/rponticelli0/The_Quality_of_Life_Dashboard.git
    ```
## Usage

Each notebook contains step-by-step instructions and code to:
- Clean and preprocess the data
- Integrate multiple datasets
- Perform feature engineering
- Build and evaluate machine learning models

To run the notebooks, open them with Jupyter or any compatible environment:
```bash
jupyter notebook <notebook_name>.ipynb
```

## Project Objective

The goal of this project is to explore which features most significantly impact the total cost of living and how salary data interacts with those features. The insights generated can support individuals, organizations, and policymakers in making data-driven decisions regarding housing, salaries, and other economic factors.


## Contributing
Contributions are welcome! If you have suggestions or improvements, please open an issue or submit a pull request.


## License
This project is licensed under the MIT License – see the LICENSE file for details.


## Contact
For questions or collaborations, please reach out to Ryan Ponticelli.
