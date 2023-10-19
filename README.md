# Global Stock Price Archive 

This analysis conducts a comprehensive analysis of a dataset containing global stock price information. The dataset includes data related to various stock indices, companies, and their stock price details such as opening, highest, lowest, closing prices, adjusted closing prices, and traded shares. The dataset is structured around key attributes, including company name, stock ticker symbols, currency, and exchange markets.

**[Global Stock Price Archive](https://www.kaggle.com/datasets/adityakishor1/global-stock-price-archive/)** from **[Kaggle](https://www.kaggle.com)**.

## Key Steps

### Data Exploration

The analysis begins with a data exploration phase to understand the dataset's content and quality:

- **Import Libraries**, we start by importing essential Python libraries, including Pandas for data manipulation, NumPy for numerical operations, Matplotlib and Seaborn for data visualization, and additional libraries for specific analysis techniques.

- **Global Options**, visual style settings for Seaborn are configured for better visualizations throughout the notebook.

- **Data Import**, the dataset is loaded using Pandas, and its initial rows are displayed to get an overview of the data structure. Missing values, duplicates, and outliers are checked to ensure data integrity and quality.

### Data Cleaning

The data cleaning process ensures the dataset is free from irrelevant information and missing values:

- **Dropping Duplicates**, duplicate rows in the dataset are removed to eliminate redundancy.

- **Handling Missing Values**, rows with missing values are dropped to maintain data quality.

### Descriptive Statistics

A summary of key statistical measures for the numeric columns in the dataset is presented:

- Mean
- Standard Deviation
- Minimum
- Maximum

### Currency and Exchange Analysis

This section explores the distribution of companies based on different currencies and stock exchanges:

- **Counting Companies per Currency**, the number of companies operating in each currency is calculated, and the most common currency is identified.

- **Counting Companies per Exchange**, the number of companies listed on different exchanges is counted, and the most common exchange is identified.

### Price Distribution Analysis

An analysis of the distribution of opening, highest, lowest, closing, and adjusted closing prices is visualized:

- **Box Plots** ,the distribution of these prices is visualized using box plots, providing insights into price variation.

### Correlation Analysis

This section investigates correlations between numeric attributes in the dataset:

- **Correlation Matrix**, a correlation matrix is calculated, showing how numeric variables are related to one another. A heatmap is generated to visualize these correlations.

### Conclusion

This analysis provides a comprehensive overview of the dataset, including its content, quality, and key statistical measures. The analysis also explores the distribution of companies based on different currencies and stock exchanges. Finally, the distribution of opening, highest, lowest, closing, and adjusted closing prices is visualized, and correlations between numeric attributes are investigated.
