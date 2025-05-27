🧼 Titanic Exploratory Data Analysis & Cleaning
📌 About the Task
This task involved performing Exploratory Data Analysis (EDA) and data cleaning on the Titanic dataset. The objective was to understand the structure and characteristics of the data, clean and preprocess it, and generate meaningful visual insights before applying machine learning techniques.

⏳ Time Frame
✅ Completed within the scheduled internship window:
🕙 10:00 AM – 10:00 PM (Same Day)

🧠 What I Learned
How to perform EDA using Pandas, Matplotlib, Seaborn, and Plotly
Handling missing values using median and mode
Boxplot and histogram analysis for outlier detection
Feature transformation using label encoding and one-hot encoding
Scaling numeric features using StandardScaler
Calculating and visualizing correlation and feature relationships
Identifying skewness and potential multicollinearity
🛠 Tools and Libraries Used
Python 🐍
Pandas
NumPy
Matplotlib
Seaborn
Plotly (optional for interactive plots)
Scikit-learn
📁 Dataset Information
Dataset: Titanic Dataset – by Yasserh
File used: titanic.csv
Source: Kaggle
🔧 What I Did
Loaded the dataset using Pandas and explored the first few rows.
Checked for null values using isnull().sum() and visual inspection.
Filled missing values:
Replaced missing values in Age with median
Replaced missing values in Embarked with mode
Dropped columns:
Cabin due to high percentage of missing values
Name and Ticket due to low predictive value
Converted categorical values:
Used label encoding and one-hot encoding for Sex and Embarked
Detected and removed outliers in Age and Fare using boxplots and IQR method
Standardized numeric columns using StandardScaler
Created visualizations:
Histograms and boxplots for distribution and outliers
Heatmaps and pairplots for feature relationships
KDE plots and count plots for survival analysis
📊 Key Visual Insights
Higher survival rates among females and first-class passengers
Most passengers were between 20–40 years
Fare had a long right tail (positive skew)
Age and Fare showed several outliers
📸 Screenshots (Optional)
You can add screenshots of:

Heatmaps
Pairplots
Boxplots for Age and Fare
KDE plots for survival comparison by age
✅ Final Output
Cleaned and transformed dataset ready for ML modeling
Code structured and reusable
Insights documented and visualized clearly
📦 How to Run the Code
Make sure you have Python installed.
Install required libraries:
pip install pandas numpy matplotlib seaborn scikit-learn plotly

Screenshots
1

2

Exploratory-Data-Analysis-on-titanic-data-set/README.md at main · REVANTHDESABOINA/Exploratory-Data-Analysis-on-titanic-data-set 
