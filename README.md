
This project involves data analysis and prediction, focusing on a dataset related to passengers. The main steps in the project include:

1. **Data Exploration**: The CSV file is read and basic information about the dataset is inspected, including missing values and the distribution of variables like age and home planet. Visualizations such as bar plots, pie charts, and histograms are used to gain a better understanding of the data.

2. **Data Cleaning**: Missing values are imputed for variables like age, home planet, and various services (e.g., RoomService, FoodCourt). Some categorical variables are transformed using one-hot encoding.

3. **Modeling**: Various machine learning models are tested to predict the target classes, including:
   - **Random Forest**
   - **KNN (K-nearest neighbors)**
   - **Naive Bayes**
   - **SVM (Support Vector Machine)**

4. **Performance Evaluation**: The models' performance is evaluated using accuracy scores on both training and test sets. Additionally, GridSearch is used to optimize hyperparameters for the Random Forest model.

The project showcases the ability to handle missing data, perform visualizations to understand data distributions, and apply multiple algorithms to effectively classify passengers based on their characteristics.
