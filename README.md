# Data Science & Analytics Interns Task1

# Task1:
# Objective:

The objective of this task is to showcase that I completed during my internship. These tasks focus on data analysis and visualization concepts using Python libraries such as Pandas, Matplotlib, Seaborn and NumPy.

# Approach:

Loaded the dataset using pandas via df=pd.read_csv('filename').

Explored the dataset structure using:
 1) shape to view dimensions
 2) columns to list features
 3) head() to fetch Initial records/rows

Created visualizations using matplotlib and seaborn:
 1) Scatter Plot to analyze relationships between features
 2) Histogram to examine data distribution
 3) Box Plot to detect outliers and value spread

# Results & Insights:

1) Helped to understand the dataset better using visualizations
2) Scatter plots shows clear relationships between SepalLength and Sepalwidth features.
3) Histogram explained the data distribution clearly.
4) Box plot helped to identify data spread and outliers.
5) Improved understanding of data analysis and visualization techniques.



# Task2:
## Objective:
The objective of this task is to predict whether a loan applicant is likely to default on a loan based on their personal, financial, and loan-related information. This helps financial institutions assess credit risk and make informed lending decisions.

## 🛠️ Approach

### 1. Data Preprocessing
  Checked dataset structure and summary statistics using `info()` and `describe()`
  Handled missing values:
    Numerical features filled using **mean**
    Categorical features filled using **mode**
  Dropped irrelevant identifier column (`Loan_ID`)
  Converted categorical variables into numerical form using **Label Encoding**

### 2. Exploratory Data Analysis (EDA)
The following visualizations were created to understand the data:
   **Loan Amount Distribution** (Histplot)
   **Education vs Income** (Box Plot)

These visualizations helped identify trends and relationships between applicant attributes and loan approval.

### 3. Model Training
Two classification models can be used:
  **Logistic Regression**
  **Decision Tree Classifier**

The dataset was split into training and testing sets using an 80/20 ratio.

### 4. Model Evaluation
The performance of the models was evaluated using:
  **Accuracy Score**
  **Confusion Matrix**

These metrics helped measure how well the models predicted loan default and approval cases.

## Results and Insights:

 1) Education level and income affect whether a loan is approved or not.
 2) Applicants who have higher income and a good credit history usually get their loans approved.
 3) The Decision Tree model is easy to understand, while Logistic Regression gives more consistent results.
 4) Cleaning missing data and converting categorical values into numbers improves the model’s accuracy.

