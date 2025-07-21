
# "A Classification Model for Titanic Passenger Outcomes"

  This project aims to build a machine learning classification model to predict passenger survival outcomes from the Titanic disaster using historical data. By analyzing features such as age, gender, class,parch and fare, the model identifies patterns that contributed to survival chances.
# Dataset Overview:

 There are 13 features and one target variable in dataset,involving 891 rows × 12 columns. 

# Exploratory Data Analysis (EDA):

- Histograms:
Visualized the distribution of continuous variables to understand skewness, central tendency, and spread.
- Countplots:
Examined categorical features such as Pclass, Sex, and Embarked to understand their frequency and potential relationship to survival.
- Boxplots:
Used boxplots to visually detect outliers and compare distributions across survival status.
- Scatter Plots:
Explored relationships between pairs of variables .

# feature Engineering :
Remove unwanted features. 
- Missing Values (Nulls):
Assessed missing values in critical features like Age, Cabin, and Embarked. Applied appropriate imputation strategies such as median imputation for numerical variables and mode imputation for categorical ones.
- Duplicate Records:
Identified and removed duplicate entries to ensure data consistency and prevent bias.
- Outlier Detection:
Detected outliers in numerical features (e.g., Fare, Age) using statistical methods like the IQR technique.
 This survival data is imbalance,SMOTE is used for data balancing.
# Model Building:
Divide data into training and testing used 75% data for training & 25% data for testing the model.

  I have to use Logistics regression classifier for survived or not based on features.
  
# Model Evaluation
  It 76% correctly classify  the data. 
The R2Score of model is 0.76 








