# Titanic Survival Prediction 🚢

This project predicts whether a passenger survived the Titanic disaster based on key features such as class, age, gender, number of relatives, and fare price. The model is built using **Logistic Regression** and trained on the **Titanic dataset** from Kaggle.

## 📌 Features Used for Prediction  
The model is trained using the following features:  
- **Pclass** (Ticket class: `1` = First, `2` = Second, `3` = Third)  
- **Sex** (`0` = Male, `1` = Female)  
- **Age** (Passenger’s age in years)  
- **SibSp** (Number of siblings/spouses aboard)  
- **Parch** (Number of parents/children aboard)  
- **Fare** (Ticket price)  
- **Embarked** (`0` = Southampton, `1` = Cherbourg, `2` = Queenstown)  

## 🛠️ How the Model is Trained  
1. **Data Preprocessing:**  
   - Missing values in **Age** are filled with the median.  
   - Missing values in **Embarked** are filled with the most frequent value (mode).  
   - The **Cabin** column is dropped due to too many missing values.  
   - Categorical values in **Sex** and **Embarked** are converted into numerical values.  

2. **Feature Selection:**  
   - The dataset is split into **training (80%) and testing (20%)** sets.  

3. **Model Training:**  
   - A **Logistic Regression** model is trained on the dataset.  
   - Model evaluation is performed using accuracy, confusion matrix, and classification report.  

4. **Making Predictions:**  
   - The trained model predicts survival outcomes based on user input.
  
5. **Enter passenger details when prompted (example input)**
   - 3 0 22 1 0 7.25 0

