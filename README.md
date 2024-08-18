
# Zomato Customer Behavior Analysis 📊

This project delves into customer preferences, spending habits, and rating trends using a dataset from Zomato. The analysis focuses on comparing online and offline orders across different types of restaurants.

## Project Overview 🚀

The main goal of this project is to extract insights about customer behavior in the context of online and offline food orders. The analysis includes:
- Distribution of restaurant types
- Voting patterns for different restaurant types
- Spending habits for online vs. offline orders
- Rating distributions and comparisons
- Order patterns across various restaurant types
- 

## Installation 🛠️

To run this project locally, you need to have Python installed along with the following libraries:
- Pandas
- Matplotlib
- Seaborn
- NumPy

Install the required packages using:

```bash
pip install -r requirements.txt
```

## Dataset 📁

The dataset used for this analysis is from Zomato and contains information on:
- Restaurant types
- Ratings
- Cost for two people
- Online vs. offline orders
- Customer votes

## Methods Used 🔍

1. **Data Cleaning**: Converting ratings to numeric format and handling missing values.
2. **Data Grouping**: Using `groupby` and `pivot_table` for summarizing data.
3. **Visualization**: 
   - **Count Plots**: To show the distribution of restaurant types.
   - **Bar Plots**: For summarizing votes by restaurant type.
   - **Pie Charts**: To visualize the proportion of votes.
   - **Box Plots**: To compare cost and rating distributions for online vs. offline orders.
   - **Heatmaps**: To show the distribution of online and offline orders across restaurant types.
4. **Statistical Analysis**: Comparing average spending for online and offline orders.

## Insights 💡

1. **Customer Preferences**: 
   - Dining restaurants are preferred for offline orders.
   - Cafes receive more online orders.
   - Buffets have an equal share of online and offline orders.

2. **Spending Patterns**: 
   - The average spending on online orders is ₹510.34.
   - The average spending on offline orders is ₹358.89.

3. **Rating Trends**:
   - Most ratings fall between 3.5 and 4.
   - Online orders tend to have higher ratings compared to offline orders.

## Visualizations 📈

Some key visualizations include:
- **Distribution Plots**: Showing the spread of ratings and costs.
- **Box Plots**: Highlighting the differences in cost and rating distributions between online and offline orders.
- **Heatmaps**: Illustrating the distribution of online and offline orders across different restaurant types.

## Conclusion 📝

This analysis provides valuable insights into customer behavior on Zomato. Understanding these patterns can help businesses in the food industry to tailor their strategies, optimize their offerings, and improve customer satisfaction.

