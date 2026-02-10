# Uber Trip Analysis with PySpark

Analysis of Uber ride-sharing data during a two-week period using PySpark for distributed data processing.

## Problem Statements

1. Which date had the most completed trips?
2. What was the highest number of completed trips within a 24-hour period?
3. What percentage of all zeroes occurred on weekends (Friday 5pm to Sunday 3am)?

## Technologies Used

- **PySpark** - Distributed data processing
- **Python** - Data analysis and transformation
- **Google Colab** - Development environment

## Dataset

The dataset contains Uber trip data with the following columns:
- Date|Time (Local)
- Eyeballs
- Zeroes
- Completed Trips
- Requests
- Unique Drivers

## Key Techniques

- Handling NULL values with forward fill using Window functions
- Date type conversions and parsing
- Aggregations and groupBy operations
- Time-based filtering for weekend analysis
- Column renaming and dataframe transformations

