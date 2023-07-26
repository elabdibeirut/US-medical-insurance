# Medical Insurance Data Analysis


## Overview

This project is an analysis of a medical insurance dataset to gain insights into various attributes' impact on medical charges. The dataset consists of information about individuals, including their age, sex, BMI, smoking status, region, and medical charges.

## Dataset

The dataset used in this analysis is stored in the `insurance.csv` file. It contains the following attributes:

- `age`: Age of the individual (numeric)
- `sex`: Gender of the individual (categorical: 'male' or 'female')
- `bmi`: Body Mass Index (numeric)
- `children`: Number of children covered by the insurance (numeric)
- `smoker`: Smoking status of the individual (categorical: 'yes' or 'no')
- `region`: Region of residence (categorical: 'southwest', 'southeast', 'northwest', 'northeast')
- `charges`: Medical charges billed to the individual (numeric)

## Project Structure

The project is organized into the following files:

- `insurance.csv`: The raw dataset in CSV format.
- `medical_insurance.ipynb`: Jupyter Notebook containing the data analysis and visualization code.
- `README.md`: This README file providing an overview of the project.

## Requirements

The following libraries are required to run the Python script or Jupyter Notebook:

- pandas
- numpy
- matplotlib
- seaborn
- plotly
- prettytable

You can install the required libraries using `pip` with the following command:

```
pip install pandas numpy matplotlib seaborn plotly prettytable
```

## How to Use

1. Clone this repository to your local machine or download the files as a ZIP archive.
2. Ensure you have the required libraries installed (see Requirements section).
3. Open the Jupyter Notebook `medical_insurance.ipynb` in Jupyter Notebook or JupyterLab to run the code step-by-step.
4. The analysis results and visualizations will be displayed or saved as images, depending on the code.

## Results

The analysis provides insights into the impact of different attributes on medical charges. It reveals significant correlations between smoking status, weight status, age, and medical charges. The findings can be used to inform health insurance risk assessments, policy pricing, and personalized insurance plans for individuals based on their health profiles.


