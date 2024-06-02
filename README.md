# Data Preparation for ETL Process

This repository contains Jupyter Notebook files for preparing and cleaning datasets for subsequent analysis tasks using Python. The notebooks guide users through various data preparation and cleaning steps to ensure the datasets are well-prepared and suitable for further analysis.

## Notebooks

### a_prelim_workings_VERY_ROUGH_WORKINGS.ipynb

- This notebook documents the initial exploration and experimentation steps taken during the project, providing insight into the preliminary data processing efforts.
- It is messy and unrefined, reflecting the early stages of the process before the more structured and refined notebooks were developed.

### 1_data_preparation_for_etl.ipynb

- Outlines initial steps to prepare datasets for the ETL process.
- Covers tasks such as file extraction, data manipulation, and formatting using Python functions.

### 2_taxi_data_processing.ipynb

- Demonstrates extraction and processing of taxi data from JSON files using Python.
- Provides functions to extract taxi group information, derive insights, and create a structured DataFrame for analysis.

### 3_data_cleaning_for_analyis.ipynb

- Focuses on data cleaning and transformation processes to prepare the dataset for analysis, ensuring data integrity and consistency.
- Outlines procedures to handle tasks such as empty fields, duplicates removal, data type conversion, outlier detection, and consistent column ordering.
- Meets the requirement of saving the final cleaned dataset as CSV while maintaining intermediate pickle files between stages.

### 4_exploratory_data_analysis_with_dtale.ipynb

- This notebook utilizes the Dtale library for interactive exploratory data analysis (EDA) on a Pandas DataFrame.
- It installs necessary libraries, loads the dataset, configures Dtale for use in the Colab environment, and provides auxiliary functions for managing Dtale instances.

### 6_report_anomalies_and_outliers.ipynb

- This notebook presents a comprehensive report of anomalies and outliers in driver performance metrics within a taxi service dataset.
- By highlighting percentile values and implementing a "sanity check" mechanism, the notebook enables stakeholders to identify and investigate potential issues or exceptional cases within the dataset, contributing to data-driven decision-making processes.

## Usage

1. Clone the repository to your local machine:
   
   ```
   gh repo clone CloudStream-Innovations/notebooks
   ```

2. Navigate to the repository directory:
   ```
   cd notebooks
   ```

3. Open the Jupyter Notebook files using Jupyter Notebook or JupyterLab:
   ```
   jupyter notebook
   ```
   or
   ```
   jupyter lab
   ```

4. Follow the instructions in the notebooks to prepare your datasets for the ETL process.

## Requirements

- Python 3.x
- Jupyter Notebook
- Required Python libraries (specified in the notebooks)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thank you to the contributors and maintainers of the Python libraries used in this project.
- Appreciation for Google Colab for offering a valuable development environment.
- Acknowledgment of Github for providing a platform for version control and collaboration.
