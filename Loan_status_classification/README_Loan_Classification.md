
# To predict loan status from using different Features.(wheather a loan will be approved or not)

  
  Predict whether a loan application will be approved or not based on applicant features using supervised machine learning techniques. This project focuses on classification modeling and includes data preprocessing, feature engineering, model building, and performance evaluation.
  we implemented and compared two supervised classification algorithms:

1️⃣ Logistic Regression
A widely used linear model that estimates the probability of loan approval based on input features. 

2️⃣ Naive Bayes Classifier
A probabilistic model based on Bayes theorem that assumes feature independence. 
- Used for: Comparing prediction performance against Logistic Regression


# Dataset Overview:

 There are 8 features and Loan_status is target variable in dataset,involving 614 rows × 9 columns. 

# Exploratory Data Analysis (EDA):

- Histograms:
Visualized the distribution of continuous variables to understand skewness, central tendency, and spread.
- Countplots:
Examined target variable balance or not.
- Boxplots:
Used boxplots to visually detect outliers and compare distributions across survival status.
- Scatter Plots:
Explored relationships between pairs of variables .
- Sweetviz : used for univariate analysis.
- Autiviz : used for bivariate analysis.

# feature Engineering : 
- Detect Missing values in data and replace numerical features with  median and categorical features with mode.
- Handling corrupted data.
- Outlier Detection:
  Detected outliers in features using statistical methods like the IQR technique.
- Data scalling : This technique transforms features to a fixed range, typically [0, 1], without distorting relative differences between values Prevents features with larger ranges (like LoanAmount) from dominating those with smaller ranges (like CreditHistory).
- label Encoding:To prepare categorical variables for machine learning algorithms, manual label encoding was applied. Each category was mapped to a unique integer value to convert textual data into numerical format without adding artificial ordering.
   categorical features such as gender,Marital Status, Education,self_employed and Property Area were similar
- Data balancing :This survival data is imbalance,SMOTE is used for data balancing.
# Model Building:
   split dataset into two parts training and testing, used 75% data for training & 25% data for testing the model.I have to use Logistic classifier & Bernoulli naive bayes classifier.
  
# Model Evaluation :
To assess the predictive performance of both Logistic Regression and Naive Bayes Classifier.
- Accuracy: Overall correctness of predictions.
- Precision: Correctness of positive predictions (Loan Approved).
- Recall (Sensitivity): Ability to identify actual approvals.
- F1-Score: Harmonic mean of precision and recall—ideal for imbalanced classes.
- Confusion Matrix: Visualization of true vs predicted labels.

  The Logistics classifier gives 75% accurasy & Bernoulli naive bayes gives 77% comparing both naive bayes classifier gives more accurasy as compared to logistic.











