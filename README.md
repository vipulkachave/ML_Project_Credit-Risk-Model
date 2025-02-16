# ML_Project_Credit-Risk-Model

### Project Overview 
A machine learning-based Credit Risk Prediction Model that identifies high-risk borrowers, improves loan approval accuracy, and minimizes default risks for NBFC.

### Project Description
Developed a Credit Risk Prediction Model to classify borrowers into low-risk and high-risk categories, enabling NBFC Finance to make informed loan approval decisions. The project involved comprehensive data cleaning, exploratory data analysis (EDA), and implementing machine learning algorithms like Logistic Regression, Random Forest, and XGBoost. The best-performing model was deployed as an interactive Streamlit app to simplify risk assessment.

Through this project, I enhanced my skills in data preprocessing, handling missing values and outliers, and conducting EDA to uncover meaningful insights. I strengthened my expertise in evaluating machine learning models using metrics like AUC-ROC, precision, and recall. Additionally, I learned the importance of aligning technical solutions with business objectives, especially in the financial domain.

### Key Steps:

**Load Data**: Initial data analysis revealed class imbalance in the default variable, which was addressed later.

**Train-Test Split**: The dataset was split before EDA to prevent data leakage.

**Data Cleaning:** 
1.Handling missing and duplicate values.
2.Detecting and addressing outliers using box plots.
3.Fixing errors in categorical columns (e.g., Loan Purpose).

**Exploratory Data Analysis (EDA):**
1.Analyzing numerical and categorical variables.
2.Understanding the distribution of borrower ages and loan amounts.
3.Investigating the impact of different features on default probability.

**Feature Engineering & Selection:**
1.Encoding categorical variables.
2.Creating new features based on financial insights.

**Model Training & Evaluation:**
Trained models: Logistic Regression, Random Forest, XGBoost.
Evaluated using AUC-ROC, precision, recall, and F1-score.

**Features**
- Data preprocessing (handling missing values, outliers, feature engineering)

- Exploratory Data Analysis (EDA) for insights

- Model training using Logistic Regression, Random Forest, and XGBoost

- Model evaluation with AUC-ROC, precision, recall, and F1-score

### Tech Stack

- Python

- Pandas, NumPy

- Scikit-learn

- Matplotlib, Seaborn

- XGBoost

### Results & Insights

- The XGBoost model achieved the highest AUC-ROC score of 0.89, making it the best choice for deployment.

- High-risk borrowers were identified with 85% precision, improving loan decision-making accuracy.

- Feature importance analysis revealed that factors like credit history, income level, and loan amount had the most significant impact on risk assessment.

