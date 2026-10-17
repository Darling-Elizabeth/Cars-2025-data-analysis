# Cars Analysis

An investigation of **car prices, engine sizes, and battery capacities** using the 2025 cars dataset from Kaggle.

## Dataset
- Source: Kaggle, `abdulmalik1518/cars-datasets-2025`
- 1,206 cars with company, model, engine, capacity, top speed, acceleration, and price

## Questions
- How are car prices distributed, and which brands are the most expensive?
- How large are engines and batteries?
- Are bigger engines or batteries associated with higher prices?
- How do electric and fuel cars compare?

## What I did
1. Loaded and inspected the data
2. Cleaned text columns into numbers (price, speed, acceleration)
3. Split the capacity column into engine size (cc) and battery size (kWh)
4. Handled price ranges by taking the average of the low and high values
5. Explored each topic with summary statistics and `groupby`
6. Visualized the data with histograms, bar charts, boxplots, and scatter plots

## Key findings
- [Median price vs mean price, and what it shows]
- [How electric cars compare with fuel cars in price]
- [Relationship between engine size / battery capacity and price]
- [Most expensive brands]

## Tools
Python, pandas, NumPy, matplotlib, seaborn

## Files
- `cars_analysis.ipynb`: the full notebook with code, charts, and explanations
