# TASK 2
# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING

COMPANY: CODTECH IT SOLUTIONS

NAME: ASMITHA SRI R

INTERN ID: CTOBDG1383

DOMAIN: DATA ANALYTICS

DURATION: 8 WEEKS

MENTOR: NEELA SANTOSH

CODE OF THE TASK:https://nbviewer.org/github/Asmitha-GitHub/PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING/blob/main/PREDICTIVE_ANALYSIS_USING_MACHINE_LEARNING.ipynb

DESCRIPTION OF TASK 2:
During the continuation of my internship at CodTech IT Solutions, guided by my mentor Neela Santosh, I was assigned Task 2 under the domain of Predictive Analysis using Machine Learning. This task focused on building a complete machine learning pipeline from scratch to predict house prices using supervised learning techniques in Python.

I used the popular House Prices: Advanced Regression Techniques dataset which contains numerous features about residential homes including lot size, neighborhood, number of rooms, garage type, and many more. The dataset was split into two files: train.csv and test.csv. My work was centered on the train.csv file for training and evaluating the model.

To begin, I loaded the dataset into Pandas DataFrame in Google Colab and examined the data by displaying the first few rows and checking the shape. I identified and handled missing values using appropriate techniques — columns with excessive null values (like PoolQC, MiscFeature, and Alley) were dropped, while others were imputed using mean/mode depending on the data type.

Next, I performed exploratory data analysis (EDA) to understand relationships between different features and the target variable SalePrice. I used seaborn and matplotlib libraries to plot heatmaps, histograms, and scatter plots. I specifically analyzed features with high correlation to SalePrice, such as OverallQual, GrLivArea, GarageCars, and TotalBsmtSF, which were later selected as important predictors.

Then came feature encoding, where I transformed categorical variables into numeric form using label encoding and one-hot encoding to make them compatible with machine learning algorithms.

For model training, I applied both:

Linear Regression, as a baseline model

Random Forest Regressor, to improve prediction accuracy

Each model was evaluated using Mean Squared Error (MSE) and R² Score. The best-performing model achieved an R² score of 0.7959, indicating a strong fit. I also analyzed feature importance from the Random Forest model to better understand which features were contributing most to the predictions.

This task gave me hands-on experience in the entire machine learning lifecycle — from data preprocessing, feature selection, encoding, training, to model evaluation. I learned the importance of clean data, understood various performance metrics, and practiced comparing models to select the most optimal one.

Overall, Task 2 helped me strengthen my foundation in machine learning using real-world data and prepared me to handle predictive analytics projects independently in the future.

OUTPUT:

![Image](https://github.com/user-attachments/assets/ff4d3979-507a-421b-ab6d-24ca740b6371)
