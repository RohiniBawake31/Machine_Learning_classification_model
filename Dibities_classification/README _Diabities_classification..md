
# To Classification whether a person will have diabetes or not.

  This project applies a Decision Tree Classifier to a medical dataset to predict whether an individual is diabetic based on diagnostic measurements. The goal is to build an interpretable model and evaluate its performance using standard classification metrics.contributed to survival chances.
# Dataset Overview:

 There are 8 features and one target variable in dataset,involving 768 rows × 9 columns. 

# Exploratory Data Analysis (EDA):

- Histograms:
Visualized the distribution of continuous variables to understand skewness, central tendency, and spread.
- Countplots:
Examined target variable balance or not.
- Boxplots:
Used boxplots to visually detect outliers and compare distributions across survival status.
- Scatter Plots:
Explored relationships between pairs of variables .

# feature Engineering : 
- Handling corrupted data.
- Duplicate Records:
 Identified duplicate entries to ensure data consistency and prevent bias.
- Outlier Detection:
 Detected outliers in features using statistical methods like the IQR technique.
 This survival data is imbalance,SMOTE is used for data balancing.
# Model Building:
  Divide data into training and testing used 80% data for training & 20% data for testing the model.I have to use Decision tree classifier for patients has dibities or not based on features.
  
# Model Evaluation :
  The training accurasy of model is 72% and testing accurasy is 1%.i.e.model is overfitting.so we have done hyperparameter tuning to increase the performance of model.

# Hyperparameter tuning:
Doing bY using two ways
1) Grid search cv
2) Random search cv

After hyperparameter tuning the training accurasy of model is 74% & the testing accurasy of model is 81%.









