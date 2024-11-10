# COTECH-TASK-2

**CO-TECH INTERNSHIP – TASK 2** 
**PREDICTIVE MODELING WITH LINEAR REGRESSION**

NAME: SAYEEDA MISBAH ILYAS                                                                                                                                                                                                                           
COMPANY: COTECH IT SOLUTIONS                                                                                                                                                                                                                              
ID: CT08DS9133                                                                                                                                                                                                                                        
DOMAIN: DATA SCIENCE                                                                                                                                                                                                                                
DURATION: OCT - NOV 2024                                                                                                                                                                                                                             
MENTOR: 

**1. Project Overview**

- This project involves analyzing the *Iris dataset*, a well-known dataset in machine learning and statistics, 
- It *aims* to apply predictive modeling using linear regression to the Iris dataset, a widely used dataset in machine learning. The dataset contains measurements of iris flowers, including features such as sepal length, sepal width, petal length, and petal width across three different species of irises: Setosa, Versicolor, and Virginica.

- The *goal* of this project is to predict one of the features of the Iris dataset, such as petal length, using linear regression. In this context, linear regression will help establish a relationship between the target feature (e.g., petal length) and the other available features (e.g., sepal length, sepal width, petal width).

*The project focuses on*

1. Data Exploration: Understanding the structure of the dataset through descriptive statistics and visualizations.
2. Feature Analysis: Examining the relationships and variations in the features to identify important predictors for classifying flower species.
3. Modeling: Using machine learning algorithms to develop a model that can accurately classify the species based on the given features.
4. Evaluation: Assessing model performance using metrics like accuracy and confusion matrices to validate the model's effectiveness.

**2. Dataset Description**

- The **Iris Dataset** contains 150 observations of iris flowers, with 50 samples from each of the three species:
- Iris setosa, Iris versicolor, and Iris virginica. The dataset includes the following attributes:
•	*Sepal Length (cm)*: Continuous variable representing the length of the sepal.
•	*Sepal Width* (cm): Continuous variable representing the width of the sepal.
•	*Petal Length* (cm): Continuous variable representing the length of the petal.
•	*Petal Width* (cm): Continuous variable representing the width of the petal.
•	*Species*: Categorical variable representing the species of the iris flower, with values: 'Iris setosa', 'Iris versicolor', and 'Iris virginica'

***Step 1: Set Up the Notebook Environment***

Import all necessary libraries. Comment each import line for clarity.

**Libraries Used**
pandas: For data manipulation and analysis (loading, cleaning, transforming data).
numpy: For numerical operations and handling arrays.
matplotlib: For creating static, animated, and interactive visualizations.

**Step 2: Load and Explore the Dataset**

Data Loading: Loaded the Iris dataset into a pandas DataFrame from a CSV file.
To Display the first few rows of the dataset
The data.head() method allows you to quickly see the structure of the dataset. For this task, we're assuming petal length as the feature and petal width as the target variable.

**Step 3: Select Features and Target Variables**
Identify and isolate the feature (independent variable) and the target (dependent variable) for the linear regression model.

**Step 4: Split the Data into Training and Testing Sets**

Split the data to separate training and testing subsets.
Training data is used to fit the model, and testing data evaluates its performance.

**Step 5: Train the Linear Regression Model**

Create a Linear Regression model instance, then fit it to the training data.
The .fit() function trains the model using X_train (feature data) and y_train (target data).

**Step 6: Make Predictions and Evaluate the Model**
With the use of LinearRegression model to make predictions on the test data , evaluate its performance using Mean Squared Error (MSE) and R-squared (R²).


MODELING WITH LINEAR REGRESSION :

MSE -  measures the average squared difference between predicted and actual values.
R²  - indicates the proportion of variance in the target variable explained by the model; values closer to 1 imply a better fit.

**Step 7: Visualize the Result**
By plotting the graph for [SIMPLE LINEAR REGRESSION] . This plot helps visualize how well the model has fit the training data.

Training Plot: The red regression line indicates the model's fit on the training set. Blue dots represent the actual training data points.
Test Plot: Green dots represent actual values, while purple dots represent predicted values, showing how well predictions match actual results.

The regression line and actual vs. predicted plot illustrate that the model is reasonably accurate for this linear relationship.

**INSIGHTS**

The descriptive statistics of the Iris dataset show that sepal length has a mean of 5.8 cm with moderate variability, while petal length has a mean of 3.7 cm and greater variation. Petal width has a mean of 1.3 cm, with a range from 0.1 cm to 2.5 cm, suggesting it plays a key role in distinguishing flower species. Sepal width shows a wider range, with some potential outliers. All features have no missing values, indicating a clean dataset for analysis.

**INTERPRETATIONS:**

1. Model Accuracy: R-squared value shows how well the model explains variance in the target.
2. Error Analysis: Mean Squared Error gives an idea of the average prediction error magnitude.
3. Visual Assessment: Use the Actual vs. Predicted plot to assess if predictions closely follow actual values.

**CONCLUSION**
The descriptive statistics of the Iris dataset show that sepal length has a mean of 5.8 cm with moderate variability, while petal length has a mean of 3.7 cm and greater variation. Petal width has a mean of 1.3 cm, with a range from 0.1 cm to 2.5 cm, suggesting it plays a key role in distinguishing flower species. Sepal width shows a wider range, with some potential outliers. All features have no missing values, indicating a clean dataset for analysis.

***THIS IS MY PROJECT CREATED BY - SAYEEDA MISBAH ILYAS***

**Github account for more infomation : https://github.com/codemisba**

**Linkdin account : https://www.linkedin.com/in/sayeeda-misbah-ilyas/**

