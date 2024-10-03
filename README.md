This repository contains a Jupyter Notebook that performs an exploratory analysis of a bank's marketing campaign data. The goal is to understand the factors that influence the conversion rate of customers subscribing to a term deposit.

**Source:** [Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing) from the UCI Machine Learning Repository.

## Dataset

The dataset contains information about bank clients, including their demographics, financial status, and interaction with previous marketing campaigns. The target variable is `y`, indicating whether the client subscribed to a term deposit ('yes' or 'no').

**Key Features:**

* **Demographics:** age, job, marital status, education
* **Financial:** credit default status, housing loan, personal loan
* **Campaign:** contact type, last contact month/day/duration, number of contacts
* **Previous Campaign:** days since last contact, number of contacts, outcome
* **Socioeconomic:** employment variation rate, consumer price index, consumer confidence index, Euribor 3 month rate, number of employees

## Analysis

The notebook performs the following analysis:

* **Data Cleaning:** Checks for missing values and data types.
* **Descriptive Statistics:** Calculates basic statistics for numerical features.
* **Correlation Analysis:** Visualizes the correlation between numerical features.
* **Conversion Rate Calculation:** Calculates the overall conversion rate and conversion rates by different features like age, education, job, and marital status.
* **Visualization:** Creates various plots (bar charts, pie charts, line graphs) to visualize the conversion rates and identify trends.

## Key Findings

* **Age:** Younger age groups have higher conversion rates.
* **Education:** Clients with higher education levels tend to convert more.
* **Job:** Students and retired individuals have the highest conversion rates.
* **Marital Status:** Single individuals are more likely to convert.

## Usage

1. Clone the repository: `git clone https://github.com/your-username/bank-marketing-analysis.git`
2. Install the required libraries: `pip install pandas matplotlib`
3. Open and run the Jupyter Notebook: `jupyter notebook bank-marketing-analysis.ipynb`

## Contributing

Feel free to fork the repository and contribute by:

* Adding new visualizations or analyses
* Improving the existing code
* Providing suggestions for further exploration
