# Titanic - Machine Learning from Disaster
- This project aims to predict the survival outcome of passengers aboard the Titanic using machine learning techniques.
- The dataset used for training and testing the models is provided in the train.csv and test.csv files.

# Dataset
- The dataset consists of the following columns:

  - PassengerId: Unique identifier for each passenger
  - Survived: Survival status (0 = No, 1 = Yes)
  - Pclass: Ticket class (1 = 1st class, 2 = 2nd class, 3 = 3rd class)
  - Sex: Gender of the passenger
  - Age: Age of the passenger
  - SibSp: Number of siblings/spouses aboard
  - Parch: Number of parents/children aboard
  - Fare: Passenger fare
  - Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

# Project Steps

1. Data Preprocessing:

  - Read the train.csv file using pandas.
  - Remove unwanted columns (Name, Ticket, Cabin) from the dataset.
  - Interpolate missing values in the Age column.
  - Convert categorical variables (Sex, Embarked) into numerical representation.
  - Perform one-hot encoding for the Embarked column.
  - Drop the original Embarked column.
  
2. Exploratory Data Analysis:

  - Visualize the relationship between age and survival using a scatter plot.
  - Visualize the distribution of passenger classes using a bar graph.
  - Visualize the distribution of survival outcomes using a histogram.

3. Model Training:

  - Split the dataset into training and testing sets.
  - Train different machine learning models:
    - Decision Tree Classifier
    - Random Forest Classifier
    - Linear Regression
    - Support Vector Machine (SVM)
    - Logistic Regression

4. Model Evaluation:
  - Calculate the cross-validation score for each model to assess their performance.

5. Predicting on Test Data:

  - Read the test.csv file using pandas.
  - Preprocess the test dataset by removing unwanted columns and performing the same transformations as in the training data.
  - Interpolate missing values in the test dataset.
  - Make predictions using the trained model.
  - Create a submission file (sub.csv) containing the passenger IDs and predicted survival outcomes.

# Dependencies

- The following libraries were used for this project:

  - pandas
  - matplotlib
  - scikit-learn
 
# Usage

  - Clone the repository:
  - Navigate to the project directory.

    - Run the Jupyter Notebook or Python script to execute the project code.
    - The generated submission file sub.csv can be used to submit your results to the Titanic - Machine Learning from Disaster competition.



