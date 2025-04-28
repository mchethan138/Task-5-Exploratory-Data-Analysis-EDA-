# Task-5-Exploratory-Data-Analysis-EDA-
1.Libraries Used:
    pandas, numpy, matplotlib.pyplot, seaborn

2.Data Loading:
    Loaded train.csv using pd.read_csv().

3.Basic EDA Operations:
    Used .info(), .isnull().sum(), .describe(), .duplicated(), .head() to explore data structure, missing values, basic statistics, and duplicates.

4.Categorical Analysis with .value_counts() and countplot():
    Sex vs Survival: Females had a higher survival rate than males.
    Gender vs Class: Most males and females were in 3rd class.
    Gender vs Embarkation: Most passengers embarked from port 'S' (Southampton).
    Survival vs Class: 1st class passengers had a higher survival rate.
    Survival vs Embarkation: Those who embarked from 'S' had higher survival.

5.Numerical Analysis:
    Age Distribution: Used histplot(), showing most passengers were aged between 20–40 years.
    Fare Distribution: Plotted Fare distribution revealing a few passengers with very high fares.

6.Relationship Analysis:
    Pairplot: Used .pairplot() to visually explore the relationships between multiple variables (Survived, Age, Fare, Pclass).


Survival was influenced by gender, class, and embarkation port.
Females, younger people, and richer (1st class) passengers had higher survival chances.
