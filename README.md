### NYC January Temperature Analysis
## Overview
This project uses historical data on the average high temperatures in New York City during January, spanning from 1895 to 2018. The goal is to apply simple linear regression to predict future temperatures and estimate historical temperatures. This project also provides visualizations to demonstrate the trends over time.

## Table of Contents
1. Project Structure
2. Installation and Setup
3. How to Run
4. Data Description
5. Analysis
6. Visualizations
7. Insights

## 1. Project Structure
* data/: Contains the NYC January temperature dataset (ave_hi_nyc_jan_1895-2018.csv).
* notebooks/: Jupyter notebooks used for developing the project.
* src/: Python scripts with the code for linear regression analysis and data visualizations.
* equirements.txt: Lists all the dependencies required to run the project.
* README.md: Instructions and project details (this file).
* .venv/: Virtual environment (optional, see setup instructions).


## 2. Installation and Setup
* Step 1: Clone the Repository  
First, clone the project repository from GitHub:
```git clone https://github.com/NickElias01/datafun-07-ml```
* Step 2: Set Up the Virtual Environment  
    * Navigate to the project directory and create a virtual environment:
    ``` python -m venv .venv```
    * Activate the virtual environment:

        * On Windows: .\.venv\Scripts\activate
        * On macOS/Linux: source .venv/bin/activate

* Step 3: Install the Required Dependencies  
Once the virtual environment is activated, install the required libraries using requirements.txt:

    * ```pip install -r requirements.txt```  
This will install numpy, pandas, matplotlib, seaborn, scipy, sklearn, and other dependencies.

## 3. How to Run
* Ensure that the virtual environment is activated.
* Run the Jupyter Notebook or Python scripts provided in the notebooks or src folder.
* For Jupyter, start the notebook using the command:
```jupyter notebook```
* Navigate to the notebook in your browser and run the cells sequentially to execute the analysis.

## 4. Data Description
The dataset used in this project contains:

* Date: The year of the temperature reading (in YYYYMM format, later cleaned to show only the year).
* Temperature: The average high temperature in January for NYC in Fahrenheit.
* Anomaly: The temperature difference from the baseline (not used in this project).

## 5. Analysis
The project consists of:

* Cleaning the dataset by truncating the date and renaming columns for clarity.
* Applying simple linear regression to model the relationship between year (independent variable) and temperature (dependent variable).
* Using the model to predict temperatures for future years (e.g., 2024) and estimate past temperatures (e.g., 1890).

## 6. Visualizations
The project includes visualizations such as:

* Line plot of temperature trends over time.
* Scatter plot with a regression line to show the linear relationship between year and temperature.

## 7. Insights
The analysis indicates a steady rise in January temperatures over time. The model suggests that average temperatures in January 2024 will continue this upward trend. More detailed insights are available in the final markdown section of the notebook.