# Climate Trend Analysis & Modeling

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data_Manipulation-150458.svg)
![SciPy](https://img.shields.io/badge/SciPy-Statistical_Modeling-8CAAE6.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626.svg)

## Project Overview
This project performs an in-depth Exploratory Data Analysis and statistical modeling on over 130 years of historical weather data. The primary objective is to investigate long-term climate trends, specifically analyzing average high temperatures, using descriptive statistics and Simple Linear Regression. 

By utilizing Python's data science stack, this project transforms raw sequential climate data into actionable visual insights, demonstrating how statistical models can establish historical trends and predict future temperature anomalies.

## Key Features
* **Data Preprocessing:** Cleaning raw data, standardizing column names, and performing type conversions (e.g., date parsing) for accurate time-series analysis.
* **Exploratory Data Analysis (EDA):** Generating descriptive statistics (mean, variance, standard deviation) to understand the distribution of temperature records over a century.
* **Statistical Modeling:** Implementing the method of least squares using `scipy.stats` to calculate slopes, intercepts, and build a Simple Linear Regression model.
* **Data Visualization:** Creating intuitive and compelling visualizations with Matplotlib and Seaborn, including regression lines and confidence intervals, to illustrate long-term climate trends.

## Technologies Used
* **Language:** Python
* **Data Manipulation:** Pandas
* **Statistical Modeling:** SciPy (`scipy.stats.linregress`)
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook / Google Colab

## Dataset
The dataset consists of historical weather records spanning 130+ years, containing chronological data points such as dates and average high temperatures in New York (Central Park) for January during 1895-2026. Sourced from [NOAA](https://www.ncdc.noaa.gov/cag/). 

## Installation and Setup

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/arcctg/climate-trend-analysis.git
   cd climate-trend-analysis
   ```

2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install the required dependencies:**
   ```bash
   pip install pandas scipy matplotlib seaborn jupyter
   ```

4. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
   *Open the `.ipynb` file in your browser to run the analysis cells.*

## Results and Insights
* The linear regression model successfully established a trend line across the 130-year dataset.
* Visualizations indicate a gradual but consistent increase in average high temperatures over the last century.
* The model's slope and intercept provide a mathematical baseline for predicting future temperature expectations based on historical trajectories.

## License
This project is open-source and available under the [MIT License](LICENSE).
