# Estimation-of-Obesity-Levels-Based-on-Eating-Habits-and-Physical-Conditions
Estimation of Obesity Levels Based on Eating Habits and Physical Conditions

Project Overview
At HubbleMind Labs, I worked on a data science project aimed at analysing and predicting obesity levels based on individuals’ eating habits and physical conditions. This project combined machine learning, statistical analysis and data visualisation to create actionable insights into health and wellness trends. It provided me with a hands-on opportunity to manage a data-driven workflow from preprocessing to model evaluation while tackling real-world challenges.

Step 1: Understanding the Dataset
The dataset consisted of a variety of features, including:
Demographic data (e.g. age, gender)
Physical attributes (e.g. height, weight)
Eating habits (e.g. consumption of fast food, frequency of meals)
Physical activity levels (e.g. exercise habits, walking distance)
The target variable was the categorical obesity level, categorised into different classes such as normal, overweight or obese. The goal was to predict an individual's obesity level based on the provided features.

Step 2: Data Preprocessing
Before building machine learning models, I focused on ensuring the dataset was clean and ready for analysis:
Handling Missing Data: Checked for and handled missing or null values using imputation techniques.
Feature Scaling: Used MinMaxScaler to normalise numerical features like weight and height, ensuring they were on the same scale.
Encoding Categorical Variables: Applied LabelEncoder for binary categorical variables and OneHotEncoder for multi-class categorical variables, enabling them to work with machine learning algorithms.
Outlier Detection and Removal: Identified and removed any extreme outliers to improve model robustness.

Step 3: Exploratory Data Analysis (EDA)
EDA was critical in identifying patterns and relationships within the dataset:
Created pairplots to explore relationships between key variables (e.g. weight and physical activity).
Visualised correlations using heatmaps, which highlighted strong relationships between weight, exercise frequency and obesity levels.
Used Kernel Density Estimation (KDE) and distribution plots to understand how specific variables were distributed across different obesity categories.
These analyses provided valuable insights into how specific eating and physical activity habits influenced obesity levels.

Step 4: Feature Importance Analysis
To determine the most impactful features:
I trained a preliminary Random Forest Classifier to calculate feature importance scores.
Plotted a feature importance chart, which revealed weight and physical activity levels as the most influential features for predicting obesity.
This step helped refine the feature selection process, allowing the model to focus on the most relevant predictors.

Step 5: Model Development
Several machine learning models were developed and evaluated:
Logistic Regression: As a baseline model, it provided decent accuracy but struggled with complex non-linear relationships.
Random Forest Classifier: Outperformed Logistic Regression, offering better accuracy and handling of feature interactions effectively.
Model Tuning:
Performed grid search cross-validation to optimise hyperparameters (e.g. number of estimators, max depth).
Tuned the models to achieve the best balance between bias and variance.

Step 6: Model Evaluation
Each model was assessed using metrics like accuracy, precision, recall and F1 score. The Random Forest Classifier emerged as the top-performing model with high accuracy and well-balanced precision and recall across all classes.
To validate the model’s robustness:
I used k-fold cross-validation to ensure consistent performance across different data splits.
Analysed confusion matrices to evaluate the model’s classification performance for each obesity category.

Step 7: Insights and Recommendations
The final model provided actionable insights, such as:
Physical activity levels were the strongest predictor of obesity, emphasising the importance of regular exercise.
High consumption of fast food and skipping meals were strongly correlated with higher obesity levels.
These findings could be used to design targeted health interventions or personalised wellness plans.

Step 8: Documentation and Presentation
The entire project was meticulously documented, covering:
Data cleaning and preprocessing steps
Visualisations generated during EDA
Model development and tuning process
Final model evaluation and comparison
I presented the results to the HubbleMind team, showcasing the insights and how the model could be applied to predict obesity levels and design preventative measures.

Challenges Faced
Class Imbalance: Some obesity categories were underrepresented, requiring techniques like oversampling (SMOTE) to balance the dataset.
Feature Selection: Ensuring that only relevant features were included to prevent overfitting.
Hyperparameter Tuning: Finding the optimal hyperparameters for complex models like Random Forests required significant time and computational resources.

Outcome
The project was a resounding success, resulting in:
A highly accurate Random Forest Classifier capable of predicting obesity levels with precision
Actionable insights into the factors influencing obesity, which could be applied in health and wellness strategies
A strengthened understanding of the end-to-end data science workflow from data preprocessing to model deployment
This project demonstrated my ability to handle complex datasets, apply machine learning techniques and extract meaningful insights to solve real-world challenges. It also enhanced my technical expertise, problem-solving skills and communication abilities, preparing me for future data science roles.
