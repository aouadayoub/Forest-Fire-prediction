## **Forest Fire Prediction Project**

### **Introduction:**
This project aims to predict forest fires using machine learning models. Forest fires pose a significant threat to natural ecosystems and human lives. Early detection and prediction of forest fires can help in timely intervention and mitigation efforts.

**Dataset:**
The dataset used in this project is 'forestdata.csv'. It contains various features such as temperature, humidity, wind speed, etc., along with the target variable indicating the occurrence of a forest fire.

**Preprocessing:**
- Data cleaning: Renaming columns, handling missing values, and removing outliers.
- Feature engineering: Encoding categorical variables using one-hot encoding.
- Standardization: Standardizing numeric features to ensure uniformity in scale.

**Modeling:**
Three machine learning models were trained and evaluated for forest fire prediction:
1. **Logistic Regression:**
   - Initial model trained with default hyperparameters.
   - Hyperparameter tuning performed using GridSearchCV to optimize model performance.

2. **Decision Tree:**
   - Decision tree classifier trained initially with default settings.
   - Hyperparameter tuning conducted with GridSearchCV to find the best combination of hyperparameters.

3. **Neural Network:**
   - Multilayer Perceptron (MLP) classifier used with default settings.
   - Hyperparameters tuned using GridSearchCV to enhance model accuracy.

**Performance Evaluation:**
- Model performance assessed using accuracy score on both training and testing datasets.
- Confusion matrices generated to visualize model performance in predicting forest fires.
