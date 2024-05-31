# Data Preparation for ETL Process

This repository contains Jupyter Notebook files for preparing datasets for the Extract, Transform, Load (ETL) process using Python. The notebooks guide users through various data preparation steps, including file extraction, manipulation, and formatting, to ensure the datasets are well-prepared for subsequent data processing tasks.

## Notebooks

### 1_data_preparation_for_etl.ipynb

- This notebook outlines the initial steps to prepare a dataset for the ETL process.
- It covers tasks such as file extraction, data manipulation, and formatting using Python functions.

### 2_taxi_data_processing.ipynb

- This notebook demonstrates the extraction and processing of taxi data from JSON files using Python.
- It provides functions to extract taxi group information, process the data to derive meaningful insights, and create a structured DataFrame for further analysis.

### 3_data_cleaning_for_analyis.ipynb

- The third Jupyter notebook primarily focuses on data cleaning and transformation processes to prepare the dataset for further analysis, ensuring data integrity and consistency.
- It outlines a series of functions and procedures to handle various data cleaning tasks, including handling empty fields, removing duplicates, converting data types, addressing outliers, and ensuring consistent column order.
- Additionally, the notebook meets the requirement of saving the final cleaned dataset as CSV but maintains pickle files between stages.

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
