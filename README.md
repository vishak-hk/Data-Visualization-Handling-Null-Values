# Data Visualization and Null Value Handling in Python

## Part 1: Exploring Data Visualization in Python with Matplotlib

### Objective:
Learn how to use Matplotlib, a popular data visualization library in Python, by creating various visualizations on the "Iris" dataset.

1. **Importing Libraries:**
   Start by importing Matplotlib, NumPy, and pandas for data visualization and manipulation.

2. **Loading the Dataset:**
   Load the Iris dataset from sklearn.datasets, convert it into a pandas DataFrame.

3. **Line Plot:**
   Create line plots for each feature against the target variable (species). Customize with titles, axis labels, and legends.

4. **Scatter Plot:**
   Create scatter plots for each pair of features, coloring points by species. Customize with titles, axis labels, and legends.

5. **Histogram:**
   Create histograms for each feature, color bars by species. Customize with titles, axis labels, and bin settings.

6. **Bar Chart:**
   Create a bar chart for the target variable (species), showing species counts. Customize with titles, axis labels, and color schemes.

7. **Heatmap:**
   Create a heatmap showing the correlation matrix between features. Customize with titles and color schemes.

8. **Bonus:**
   Explore a different dataset and create a unique visualization using Matplotlib.

## Part 2: Handling Null Values in Python with Pandas

### Objective:
Learn how to handle null values in a dataset using Python with the Pandas library, using the "California Housing Prices" dataset.

1. **Importing Libraries:**
   Import Pandas, NumPy, and Scikit-learn for null value handling.

2. **Loading the Dataset:**
   Load the California Housing Prices dataset from sklearn.datasets, convert to a pandas DataFrame.

3. **Identifying Null Values:**
   Check for missing values and count them in each column.

4. **Dropping Null Values:**
   Remove rows with missing values (though none exist in the dataset).

5. **Filling Null Values:**
   Replace missing values in the "total_bedrooms" column with the median value (not applicable in this dataset).

6. **Interpolation:**
   Fill missing values in the "total_bedrooms" column using interpolation (not applicable in this dataset).
