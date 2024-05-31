# Data Preparation for ETL Process

This repository contains Jupyter Notebook files for preparing and cleaning datasets for subsequent analysis tasks using Python. The notebooks guide users through various data preparation and cleaning steps to ensure the datasets are well-prepared and suitable for further analysis.

## Notebooks

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
