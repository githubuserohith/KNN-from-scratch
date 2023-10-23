# Customm KNN V/S Scikit-learn KNN
Built KNN from scratch using Pandas and Numpy

## 1. Data Import
- Two datasets are imported from CSV files: one for the main dataset (`CO2_Emissions.csv`) and the other for prediction (`CO2_prediction.csv`).

## 2. Data Preprocessing
- Initial data preprocessing tasks are executed, including dropping unnecessary columns and checking for missing values.

## 3. Feature Engineering
- The dataset is separated into numerical and categorical features for further processing.

## 4. Data Transformation
- Data transformation techniques are applied, including scaling numerical features using MinMaxScaler and label encoding for categorical features using LabelEncoder.

## 5. Data Concatenation
- The scaled numerical and encoded categorical features are concatenated into a single dataframe, preparing the data for modeling.

## 6. Train-Test Split
- The data is split into training and test sets to evaluate the performance of the machine learning models.

## 7. Model Implementation
- A K-Nearest Neighbors (KNN) regression model is implemented using both a custom KNN implementation and the scikit-learn KNN model.

## 8. Model Evaluation
- The models are trained and evaluated using different values of `k` (number of neighbors), and mean squared errors are calculated for both training and test data.

## 9. Performance Comparison
- The performance of the custom KNN implementation is compared with the scikit-learn KNN model by calculating the mean squared errors (MSE) for their predictions.

## 10. Conclusion
- Based on the MSE values, it is found that the custom KNN implementation has a lower MSE, indicating better performance compared to the scikit-learn KNN model.

