# Sales Analysis

This project analyzes sales data to extract meaningful insights using Python. The Jupyter notebook `SalesAnalysis.ipynb` includes data processing, visualization, and analysis steps to understand sales trends, peak times for orders, and other useful business insights.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Data Source](#data-source)
- [Analysis Steps](#analysis-steps)
- [Visualizations](#visualizations)
- [Contributing](#contributing)
- [License](#license)

## Installation

To run this project locally, ensure you have Python and Jupyter Notebook installed. You can install the necessary Python packages using:

```bash
pip install pandas matplotlib
```

## Usage

To use this project, open the `SalesAnalysis.ipynb` notebook in Jupyter Notebook or JupyterLab and run the cells. This will process the sales data and generate visualizations and analysis results.

```bash
jupyter notebook SalesAnalysis.ipynb
```

## Project Structure

- `SalesAnalysis.ipynb`: Main notebook containing the code for data processing, visualization, and analysis.

## Data Source

The sales data used in this analysis should be stored in a CSV file named `all_data.csv`. Ensure this file is in the same directory as the notebook. The dataset should include columns such as `Order ID`, `Product`, `Quantity Ordered`, `Price Each`, and `Order Date`.

## Analysis Steps

1. **Data Cleaning**: Remove NaN values, drop rows with incorrect data, and convert columns to appropriate data types.
2. **Data Augmentation**: Add new columns for `Month`, `Sales`, `City`, etc., to facilitate the analysis.
3. **Exploratory Data Analysis (EDA)**: Analyze sales trends, peak order times, most sold products, and other insights.
4. **Visualizations**: Generate bar charts, line plots, and other visualizations to present the analysis results.

## Visualizations

The notebook includes several visualizations, such as:
- **Monthly Sales**: Bar chart showing sales per month.
- **Sales by City**: Bar chart showing sales in different cities.
- **Peak Order Time**: Line plot showing the distribution of orders throughout the day.
- **Products Sold vs. Price**: Combined bar and line plot showing the quantity of products sold and their prices.
