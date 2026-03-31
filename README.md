# Supermarket Sales Data Cleaning, Analysis & Visualization

## Project Overview

This project performs **end-to-end data analysis** on a supermarket sales dataset. It includes data cleaning, preprocessing, exploratory data analysis (EDA), outlier detection, and data visualization using Python.

The goal is to transform raw data into meaningful insights by applying real-world data science techniques.

---

## Features

✔ Data Cleaning & Preprocessing
✔ Handling Missing Values & Duplicates
✔ Standardizing Data Formats (Date, Time, Text)
✔ Univariate & Bivariate Analysis
✔ Outlier Detection (Boxplot, Histogram, Z-score, IQR)
✔ Data Visualization using Pandas, Matplotlib & Seaborn

---

## Dataset Columns

* Invoice ID
* Branch
* City
* Customer Type
* Gender
* Product Line
* Unit Price
* Quantity
* Tax 5%
* Total
* Date
* Time
* Payment
* COGS
* Gross Margin Percentage
* Gross Income
* Rating

---

## Technologies Used

* Python 
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Data Cleaning Steps

* Checked and handled missing values
* Removed duplicate records
* Converted Date to **YYYY/MM/DD format**
* Converted Time to **12-hour format (AM/PM)**
* Standardized text data to **Title Case**
* Fixed inconsistent data formats

---

## Data Analysis

### Univariate Analysis

* Distribution of Unit Price using histogram
* Histograms + KDE for all numerical columns

### Bivariate Analysis

* Scatter plots for relationships between numerical variables
* Box plots for categorical vs numerical analysis

---

## Outlier Handling

* Detected using:

  * Box plots
  * Histograms
  * Z-score method
  * IQR method
* Removed outliers using IQR method
* Verified dataset after removal

---

## Data Visualization

### Pandas Plots

* Area Plot
* Bar Plot
* Horizontal Bar Plot
* Line Plot
* Scatter Plot
* Histogram
* KDE Plot
* Box Plot
* Hexbin Plot
* Pie Chart

### Seaborn Plots

* Distribution Plots (Hist, KDE, Rug)
* Relationship Plots (Joint, Pair)
* Categorical Plots (Box, Violin, Strip, Swarm, Bar, Count, Catplot)
* Heatmap (Correlation Matrix)

---

## Key Insights

* Sales vary across product lines and cities
* Customer payment preferences are clearly visible
* Strong relationship between Total and Gross Income
* Outliers can significantly affect analysis results

---

## Conclusion

This project demonstrates how proper data cleaning, analysis, and visualization can help uncover valuable insights from raw data. It highlights the importance of preprocessing and exploratory analysis in real-world data science workflows.

---

## How to Run

1. Clone the repository
2. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Run the Jupyter Notebook or Python script



⭐ If you like this project, feel free to star the repository!
