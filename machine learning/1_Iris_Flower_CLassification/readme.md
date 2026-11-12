# Exploratory Data Analysis (EDA) – Iris Flower Classification Dataset

## 1. Project Overview

The objective of this project is to perform Exploratory Data Analysis (EDA) on the Iris Flower Classification dataset to understand the underlying patterns, distributions, and relationships among the features.

The analysis aims to identify which flower characteristics are useful for distinguishing between the three Iris species: **Iris-setosa, Iris-versicolor, and Iris-virginica**.

The insights obtained from this analysis will serve as a foundation for developing machine learning classification models.

## 2. Problem Statement

Iris flower classification is a supervised machine learning problem that involves predicting the species of an Iris flower based on its physical measurements.

The objective of this project is to explore the dataset and understand how sepal and petal measurements vary across the three species.

The features used for analysis are:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## 3. Dataset Description

- **Dataset Source:** [Iris Flower Classification – Kaggle](https://www.kaggle.com/datasets/uciml/iris)
- **Number of Instances:** 150
- **Number of Numerical Features:** 4
- **Target Variable:** Species
- **Number of Classes:** 3

The Iris dataset is one of the earliest and most widely used datasets in statistical analysis and machine learning research.

It contains 150 observations, equally distributed across three Iris species, with 50 observations per species.

One species is linearly separable from the other two, whereas the remaining two species are not linearly separable from each other.

### Features Description

| Feature | Description |
|---|---|
| SepalLengthCm | Length of the sepal in centimeters. |
| SepalWidthCm | Width of the sepal in centimeters. |
| PetalLengthCm | Length of the petal in centimeters. |
| PetalWidthCm | Width of the petal in centimeters. |
| Species | Target variable representing the Iris flower species. |

## 4. Tools and Libraries

The following tools and Python libraries were used:

- **Python:** Programming language for data analysis.
- **Pandas:** Data manipulation and analysis.
- **NumPy:** Numerical computations.
- **Matplotlib:** Data visualization.
- **Seaborn:** Statistical data visualization.

## 5. EDA Methodology

The following steps were performed to explore and understand the dataset:

1. **Data Inspection:** Examined the dataset structure, dimensions, data types, and statistical summaries.
2. **Data Quality Checks:** Checked for missing values, duplicate records, and inconsistencies.
3. **Univariate Analysis:** Analyzed individual feature distributions using histograms, density plots, and box plots.
4. **Bivariate Analysis:** Explored relationships between numerical features and compared feature distributions across species.
5. **Correlation Analysis:** Examined correlations among numerical features using a correlation matrix and heatmap.
6. **Outlier Detection:** Investigated potential outliers using box plots.

## 6. Visualizations

The following visualizations were created to understand feature distributions, relationships, and patterns in the dataset.

### 6.1 Feature Distributions

![Feature Distributions](https://github.com/user-attachments/assets/00bacf18-865f-452e-bd6e-7960aa16d48a)

### 6.2 Univariate Analysis

![Univariate Analysis](https://github.com/user-attachments/assets/64d4eb73-596a-495e-8f5b-873bf242f653)

### 6.3 Bivariate Analysis

![Bivariate Analysis](https://github.com/user-attachments/assets/73f222a2-a327-40f3-978c-c367393bd771)

### 6.4 Correlation Analysis

![Correlation Heatmap](https://github.com/user-attachments/assets/5babc333-7ebc-4eb0-8dee-74e28ba72f02)

## 7. Key Findings and Observations

- **Species Distribution:** The dataset is balanced, with 50 observations belonging to each of the three Iris species.
- **Feature Distributions:** Sepal and petal measurements exhibit different distribution patterns across the three species.
- **Species Separation:** Iris-setosa is distinctly separated from the other two species based on petal measurements.
- **Feature Overlap:** Iris-versicolor and Iris-virginica exhibit some overlap in their feature distributions, making their classification comparatively more challenging.
- **Feature Correlation:** Petal length and petal width exhibit a strong positive correlation. Sepal measurements also show correlations, although generally weaker.
- **Data Quality:** The dataset contains no missing values or duplicate records, indicating that it is relatively clean.

## 8. Conclusion

The exploratory data analysis reveals that petal measurements, particularly petal length and petal width, are important features for distinguishing between the three Iris species.

Iris-setosa is easily distinguishable from Iris-versicolor and Iris-virginica, while the latter two exhibit some overlap in their measurements.

The correlation analysis highlights strong relationships between certain numerical features, which should be considered during subsequent model development.

The dataset is well-structured, balanced across all three species, and contains no missing or duplicate records.

Overall, the findings provide a foundation for the next stage of the machine learning workflow: **feature analysis, classification model development, training, and evaluation.**
