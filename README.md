# NBAForecasting
### Forecasting Basketball Player Positions Using Machine Learning 🏀 🧑‍💻


# Main Contents:
    data_preprocessing.ipynb
    decision_tree_percentage.ipynb
    decision_tree_raw.ipynb
    knn_percentage.ipynb
    knn_raw.ipynb
    neural_network_percentage.ipynb
    neural_network_raw.ipynb
    svm_percentage_1982
    svm_percentage_2005
    season_stats.csv

# Tools Used:
    Python
    Pandas
    Jupyter Notebook
    Scikit-learn
    TensorFlow
    Matplotlib
    Tableau

# Project Desctiption

### [Data_Preprocessing.ipynb](https://github.com/blhawkins/NBAForecasting/blob/main/Data%20%26%20Pre-Processing/data_preprocessing.ipynb)
Components of the data_preprocessing.ipynb file include:
1. Use of Python and Pandas commands to clean the season_stats.csv dataset and remove extraneous information.
2. Segregation of features into percentage-based statistics (Assist Percentage, Total Rebound Percentage, ect.) and raw-valued statistics (Number of Assists, Number of Total Reounds ect.).
3. Percentage-based dataset saved as [percent_stats.csv](https://github.com/blhawkins/NBAForecasting/blob/main/Data%20%26%20Pre-Processing/percent_stats.csv) and raw-valued dataset saved as[raw_stats.csv](https://github.com/blhawkins/NBAForecasting/blob/main/Data%20%26%20Pre-Processing/raw_stats.csv)
### [Decision_Tree_Percentage.ipynb](https://github.com/blhawkins/NBAForecasting/blob/main/Models/decision_tree_percentage.ipynb)
Components of the decision_tree_percentage.ipynb file include:
1. Importation of the percent_stats.csv dataset.
2. Use of Sklearn's train_test_split to split the data.
3. Use of Sklearn's Decision Tree Classifier to create a decision tree model fit to the dataset.
4. Use of Sklearn's Random Forest Classifier to create a random forest model fit to the dataset.
5. Use of Random Forest functionality to print a list of feature importances.
### [Decision_Tree_Raw.ipynb](https://github.com/blhawkins/NBAForecasting/blob/main/Models/decision_tree_raw.ipynb)
Components of the decision_tree_raw.ipynb file include:
1. Importation of the raw_stats.csv dataset.
2. Use of Sklearn's train_test_split to split the data.
3. Use of Sklearn's Decision Tree Classifier to create a decision tree model fit to the dataset.
4. Use of Sklearn's Random Forest Classifier to create a random forest model fit to the dataset.
5. Use of Random Forest functionality to print a list of feature importances.
### [knn_percentage.ipynb](https://github.com/blhawkins/NBAForecasting/blob/main/Models/knn_percentage.ipynb)
Components of the knn_percentage.ipynb file include:
1. Importation of the percent_stats.csv dataset.
2. Use of Sklearn's train_test_split and StandardScaler modules to split and scale the data.
3. Use of Sklearn's KNeighbors Classifier to create a KNN model fi to the dataset
4. Use of Matplotlib to visualize the accuracy of the model as training progressed.
![alt text](https://github.com/blhawkins/NBAForecasting/blob/main/Visualizations/knn_percentage_accuracy.png 'Accuracy of KNN Percentage-Based model as training progressed')
### [knn_raw.ipynb](https://github.com/blhawkins/NBAForecasting/blob/main/Models/knn_raw.ipynb)
Components of the knn_raw.ipynb file include:
1. Importation of the raw_stats.csv dataset.
2. Use of Sklearn's train_test_split and StandardScaler modules to split and scale the data.
3. Use of Sklearn's KNeighbors Classifier to create a KNN model fi to the dataset
4. Use of Matplotlib to visualize the accuracy of the model as training progressed.
![alt text](https://github.com/blhawkins/NBAForecasting/blob/main/Visualizations/knn_raw_accuracy.png 'Accuracy of KNN Percentage-Based model as training progressed')
### [neural_network_percentage.ipynb](https://github.com/blhawkins/NBAForecasting/blob/main/Models/neural_network_percentage.ipynb)
Components of the neural_network_percentage.ipynb file include:
1. Importation of the percent_stats.csv dataset.
2. Use of Sklearn's train_test_split and StandardScaler modules to split and scale the data.
3. Use of Sklearn's Label Encoder and TensorFlow's Keras library to perform one-hot encoding on the target variable.
4. Use of TensorFlow's Keras library to create a neural network fit to the dataset.
### [neural_network_raw.ipynb](https://github.com/blhawkins/NBAForecasting/blob/main/Models/neural_network_raw.ipynb)
Components of the neural_network_raw.ipynb file include:
1. Importation of the raw_stats.csv dataset.
2. Use of Sklearn's train_test_split and StandardScaler modules to split and scale the data.
3. Use of Sklearn's Label Encoder and TensorFlow's Keras library to perform one-hot encoding on the target variable.
4. Use of TensorFlow's Keras library to create a neural network fit to the dataset.
### [svm_percentage_1982.ipynb](https://github.com/blhawkins/NBAForecasting/blob/main/Models/svm_percentage_1982.ipynb)
Components of the svm_percentage_1982.ipynb file include:
1. Importation of the percent_stats.csv dataset.
2. Selection of relevant percentage-based features.
3. Use of Sklearn's train_test_split and StandardScaler modules to split and scale the data.
4. Use of Sklearn's SVC and GridSearchCV modules to fit an SVM model to the dataset by way of the Grid Search estimator.
### [svm_percentage_2005.ipynb](https://github.com/blhawkins/NBAForecasting/blob/main/Models/svm_percentage_2005.ipynb)
Components of the svm_percentage_2005.ipynb file include:
1. Importation of the percent_stats.csv dataset.
2. Use of dataframe operations to select only data points taken beginning in the 2005 season.
3. Selection of relevant percentage-based features.
4. Use of Sklearn's train_test_split and StandardScaler modules to split and scale the data.
5. Use of Sklearn's SVC and GridSearchCV modules to fit an SVM model to the dataset by way of the Grid Search estimator.
# Tableau Visualizations
### Rise in 3PT Shooting Among Centers and Power Forwards Since 1982
![alt text](https://github.com/blhawkins/NBAForecasting/blob/main/Visualizations/3pt_shooting_centers.png 'Line Graph Showing the Rise in 3PT Shooting Among Centers and Power Forwards Since 1982')

### Rise in 3PT Shooting Among All Players Since 1982
![alt text](https://github.com/blhawkins/NBAForecasting/blob/main/Visualizations/3pt_shooting_overall.png 'Bar Chart Showing the Rise in 3PT Shooting Among All Players Since 1982')

### Overlap in Positional Roles Over Time
![alt text](https://github.com/blhawkins/NBAForecasting/blob/main/Visualizations/positions_over_time.png 'Stacked Line Chart Showing the Overlap in Positional Roles Over Time')
    

