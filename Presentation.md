# Intro
Project background/goals
- Predict NBA player positions (classification) through modeling in Jupyter Notebook
- Use Tableau visuals to demonstrate the data flow, identify any trends or problems
- Have trained models for forecasting based on other datasets (NCAA statistics, e.g.)

Dataset- "NBA Player Stats since 1950" via Kaggle
- Lots of possible features (about 60 columns)
- Broad timeframe to keep or reduce
- "Position" for classifying

# Data pre-processing
- Dropped duplicate data
    - "TOT" rows added data for players on two teams during one season
    - We could either remove all the "TOT" rows or remove the rows that made up the "TOT" rows
    - easier removal was "TOT" rows
- Dropped intentionally blank columns
- Restricted data to 1982
    - Mostly complete data, mostly filled out rows with fewer null values
    - 3 point shots were introduced
    - Certain calculated statistics were not available in the first few decades
- Filled in remaining null values
- Created two separate DFs for exporting
    - Raw/flat statistics
    - Percent based statistics 

# Modeling
- Random Forest
- Decision Trees
- KNN
- Neural Network
- SVM/Grid search

# Outcomes
- Accuracy of Models
- Data flow via Tableau, results
- What our data looks like/means, what we could change/manipulate/process
- Difficulties
- Last goal/further implementation