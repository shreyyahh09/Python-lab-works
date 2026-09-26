# Agricultural Price Trends in India 📊🌾 
http://localhost:8888/notebooks/Agricultural%20Data%20Analysis.ipynb 

## Overview

Agriculture plays an important role in India's economy, and understanding agricultural commodity prices is important for farmers, traders, policymakers, researchers, economists, and consumers.

This project analyses agricultural commodity price data across different states, districts, markets, and commodities in India. The analysis uses Python and data visualization techniques to understand variations in minimum, maximum, and modal prices and to identify relationships between different price variables.

The purpose of the project is to use data-driven analysis to understand agricultural price patterns and explore how such information can support better decision-making in agriculture and related markets.

## Objective

The main objective of this project is to analyse agricultural commodity price trends and understand their variation across different markets and geographical locations.

Specifically, the analysis focuses on:

- Understanding minimum, maximum, and modal prices of agricultural commodities.
- Examining the distribution of commodities across Indian states and districts.
- Identifying commodities with relatively high and low price levels.
- Studying the relationship between minimum, maximum, and modal prices.
- Exploring commodity distribution in Chhattisgarh.
- Using visualizations to communicate important patterns in the dataset.
- Understanding how agricultural price information can be useful for different stakeholders.

## Dataset

The dataset contains information on agricultural commodities traded across different markets in India.

The major variables include:

| Variable | Description |
|----------|-------------|
| `state` | State where the market is located |
| `district` | District where the market is located |
| `market` | Agricultural market |
| `commodity` | Name of the agricultural commodity |
| `variety` | Variety of the commodity |
| `arrival_date` | Date of commodity arrival |
| `min_price` | Minimum recorded price |
| `max_price` | Maximum recorded price |
| `modal_price` | Modal/most commonly observed price |

The dataset initially contained **2,238 observations and 9 variables**. After removing duplicate observations, the dataset contained **2,236 observations**.

## Tools & Technologies

The analysis was conducted using:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Analysis Process

The analysis followed the following steps:

1. Imported the required Python libraries.
2. Loaded the agricultural commodity dataset.
3. Examined the structure and data types of the variables.
4. Checked the dimensions and observations of the dataset.
5. Checked for duplicate and missing values.
6. Examined the different commodities, states, and districts present in the dataset.
7. Generated descriptive statistics for the price variables.
8. Analysed the relationship between minimum, maximum, and modal prices.
9. Created different visualizations to understand price patterns and commodity distribution.
10. Interpreted the results from an economic and market perspective.

## Exploratory Data Analysis

### 1. Descriptive Statistics

The descriptive analysis showed considerable variation in agricultural commodity prices.

For the three major price variables:

- Mean minimum price: **2451.27**
- Mean maximum price: **2851.29**
- Mean modal price: **2694.12**

The maximum recorded values were:

- Minimum price: **110,000**
- Maximum price: **130,000**
- Modal price: **120,000**

This indicates substantial variation in commodity prices across markets and commodities.

## 2. Price Correlation

The analysis examined the correlation between minimum, maximum, and modal prices.

The correlation coefficients were:

| Variables | Correlation |
|-----------|-------------|
| Minimum Price – Maximum Price | 0.9755 |
| Minimum Price – Modal Price | 0.9853 |
| Maximum Price – Modal Price | 0.9943 |

The correlation matrix and heatmap show a strong positive relationship among the three price variables.

This suggests that changes in one measure of commodity price are closely associated with changes in the other price measures within the dataset.

## 3. Commodity Distribution Across States

The project also examines the number of commodity observations across different Indian states.

The visualization shows that the dataset has considerable variation in the number of observations across states, with Uttar Pradesh and Kerala representing a relatively large share of the observations.

This helps demonstrate how agricultural market observations are distributed geographically within the dataset.

## 4. Chhattisgarh Analysis

A separate analysis was conducted for Chhattisgarh to understand the district-wise distribution of commodities.

The dataset contains observations from districts including:

- Bastar
- Raipur

and other districts represented in the dataset.

The district-level visualization helps provide a more localized understanding of agricultural commodity observations within the state.

## 5. Commodity Price Analysis

The project also examines minimum, maximum, and modal prices across commodities.

Bar plots were used to compare price levels for selected commodities.

The analysis indicates that agricultural commodities can exhibit substantial differences in their observed price levels.

For example, the visualizations show relatively high observed prices for commodities such as:

- Arecanut (Betelnut/Supari)
- Sesamum (Sesame, Gingelly, Til)
- Apple
- Amaranthus

The exact price levels vary depending on the market and observation.

## 6. Price Visualization

Several visualization techniques were used, including:

- Bar plots
- Scatter plots
- Heatmaps
- Pie charts
- Seaborn categorical plots

These visualizations were used to understand:

- Price variation
- Commodity distribution
- State-wise distribution
- District-wise distribution
- Relationships between price variables

## Economic Interpretation

Agricultural prices are influenced by several factors, including market conditions, supply, demand, arrivals, location, commodity characteristics, and market-level differences.

Understanding price patterns can therefore be useful for different stakeholders.

### For Farmers

Price information can help farmers understand market conditions and make better decisions regarding production and selling.

### For Traders

Market and arrival information can potentially support decisions related to market timing, supply-chain planning, and logistics.

### For Policymakers

Understanding agricultural price variation can help in identifying areas where market interventions, infrastructure, storage facilities, or other agricultural policies may be required.

### For Economists and Researchers

Agricultural price data can be used to study market behaviour, price variation, supply conditions, regional differences, and relationships between agricultural markets.

## Key Findings

The analysis provides the following broad insights:

- Agricultural commodity prices vary considerably across observations.
- Minimum, maximum, and modal prices show strong positive correlations.
- The dataset contains a wide variety of agricultural commodities.
- Commodity observations vary substantially across Indian states and districts.
- Agricultural price patterns can be explored through multiple dimensions such as commodity, state, district, market, and arrival date.
- Data visualization provides a useful way of identifying patterns that may not be immediately visible from the raw dataset.

## Recommendations

Based on the analysis, agricultural price data can potentially be used for:

- Market-timing analysis for traders.
- Supply-chain and logistics planning.
- Monitoring commodity price movements.
- Identifying regional differences in agricultural markets.
- Supporting evidence-based agricultural policy.
- Further research on agricultural price forecasting.

A useful extension of this project would be to incorporate time-series methods to study how commodity prices change over time and potentially develop price forecasting models.

## Conclusion

This project demonstrates how Python-based data analysis and visualization can be used to explore agricultural commodity prices in India.

The analysis highlights significant variation in agricultural prices and shows strong relationships between minimum, maximum, and modal prices. It also demonstrates the geographical distribution of agricultural commodities across states and districts.

Overall, the project shows how data-driven approaches can provide useful insights for understanding agricultural markets and can serve as a foundation for further research in agricultural economics, price forecasting, and market analysis.

## Future Scope

The analysis can be extended further by:

- Conducting time-series analysis of commodity prices.
- Developing commodity price forecasting models.
- Studying seasonal patterns in agricultural prices.
- Comparing agricultural prices across states.
- Examining the relationship between arrivals and prices.
- Applying econometric models to identify determinants of agricultural prices.
- Developing interactive dashboards using Power BI or Tableau.

## References

The project used learning resources and documentation from:

- GeeksforGeeks
- W3Schools
- Google Colab examples
- ChatGPT

## Author

**Shreya Kispotta**

MSc Economics & Analytics

Interested in Economics, Data Analytics, Econometrics, and Research.
