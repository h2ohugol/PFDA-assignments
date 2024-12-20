# PFDA-assignments

This will be a mix of small PFDA (programming-for-data-analytics) practical assignments.
Lecture by Andrew Beatty at [ATU](https://www.atu.ie/).

![weatherisk](img/weather_risk20241214.jpg)

# Assignments Overview
***

This repository contains a series of assignments designed to practice data analysis, visualization, and simulation techniques using Python. Below are the details of each assignment, along with instructions on what is required.

## Assignment 2: Weather Plot
***

### Objective
Create a Jupyter Notebook (`assignment2-weather.ipynb`) that plots the temperature over time using the `dryBulbTemperature_Celsius` column from a provided dataset.

### Instructions
- Use **Pandas** to read in the data.
- Generate a plot that visualizes the temperature (`dryBulbTemperature_Celsius`) over time.
- Ensure the plot is clear and well-labelled.

## Assignment 3: Email Domains Pie Chart
***
### Objective
Create a Jupyter Notebook (`assignment03-pie.ipynb`) that displays a pie chart of people's email domains based on the provided CSV file.

### Dataset
- The dataset is available at this URL:
  [Download CSV](https://drive.google.com/uc?id=1AWPf-pJodJKeHsARQK_RHiNsE8fjPCVK&export=download)
- The file contains 1000 entries.

### Instructions
- You can either download the data or link to it directly.
- Use the CSV data to extract email domains.
- Plot a pie chart showing the distribution of email domains.
- Ensure the code is clean, concise, and well-commented.

## Assignment 5: Risk Simulation
***

### Objective
Write a program (`assignment_5_risk.py` or `assignment_5_risk.ipynb`) that simulates **1000 individual battle rounds** in the game Risk and visualizes the results.

### Instructions
- Simulate one battle round as a single shake of the dice for 3 attackers and 2 defenders.
- Record the results for all 1000 rounds.
- Create a plot that visualizes the outcomes (e.g., attacker losses, defender losses, win rates, etc.).
- Use your creativity for the visualization; there are no strict guidelines.

## Assignment 6: Weather Data Analysis
***

### Objective
Create a Python program or notebook (`assignment_6_Weather.py` or `assignment_6_Weather.ipynb`) that analyses weather data from a provided CSV file.

### Dataset
- The dataset is available at this URL:
  [Weather Data CSV](https://cli.fusio.net/cli/climate_data/webdata/hly4935.csv)

### Instructions

#### Temperature Analysis
- Plot the temperature over time.
- Calculate and plot the **mean temperature** for each day.
- Calculate and plot the **mean temperature** for each month.

#### Windspeed Analysis
- Plot the windspeed (handle missing data appropriately).
- Calculate and plot the **rolling average windspeed** over 24 hours.
- Calculate and plot the **maximum windspeed** for each day.
- Calculate and plot the **monthly mean of daily maximum windspeeds**.

### General Requirements
***

- All code should be **well-documented** with concise comments explaining each step.
- Include clear and labelled visualizations where applicable.
- Ensure reproducibility and clean architecture in all scripts and notebooks.

### Technologies
***

- [Python](https://www.python.org/): Core language for all assignments.
- [Pandas](https://pandas.pydata.org/docs/): For data manipulation and analysis.
- [Matplotlib](https://matplotlib.org/): For creating visualizations.
- [NumPy](https://numpy.org/): For numerical computations.
- [Jupyter Notebooks](https://jupyter.org/): For interactive code and documentation.
