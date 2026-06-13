
# Task 3: Exploratory Data Analysis (EDA) on Iris Dataset

## Overview

This project demonstrates Exploratory Data Analysis (EDA) on the famous Iris Dataset using Python. The objective of this analysis is to understand the dataset, identify patterns, visualize distributions, and explore relationships between different features.

---

## Objective

The main objectives of this project are:

* Understand the structure of the Iris dataset.
* Generate summary statistics.
* Check for missing values.
* Visualize feature distributions.
* Detect outliers.
* Analyze correlations between variables.
* Identify patterns and trends among different flower species.

---

## Tools and Libraries Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

## Dataset Information

The Iris dataset contains 150 observations and 5 columns:

1. Sepal Length (cm)
2. Sepal Width (cm)
3. Petal Length (cm)
4. Petal Width (cm)
5. Species

The dataset consists of three Iris flower species:

* Setosa
* Versicolor
* Virginica

---

## Steps Performed

### 1. Data Loading

* Loaded the Iris dataset using Scikit-learn.
* Converted the dataset into a Pandas DataFrame.

### 2. Data Inspection

* Checked dataset shape.
* Viewed column names.
* Inspected data types and structure.

### 3. Missing Value Analysis

* Verified that the dataset contains no missing values.

### 4. Summary Statistics

* Generated descriptive statistics using `describe()`.

### 5. Data Visualization

Created the following visualizations:

#### Histogram

* Analyzed the distribution of numerical features.

#### Boxplot

* Detected outliers and analyzed data spread.

#### Correlation Heatmap

* Examined relationships among numerical variables.

#### Pairplot

* Visualized feature relationships and species separation.

---

## Key Findings

* The dataset contains 150 records and no missing values.
* Petal Length and Petal Width have a very strong positive correlation (0.96).
* Sepal Length also shows a strong positive correlation with Petal Length.
* Setosa species is clearly distinguishable from the other species.
* Virginica generally has larger petal measurements.
* Petal features are more informative than sepal features for species classification.

---

## Conclusion

Exploratory Data Analysis helped in understanding the characteristics of the Iris dataset through statistical summaries and visualizations. The analysis revealed strong relationships among petal measurements and demonstrated clear separation of species, especially Setosa. The project highlights the importance of EDA as a foundational step before applying machine learning models.

---

## Author

Ankit Yadav

Data Science Internship - Task 3

