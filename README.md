# Japan Population Analysis

This project analyzes population distribution across Japanese prefectures using real census data.  
The goal of the project was to apply statistical concepts such as central tendency, variability, and data visualization to a real-world dataset using Python.

---

## Objective

The main objectives of this project were:

- To explore population distribution across Japanese prefectures
- To apply statistical measures such as:
  - Mean
  - Median
  - Range
  - Interquartile Range (IQR)
  - Variance
  - Standard Deviation
- To visualize the data using graphs
- To understand how population is unevenly distributed across regions

---

## Dataset

The dataset contains Japanese census data categorized by:

- Prefecture
- Age group
- Gender
- Year
- Population

The dataset was cleaned and processed using pandas before analysis.

---

## Data Cleaning

Several preprocessing steps were performed before analysis:

- Removed unnecessary columns
- Filtered the dataset to keep only the latest available year
- Standardized prefecture naming (e.g., Tokyo Metropolis → Tokyo Prefecture)
- Grouped population data by prefecture

During analysis, inconsistencies in aggregation were identified and investigated to ensure the population calculations were meaningful.

---

## Exploratory Data Analysis

Basic exploratory analysis was performed to understand:

- Dataset structure
- Data types
- Missing values
- Summary statistics

The analysis showed that population values varied significantly across prefectures.

---

## Statistical Analysis

The following statistical measures were analyzed:

### Central Tendency
- Mean
- Median

### Measures of Spread
- Range
- Interquartile Range (IQR)
- Variance
- Standard Deviation

The results showed that:
- The mean population was significantly higher than the median
- Population distribution was right-skewed
- A few prefectures had extremely large populations compared to others

---

## Visualizations

The following visualizations were created:

- Histogram of population distribution
- Boxplot for spread and outlier detection
- Most populated prefectures bar chart
- Least populated prefectures bar chart

These visualizations helped confirm:
- Population imbalance
- High variability
- Presence of outliers

---

## Key Findings

- Population distribution across Japanese prefectures is highly uneven
- A few prefectures such as Tokyo contain significantly larger populations
- The dataset showed strong right-skewness
- Variance and standard deviation were very large, indicating high spread
- Median provided a more stable measure of central tendency than the mean

---

## Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Git & GitHub

---

## Conclusion

This project demonstrates how statistical concepts can be applied to real-world datasets using Python.

In addition to statistical analysis, the project also involved:
- data cleaning
- debugging aggregation issues
- validating unexpected results
- interpreting visualizations

The project helped strengthen both statistical understanding and practical data analysis skills.
