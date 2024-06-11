# Car Price Prediction Project

## Project Overview

This project involves scraping car price data from the Yad2 website, preprocessing and cleaning the data, and building predictive models to forecast car prices. Additionally, the project includes data visualizations to derive insights from the data.

## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Data Scraping](#data-scraping)
- [Data Preprocessing and Cleaning](#data-preprocessing-and-cleaning)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Data Visualization](#data-visualization)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)

## Installation

To get started with this project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/TiurinMikhail/Israels-Car-market-price-predictor
cd Car-Price-Prediction-Project
```

## Data Scraping
The data scraping process involves extracting car price data from the Yad2 website. The script yad2_scrap.ipynb in the Data-collection directory handles this task.
- Input: None
- Output: yad2_cars.csv

## Data Preprocessing and Cleaning
After scraping the data, preprocessing and cleaning are necessary steps to prepare the data for modeling. The script data_cleaning_preproc.ipynb in the Data-cleaning directory handles this task.

- Input: yad2_cars.csv
- Output: yad2_cars_cleaned.csv

## Modeling
The modeling process involves training different regression models to predict car prices. The script model_train.ipynb in the Model-training directory handles this task.

- Input: yad2_cars_cleaned.csv
- Output: Trained models and evaluation metrics

## Evaluation
The models are evaluated using metrics such as R2 Score, Mean Squared Error (MSE), and Root Mean Squared Error (RMSE). These metrics help in understanding the performance of the models.

## Data Visualization
Check file in Visualizations directory

## Technologies Used
- Python: Core programming language
- BeautifulSoup & Selenium: For web scraping
- Pandas: For data manipulation
- Scikit-learn: For modeling and evaluation
- Statsmodels: For statistical modeling and p-value calculations
- XGBoost: For advanced modeling
- Matplotlib & Seaborn: For data visualization
- Tableau & PowerBI: For advanced data visualization and insights
- ChatGPT & Gemini: For code generation and project assistance
## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or additions.