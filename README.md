# Hotel Bookings Exploratory Data Analysis (EDA)

This repository contains an exploratory data analysis (EDA) of hotel booking data. The project aims to uncover insights and patterns within the dataset, which includes information about hotel bookings such as lead time, cancellation rates, customer types, and more.

---

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [EDA Highlights](#eda-highlights)
- [Visualizations](#visualizations)
- [Insights](#insights)
- [Contributing](#contributing)
- [License](#license)

---

## Overview
This project analyzes a dataset of hotel bookings to explore trends and patterns. The analysis includes data cleaning, statistical summaries, and visualizations to better understand customer behavior and booking trends.

---

## Dataset
The dataset used in this analysis contains 32 columns and over 119,000 rows. Key features include:
- **Hotel type**: Resort Hotel or City Hotel
- **Is Canceled**: Whether the booking was canceled (1) or not (0)
- **Lead Time**: Number of days between booking and check-in
- **Customer Type**: Categories like Transient, Group, etc.
- **Reservation Status**: Status of the booking (e.g., Check-Out, Canceled)

### Sample Data
Here is a preview of the dataset:

| Hotel         | Is Canceled | Lead Time | Arrival Date Year | Arrival Date Month | Stays in Weekend Nights | Adults |
|---------------|-------------|-----------|-------------------|--------------------|--------------------------|--------|
| Resort Hotel  | 0           | 342       | 2015              | July               | 0                        | 2      |
| Resort Hotel  | 0           | 737       | 2015              | July               | 0                        | 2      |

---

## EDA Highlights
The analysis includes:
1. **Data Cleaning**: Handling missing values and ensuring data consistency.
2. **Descriptive Statistics**: Summarizing key metrics like mean, median, and standard deviation.
3. **Correlation Analysis**: Identifying relationships between variables such as lead time and cancellation rates.
4. **Visualization**: Using Seaborn and Matplotlib for insightful plots.

---

## Visualizations
Here are some key visualizations from the analysis:
1. **Cancellation Rates by Hotel Type**: A bar chart showing which hotel type has higher cancellation rates.
2. **Lead Time Distribution**: A histogram displaying the distribution of lead times for bookings.
3. **Customer Type Analysis**: Pie charts showing the proportion of different customer types.

---

## Insights
Key findings from the analysis include:
1. **Cancellation Trends**:
   - City Hotels have a higher cancellation rate compared to Resort Hotels.
2. **Lead Time Impact**:
   - Longer lead times are associated with higher cancellation probabilities.
3. **Customer Preferences**:
   - Most bookings are made by transient customers with short stays.

---
