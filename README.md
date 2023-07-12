# Wine Quality Prediction
This project aims to predict the quality of red wine based on various features using machine learning techniques.

### Install Dependencies and Setup
To run this project, make sure you have the following dependencies installed:

-pandas<br>
-numpy<br>
-matplotlib<br>
-seaborn<br>
-scikit-learn<br>

### Importing the Dataset
The dataset used for this project is **[Red Wine Quality](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)**. It contains various attributes of red wine and their corresponding quality ratings. 

### Exploring the Data
Before building the model, it's important to understand the data. Here are some exploratory data analysis (EDA) steps performed on the dataset:

-Checking the data types and dimensions of the dataset<br>
-Displaying the first few rows of the dataset<br>
-Checking for missing values<br>
-Visualizing the distribution of each feature using histograms<br>
-Creating pair plots to visualize the relationships between features<br>
-Creating a correlation heatmap to identify correlations between features<br>
-Creating boxplots to visualize the distribution and outliers of each feature<br>
-Creating a countplot to visualize the distribution of wine quality ratings<br>
-Creating a barplot to analyze the relationship between volatile acidity and wine quality<br>

### Data Preprocessing
To prepare the data for model training, the following steps are performed:

-Splitting the data into features (X) and target (y)<br>
-Scaling the features using a StandardScaler<br>
-Splitting the data into training and testing sets using train_test_split<br>

### Model Building
In this project, a Gradient Boosting Classifier is used to build the model

### Model Evaluation
After training the model, it is evaluated using various metrics:

-Accuracy: Percentage of correctly predicted labels<br>
-Precision: Proportion of true positives among predicted positives<br>
-Recall: Proportion of true positives among actual positives<br>
-F1-score: Harmonic mean of precision and recall<br>
-Confusion matrix: Tabular representation of predicted vs. actual labels<br>
-Mean Absolute Error: Average absolute difference between predicted and actual labels<br>
-Mean Absolute Percentage Error: Average percentage difference between predicted and actual labels<br>
-Loss: Logarithmic loss calculated using predicted probabilities<br>
-Building a Predictive System<br>

The trained model can be used to predict the quality of wine based on new input data. The input data should be preprocessed and scaled before making predictions. The model predicts whether the wine is of good or bad quality.

### Conclusion
This project demonstrates the process of wine quality prediction using machine learning techniques. By analyzing the dataset and building a predictive model, it is possible to estimate the quality of red wine based on its attributes.
