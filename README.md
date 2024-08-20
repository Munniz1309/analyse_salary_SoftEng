# Software Engineer Salary Analysis

This project analyzes the salary distribution of software engineers based on various factors such as location, company, and company score. The data is sourced from a CSV file, and the analysis is done using Python with `pandas`, `numpy`, `matplotlib`, and `seaborn` libraries.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Cleaning and Processing](#data-cleaning-and-processing)
- [Visualizations](#visualizations)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [License](#license)

## Project Overview
This project aims to clean and analyze salary data for software engineers. The dataset includes information about the salaries of software engineers across different companies and locations. Through data cleaning and visualizations, the project showcases salary trends, outliers, and key insights related to the maximum and minimum salaries by location and company.

## Data Cleaning and Processing
The following steps were performed to clean and preprocess the data:
- Removed missing values.
- Cleaned the salary data by removing unwanted text like `(Glassdoor est.)` and `(Employer est.)`.
- Extracted minimum and maximum salary values from the salary column.
- Converted salary values into integers for analysis.
- Removed outliers and anomalous data, such as extremely low or high salaries.

## Visualizations
The project provides various visualizations that illustrate the salary distribution for software engineers:
- **Max Salary by Location:** Bar plot showing the maximum salary for software engineers by location.
- **Min Salary by Location:** Bar plot showing the minimum salary by location.
- **Max Salary by Company Score:** Bar plot showing the maximum salary by the score of the company.
- **Min Salary by Company Score:** Bar plot showing the minimum salary by the score of the company.
- **Max Salary by Company:** Bar plot showing the maximum salary by company.
- **Min Salary by Company:** Bar plot showing the minimum salary by company.

## Installation
To run this project locally, you will need to install the required Python packages. You can do this by following these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/Munniz1309/software-engineer-salary-analysis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd software-engineer-salary-analysis
    ```
3. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
Once the setup is complete, you can run the analysis by executing the Jupyter notebook or running the Python script. Make sure to have the dataset placed in the correct directory before running.

## Technologies

- Python: Used for data manipulation and analysis.
- Pandas: Used for data handling and cleaning.
- Numpy: Utilized for numerical computations.
- Matplotlib & Seaborn: Libraries for creating visualizations and plots.

## License
- If you use a `Software Engineer Salaries.csv` file, include the necessary libraries (e.g., `pandas`, `numpy`, `matplotlib`, `seaborn`) in it.

This `README.md` provides an overview of your project, instructions for setting it up, and a brief description of each section of the code.
