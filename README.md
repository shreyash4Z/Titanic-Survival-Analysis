# Titanic Survival Analysis

## Project Overview
This project provides an in-depth analysis of the Titanic dataset to uncover insights into the factors affecting passenger survival rates. It includes steps for data cleaning, feature extraction, and various visualizations to explore the data. The analysis is intended to identify patterns and relationships among different variables, such as passenger class, gender, and embarkation port.

## Dataset
The dataset used in this project contains information about the passengers, including:
- **Passenger ID:** Unique identifier for each passenger
- **Survived:** Survival status (0 = No, 1 = Yes)
- **Pclass:** Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name:** Passenger name
- **Sex:** Gender
- **Age:** Age of the passenger
- **SibSp:** Number of siblings or spouses aboard
- **Parch:** Number of parents or children aboard
- **Ticket:** Ticket number
- **Fare:** Passenger fare
- **Cabin:** Cabin number
- **Embarked:** Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Analysis Steps
### Data Cleaning
- **Handling Missing Values:** Addressed missing values in columns such as 'Age' and 'Embarked.'
- **Feature Engineering:** Created new features like 'Family Size' and 'Title' from existing data.

### Exploratory Data Analysis
- **Survival Rate by Class:** Analyzed how survival rates varied across different passenger classes.
- **Gender Analysis:** Examined the survival rate differences between male and female passengers.
- **Embarkation Port:** Investigated survival rates based on the port of embarkation.

### Visualizations
- **Survival Rate by Passenger Class and Gender:** Bar charts depicting survival rates across different classes and genders.
- **Age Distribution:** Histogram showing the distribution of ages among passengers.
- **Fare Distribution:** Analyzed fare distribution and its correlation with survival.

## Requirements
- **Python Libraries:** pandas, matplotlib, seaborn, numpy, scipy

## Usage
1.  **Clone the repository:**
    ```bash
       git clone https://github.com/your-username/titanic-survival-analysis.git

2.  Navigate to the project directory:
    ```bash
    cd titanic-survival-analysis
3.  Install required libraries:
    ```bash
    pip install pandas matplotlib seaborn numpy scipy
4.  Place the Titanic.csv dataset file in the project directory.
5.  Run the analysis script:
    ```bash
    jupyter notebook titanic_analysis.ipynb
## Results
- Key Insights: Summary of findings related to survival rates based on different features.
- Visualization: Plots and charts illustrating various aspects of the data.
