Titanic Dataset – Data Cleaning & Preprocessing 

  

This project is part of an AI & ML Internship Task. The goal is to clean and preprocess the Titanic dataset for machine learning. 

  

Steps Performed: 

1. Loaded dataset from a ZIP file (`archive.zip`) 

2. Handled missing values (`Age`, `Embarked`) 

3. Dropped unnecessary column (`Cabin`) 

4. Encoded categorical columns (`Sex`, `Embarked`) 

5. Standardized numeric features (`Age`, `Fare`) 

6. Visualized and removed outliers using boxplot 

  

  

Libraries Used: 

- pandas :- Load, clean, manipulate tabular data 

- numpy :- Perform numerical operations (e.g., median) 

- seaborn :- Visualization (boxplots) 

- matplotlib :- Visualization (used with seaborn) 

- sklearn.preprocessing.StandardScaler :- Normalize/standardize features 

  

How to Run: 

1. Make sure Python is installed with all required libraries. 

2. Place `archive.zip` in the same folder. 

3. Run the script: 

     "python titanic_preprocessing.py" 

  

 

Data Preprocessing Steps: 

1. Load Data :- From archive.zip (containing train.csv) 

2. Explore Data :- View structure, data types, and missing values 

3. Handle Missing :- Fill Age with median, Embarked with mode, drop Cabin 

4. Encode Categorical :- Convert Sex and Embarked into numeric using one-hot encoding 

5. Feature Scaling :- Standardize Age and Fare to have mean 0 and std 1 

6. Outlier Detection :- Boxplot of Fare to detect extreme values 

7. Remove Outliers :- Drop rows where scaled Fare > 3 

8. Final Check :- Print cleaned data sample using df.head() 

 

9. Learnings 
 
1.Importance of handling missing values in ML 
2.Difference between one-hot encoding and label encoding 
3.How to standardize and normalize data 
4.How to use boxplots to detect outliers 

 