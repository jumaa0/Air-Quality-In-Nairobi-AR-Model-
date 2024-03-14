# Air Quality Analysis and Forecasting in Nairobi

## Overview
This project analyzes air quality data from Nairobi, focusing on PM-2.5 levels, using MongoDB for data storage and manipulation and Python for data analysis and forecasting. The goal is to build a time series model to predict PM-2.5 levels for 2023.

## Prerequisites
- Python 3.x installed
- MongoDB installed
- Required Python packages installed (see `requirements.txt`)

## Installation
1. Clone the GitHub repository:

`git clone https://github.com/your-username/air-quality-nairobi.git`

2. Install the required Python packages:

`pip install -r requirements.txt`


## Usage
1. Start by restoring the MongoDB backup:

`mongorestore --db mydatabase /path/to/backup/directory/mydatabase`

2. Run the Jupyter Notebook

`air_quality_analysis.ipynb`

4. Follow the instructions in the notebook to connect to the MongoDB database, import the data, and analyze it.
5. The notebook includes sections for data preparation, exploratory data analysis, model building, and evaluation.
6. The final model predicts PM-2.5 levels for the year 2023 and evaluates its performance using mean absolute error (MAE).


## Files

- `air_quality_analysis.ipynb`: Jupyter Notebook containing the project code.

- `mongodb_backup`: MongoDB backup file containing the air quality data.

## Dependencies
- pandas
- matplotlib
- seaborn
- plotly
- pytz
- statsmodels
- pymongo

## Credits
- Data source: [https://africaopendata.org/dataset/sensorsafrica-airquality-archive-nairobi]



