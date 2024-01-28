# nih
NIH Generally Keeps Investing in More Edge Science: Examining Research Projects from 2000-2022

Project Overview
This project involves processing NIH (National Institutes of Health) data, including tasks such as data cleaning, filtering, and column mapping. The code is written in Python and utilizes the pandas library for data manipulation.

Folder Structure

The project is organized into several folders:
nih: Contains the main Python scripts for data processing.
nih_cleaned_dfs: Stores the cleaned and processed CSV files during the cleaning process
nih_calculations: Manipulated numbers in some way
nih_concatenated: Concatenated dfs
r_code_category: Data surrounding r_code

Getting Started
Prerequisites
Before running the code, ensure you have the following dependencies installed:
Python 3
pandas library
Install the required Python libraries using:
bash
pip install -r requirements.txt

Installation
Clone the repository:
bash
git clone https://github.com/sf-portfolio/nih-data-processing.git
cd nih-data-processing

Run the data processing script:
bash
python nih_data_processing/main_script.py

Usage
Modify the folder_path variable in the main_script.py file to point to the directory containing your NIH data CSV files.
Execute the script to perform data processing.
Data
The input data is in CSV format and located in the specified folder. 
Code Explanation
1. Data Cleaning and Mapping
main_script.py: Performs data cleaning, sets column names to lowercase, and maps columns.
cleaning_functions.py: Contains functions for data cleaning and column mapping.
2. Column Renaming
column_mapping.py: Defines a function for mapping and renaming columns in the processed data.
3. Filtering Data
data_filtering.py: Filters data based on specified conditions, such as date and activity type.
4. Date Correction
date_correction.py: Corrects out-of-bound dates and updates 'award_notice_date' based on 'budget_start'.

Relative Path
Example: "Documents/nih_cleaned_dfs"

Results
The processed data is saved in the nih_cleaned_dfs, nh_calculations, nih_conccatenated, or r_code_category  folder. Check the individual scripts for detailed information on each processing step.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
The pandas library for efficient data manipulation in Python.
Contributors and authors of external code snippets used in this project.

