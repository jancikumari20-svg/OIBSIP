Iris Flower Classification

Oasis Infobyte Internship, Data Science Track, Task 1

By Janci Kumari

About this project

I built a machine learning model that identifies the species of an iris flower (Setosa, Versicolor or Virginica) from its measurements.

Dataset

I used the Iris dataset that comes built into scikit-learn. It has 150 flowers, 4 measurements for each (sepal length, sepal width, petal length, petal width) and 50 flowers of each species. There are no missing values.

Tools used

Python, pandas, matplotlib, seaborn, scikit-learn and Jupyter Notebook (Google Colab).

What I did

First I loaded the data and checked its shape, data types, missing values and basic statistics.

Then I made a pairplot and box plots to see how the species differ. Petal length and petal width separate the species best.

After that I split the data 80/20 into training and test sets and trained three models: Logistic Regression, KNN and Random Forest.

I compared the models using test accuracy, 5-fold cross-validation, confusion matrices and classification reports.

Results

Logistic Regression: test accuracy 0.967, cross-validation accuracy 0.973

KNN: test accuracy 1.0, cross-validation accuracy 0.973

Random Forest: test accuracy 0.9, cross-validation accuracy 0.967

KNN gave the best result and classified all 30 test flowers correctly. But the test set is small, and the cross-validation scores of all three models are very close, so the models perform almost the same. All of them only get confused between Versicolor and Virginica.

Files in this folder

Task1_Iris_Classification.ipynb is the full notebook with code, outputs and explanations.

The screenshots folder has screenshots of the outputs.

How to run

Open the notebook in Google Colab or Jupyter and run all the cells. No dataset download is needed.
