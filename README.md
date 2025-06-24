# Flight Delay Dataset - Outlier Analysis

This project involves outlier detection and basic data cleaning on a Airline Passenger Satisfaction dataset.

## Dataset

The dataset includes flight details and customer satisfaction data. Key numerical columns analyzed:
- Arrival Delay in Minutes
- Departure Delay in Minutes
- Flight Distance

## Methods

Two statistical methods were used to detect outliers:
- IQR (Interquartile Range)
- Z-Score

Manual threshold was also applied to filter flights shorter than 150 km.

## Steps

- Missing values in "Arrival Delay in Minutes" were filled with the column mean.
- Outliers were visualized using histograms.
- Outliers were removed based on defined thresholds.
- Cleaned data was saved for further use.

## Tools

- Python
- Pandas, NumPy, Matplotlib, Seaborn, SciPy

## Output

Final cleaned dataset and visualizations are included.
