# Airbnb EDA and Data Visualization Project - New York 2024

## Project Description
This project performs a comprehensive Exploratory Data Analysis (EDA) on New York City Airbnb listing data for the year 2024. The analysis aims to uncover pricing trends, geographical distribution of rentals, and the relationship between different property metrics. By cleaning and visualizing the data, this project provides insights into the short-term rental market across the five boroughs of NYC.

## Objectives
1. Perform data cleaning and handle encoding issues.
2. Conduct initial statistical exploration of the dataset.
3. Analyze the distribution of listings across different neighborhood groups.
4. Identify correlations between numerical variables such as price, availability, and reviews.
5. Visualize findings using professional plotting libraries.

## Dataset Features
The analysis covers several key attributes of the Airbnb listings, including:
* Listing names and host information.
* Neighborhood groups (Manhattan, Brooklyn, Queens, Bronx, Staten Island).
* Room types (Entire home/apt, Private room, Shared room, Hotel room).
* Pricing, minimum nights, and total number of reviews.
* Availability throughout the year.

## Analysis Workflow
* **Dependencies**: Utilization of Python libraries including NumPy, Pandas, Matplotlib, and Seaborn.
* **Data Ingestion**: Loading data with robust encoding error handling.
* **Data Cleaning**: Dropping unnecessary columns, handling missing values, and removing duplicates.
* **Numerical Analysis**: Generating correlation matrices and heatmaps to understand price drivers.
* **Categorical Analysis**: Bar charts and count plots for neighborhood and room type distributions.

## Key Insights
* Distribution of property types varies significantly by borough.
* Manhattan and Brooklyn represent the highest density of listings.
* Correlation analysis reveals the impact of availability and minimum nights on listing popularity.

## Requirements
To run the analysis locally, ensure you have the following Python packages installed:
* pandas
* numpy
* matplotlib
* seaborn

## Usage
1. Clone this repository.
2. Ensure the dataset `airbnb_datasets.csv` is in the project root.
3. Open `Airbnb_EDA.ipynb` in a Jupyter environment.
4. Run all cells to generate the analysis and visualizations.

## License
This project is for educational and analytical purposes.
