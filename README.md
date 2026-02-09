# Detecting Phishing Scams with Machine Learning

This Project aims to classify URLs as either phishing scams or legitimate. It uses several python libraries that are necessary for data processing, visualization, model training, and evaluation.

## Dependencies

- **pandas**: For data manipulation and analysis
- **numpy**: For numerical operations
- **matplotlib**: For plotting and data visualization
- **seaborn**: For statistical data visualization 
- **scikit-learn**: For machine learning algorithms, model evaluation, and data preprocessing
  - `train_test_split`
  - `GridSearchCV`, `RandomizedSearchCV`
  - `LogisticRegression`
  - `StandardScaler`
  - `cross_val_score`
  - `classification_report`, `confusion_matrix`, `RocCurveDisplay`
  - `DecisionTreeClassifier`
  - `RandomForestClassifier`: 
  - `SVC`

## How to Run Code

Code is intended to be run sequentially from start of notebook to the end. Many variable names are preserved throughout so running the code sequentially is important for the notebook to run smoothly. 

**Note:** Some of the machine learning algorithms take much longer to run than others, with the longest runtime being with the grid search for the SVM. This took my machine between 4 to 6 minutes to run. 