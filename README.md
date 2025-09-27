## Titanic Survival Prediction

This project explores various machine learning models to predict passenger survival on the Titanic using the famous Titanic dataset. It includes data preprocessing, feature engineering, model training, and evaluation across Decision Trees, Bagging, Random Forests, and Gradient Boosting.

⚙️ Technologies Used
- Python
- pandas
- scikit-learn
- matplotlib

📊 Models Implemented
- Decision Tree Classifier
- Bagging Classifier (with Decision Trees)
- Random Forest Classifier
- Gradient Boosting Classifie

🧹 Data Preprocessing
- Dropped irrelevant columns (Cabin)
- Encoded categorical variables (Sex, Embarked) using one-hot encoding
- Filled missing values in Age with median
- Selected relevant features for modeling

🔍 Model Evaluation
- Split data into training, development, and test sets
- Tuned max_depth for Decision Trees
- Compared model performance using accuracy scores
- Identified best hyperparameters for Random Forest via grid search
- Visualized decision trees and accuracy trends

