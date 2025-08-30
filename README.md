# CODESOFT_INTERNSHIP_TASK
TASK 1
# 🚢 Task 1 – Titanic Survival Prediction

## 📌 Problem Statement
The goal of this project is to build a **machine learning model** that predicts whether a passenger on the Titanic survived or not.  
This is a classic beginner project with a well-known dataset.

The dataset typically contains information about passengers such as:
- Age
- Gender
- Ticket class (Pclass)
- Fare
- Cabin
- Number of siblings/spouses aboard
- Number of parents/children aboard
- Survival status (Target variable: `0 = Not Survived`, `1 = Survived`)

---

## ⚙️ Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn (for visualization)
- Scikit-learn (for model building)

---

## 🚀 Approach
1. **Data Exploration & Cleaning**  
   - Handle missing values (Age, Cabin, Embarked).  
   - Convert categorical features (Sex, Embarked) into numerical.  

2. **Exploratory Data Analysis (EDA)**  
   - Analyze survival rates by gender, age group, and passenger class.  
   - Visualize key insights using graphs.  

3. **Feature Engineering**  
   - Create new features (e.g., FamilySize, Title from Name).  

4. **Model Building**  
   - Train models such as Logistic Regression, Decision Tree, or Random Forest.  
   - Evaluate performance using accuracy, precision, recall, and F1-score.  

5. **Prediction**  
   - Predict survival on test dataset.  

---

## 📊 Sample Visualizations
(Add your plots or screenshots here if available)

---

## 📸 Output
Example model accuracy: **~80%** (depends on preprocessing and model choice).

---

## 🏆 Conclusion
This project demonstrates how to handle a real-world dataset with missing values, categorical variables, and perform predictive modeling using machine learning.

---

# 🎥 Task 2 – Movie Rating Prediction with Python

## 📌 Problem Statement
The goal of this project is to build a **machine learning model** that predicts the rating of a movie based on its features such as:
- Genre  
- Director  
- Actors  
- Budget / Revenue (if available)  

By analyzing historical movie data, the model should estimate the ratings given by users or critics.  

This project provides insights into the factors influencing movie ratings and demonstrates the use of **data preprocessing, feature engineering, regression modeling, and evaluation techniques**.

---

## ⚙️ Tools & Libraries
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn (visualization)  
- Scikit-learn (machine learning)  

---

## 🚀 Approach
1. **Data Collection & Cleaning**  
   - Load dataset (movies with ratings).  
   - Handle missing values and categorical features (e.g., Genre, Director, Actors).  

2. **Exploratory Data Analysis (EDA)**  
   - Visualize distribution of ratings.  
   - Check correlation between features (budget, cast, genre) and rating.  

3. **Feature Engineering**  
   - Encode categorical variables (One-Hot Encoding for genre, director, actors).  
   - Create new features like number of actors, movie decade, etc.  

4. **Model Building**  
   - Train regression models (Linear Regression, Random Forest Regressor, Gradient Boosting).  
   - Evaluate with metrics such as R² score, Mean Absolute Error (MAE), Root Mean Squared Error (RMSE).  

5. **Prediction**  
   - Input movie features → predict estimated rating.  

---

## 📊 Sample Output
- Input: Genre = "Sci-Fi", Director = "Christopher Nolan", Actors = ["Leonardo DiCaprio"]  
- Predicted Rating: **8.5/10**  

---

## 🏆 Conclusion
This project shows how **regression techniques** can be applied in machine learning to predict continuous values (movie ratings).  
It provides valuable insights into the factors that affect how movies are rated by users and critics.


# 🌸 Task 3 – Iris Flower Classification

## 📌 Problem Statement
The **Iris flower dataset** consists of three species:
- Setosa  
- Versicolor  
- Virginica  

These species can be distinguished based on their **sepal and petal measurements** (length and width).  

The objective is to train a **machine learning model** that learns from these measurements and accurately classifies iris flowers into their respective species.  
This dataset is widely used as an **introductory classification problem** in machine learning.

---

## ⚙️ Tools & Libraries
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn (visualization)  
- Scikit-learn (machine learning models)  

---

## 🚀 Approach
1. **Data Exploration**  
   - Load the Iris dataset.  
   - Visualize the relationships between features (pair plots, histograms).  

2. **Data Preprocessing**  
   - Check for missing values (Iris dataset is clean).  
   - Split dataset into training and testing sets.  

3. **Model Building**  
   - Train models such as Logistic Regression, Decision Tree, KNN, and Random Forest.  
   - Compare their performance.  

4. **Evaluation**  
   - Evaluate using accuracy score, confusion matrix, and classification report.  

---

## 📊 Sample Visualizations
- Pair plot showing species separability  
- Boxplots of petal/sepal measurements by species  

---

## 📸 Output
Example results:  
- Logistic Regression Accuracy: **96%**  
- Random Forest Accuracy: **97%**  

---

## 🏆 Conclusion
The Iris Flower Classification project demonstrates how to solve a **multiclass classification problem** using simple yet effective machine learning techniques.  
It is a fundamental dataset for learning and practicing supervised classification.


# 📈 Task 4 – Sales Prediction Using Python

## 📌 Problem Statement
Sales prediction involves forecasting the **amount of a product that customers will purchase**, considering various factors such as:
- Advertising expenditure  
- Target audience segmentation  
- Advertising platform selection  

In businesses that offer products or services, the role of a Data Scientist is crucial for predicting future sales.  
By leveraging machine learning techniques, sales prediction enables companies to **optimize advertising strategies** and **maximize revenue potential**.

---

## ⚙️ Tools & Libraries
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn (data visualization)  
- Scikit-learn (machine learning models)  

---

## 🚀 Approach
1. **Data Collection & Cleaning**  
   - Load dataset (sales & advertisement spending).  
   - Handle missing values and convert categorical data if needed.  

2. **Exploratory Data Analysis (EDA)**  
   - Visualize relationships between advertising budget and sales.  
   - Identify correlations among features.  

3. **Feature Engineering**  
   - Create meaningful features (e.g., total advertising spend, ROI-related features).  

4. **Model Building**  
   - Train regression models such as Linear Regression, Random Forest Regressor, Gradient Boosting.  
   - Compare their performance.  

5. **Evaluation**  
   - Metrics: R² Score, Mean Squared Error (MSE), Mean Absolute Error (MAE).  

---

## 📊 Sample Output
- Input: TV Advertising = \$250, Radio = \$50, Newspaper = \$30  
- Predicted Sales: **22.3 units**  

---

## 🏆 Conclusion
This project demonstrates how machine learning can be applied to **forecast sales** based on advertising and other business factors.  
The insights gained from this prediction model help businesses **allocate resources efficiently** and **make data-driven marketing decisions**.

