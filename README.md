# iris-dataset-analysis
Exploring and visualizing the Iris dataset using Python
~STEP BY STEP PROCESS-

###📊 Exploring and Visualizing the Iris Dataset
-📌 Project Overview

-This project is part of a data exploration and visualization exercise using the famous Iris flower dataset.
-The goal is to load, inspect, and visualize the dataset to understand its trends, distributions, and relationships.

###🎯 Objectives

-Load and inspect the Iris dataset using Pandas.

-View dataset shape, column names, and first rows.

-Generate summary statistics.

-Visualize the dataset using Matplotlib and Seaborn:

-Scatter plots to show relationships between features.

-Histograms to visualize value distributions.

-Box plots to detect outliers.

###🛠️ Tools & Libraries

-Python 3

-Pandas → Data manipulation & analysis

-Matplotlib → Data visualization

-Seaborn → Advanced visualizations & dataset loading

###📂 Dataset

-The Iris dataset contains 150 rows and 5 columns:

-sepal_length (cm)

-sepal_width (cm)

-petal_length (cm)

-petal_width (cm)

-species (Setosa, Versicolor, Virginica)

###🚀 Steps Performed

##Import Libraries

-import pandas as pd
-import seaborn as sns
-import matplotlib.pyplot as plt


##Load Dataset

-iris = sns.load_dataset('iris')


##Inspect Data

-print(iris.shape)
-print(iris.columns)
-print(iris.head())
-print(iris.info())
-print(iris.describe())


##Visualizations

#Scatter Plot

-sns.scatterplot(data=iris, x='sepal_length', y='sepal_width', hue='species')
plt.show()


#Histograms

-iris.hist(figsize=(10, 8))
plt.show()


#Box Plots

-sns.boxplot(data=iris)
plt.show()
