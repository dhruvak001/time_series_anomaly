
# Time Series Anomaly Detection

## Overview
This project aims to perform time series anomaly detection using multivariate time series data and labeled anomaly regions. It involves reading test and label files, drawing time series plots with anomaly regions, performing exploratory data analysis (EDA), and identifying the variables that are the root cause of anomalies....

## Project Structure
- `files/`: Contains the dataset files.
- `AI4SEE.py`: Python script for performing anomaly detection and analysis.
- `README.md`: Documentation file providing an overview of the project.

## Dependencies
- python3
- pandas
- matplotlib
- seaborn

## Usage
1. Clone the repository:

2. Navigate to the project directory:

3. Ensure the dataset files are placed in the `files/` directory.

4. Run the `AI4SEE.py` script:

5. The script will perform the following tasks:
    - Read the test and label files.
    - Draw time series plots with anomaly regions.
    - Perform exploratory data analysis (EDA).
    - Find out the variables which are the root cause for the anomaly.

## Additional notes
- Adjust the `chunk_size` and `sample_size` variables in the script according to your system's memory constraints and the size of the dataset.
- Ensure that the dataset files are in CSV format and contain the required columns.


---

### Description 
This repository contains code for performing time series anomaly detection using Python. It includes a Python script (`AI4SEE.py`) that reads multivariate time series data and labeled anomaly regions, performs analysis, and identifies the variables responsible for anomalies. The script utilizes pandas, matplotlib, and seaborn libraries for data manipulation, visualization, and exploratory data analysis. The project aims to provide insights into anomaly detection techniques and serve as a learning resource for time series analysis.


