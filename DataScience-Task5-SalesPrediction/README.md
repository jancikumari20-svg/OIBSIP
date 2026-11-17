Sales Prediction Using Python

Oasis Infobyte Internship, Data Science Track, Task 5

By Janci Kumari

About this project

I built regression models that predict product sales from the money spent on advertising on TV, Radio and Newspaper.

Dataset

I used the classic Advertising dataset. It has 200 rows with the advertising spend on TV, Radio and Newspaper and the resulting sales. There are no missing values.

Tools used

Python, pandas, numpy, matplotlib, seaborn, scikit-learn and Jupyter Notebook (Google Colab).

What I did

First I checked the data for missing values and looked at the descriptive statistics.

Then I made a pairplot, scatter plots of Sales against each channel, and a correlation heatmap. TV has the strongest correlation with Sales (0.78), then Radio (0.58) and Newspaper (0.23).

After that I split the data 80/20 and trained two models: Linear Regression as the baseline and a Random Forest Regressor.

I evaluated both models with MAE, RMSE and R2 score, and also with 5-fold cross-validation. I made a residual plot for the best model.

Results

Linear Regression: MAE 1.461, RMSE 1.782, R2 0.899

Random Forest: MAE 0.629, RMSE 0.757, R2 0.982

Random Forest is the best model. Its residuals look random and are mostly between -1 and +1.

Which channel matters most

TV has the highest overall impact. Radio is second, and each extra unit spent on Radio increases sales more than a unit spent on TV. Newspaper has almost no impact.

Files in this folder

Task5_Sales_Prediction.ipynb is the full notebook with code, outputs and explanations.

How to run

Open the notebook in Google Colab and run all the cells. The dataset is loaded from the internet, so no download is needed.
