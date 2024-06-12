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
Check file in Visualizations directory.


Insights from Car Price Data Visualization
The data visualizations provide several insights into the car market, specifically focusing on various aspects such as the number of cars by country, production years, fuel type distribution, and price ranges. Here are some key insights:

1. Car Distribution by Country
Japan has the highest number of cars, followed by South Korea and Germany.
Other notable countries include France, United States, and Czech Republic.
China and Romania have the least number of cars in the dataset.
2. Car Production Years
There is a noticeable increase in the number of car models produced starting from the mid-2000s.
The peak production years are between 2015 and 2020, with a slight decrease observed after 2020.
3. Fuel Type Distribution
Petrol cars dominate the dataset.
Diesel and hybrid cars are also significant, but much less compared to petrol.
Electric cars represent the smallest segment.
4. Car Pricing
The average price of cars listed on yad2 is approximately 84.60K.
There are 14.94K cars in the dataset from 63 unique brands.
5. Top 10 Expensive Car Brands
McLaren, Lamborghini, and Ferrari are the top three most expensive car brands by average price.
Other high-priced brands include Hummer, Aston Martin, and Bentley.
6. Top 10 Cheapest Car Brands
Lancia, Great Wall, and GMC are among the cheapest car brands by average price.
Other affordable brands include Daihatsu, Buick, and Opel.
7. Most Popular Car Brands in Israel
Hyundai is the most popular brand, followed by Toyota and Kia.
Other popular brands include Skoda, Nissan, and Mazda.
8. Most Popular Car Models in Israel
The Toyota Corolla is the most popular model, followed by Kia Sportage and Kia Picanto.
Other popular models include Nissan Qashqai, Skoda Octavia, and Mazda 3.
Visualizations Overview
The visualizations depict various facets of the car market:

- A bar chart showing the number of cars by country.
- A bar chart illustrating the number of car models by production year.
- A treemap showcasing the distribution of cars by fuel type.
- Summary statistics displaying the average price, total number of cars, and unique brands.
- Bar charts for the top 10 most expensive and cheapest car brands.
- Bar charts for the top 10 most popular car brands and models in Israel.

These visualizations provide a comprehensive overview of the car market, highlighting key trends and patterns in car production, pricing, and popularity. They can assist in making informed decisions regarding car purchases, marketing strategies, and understanding market dynamics.
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