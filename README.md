# Insurance Cost Prediction 🏥💰

## 📝 Description 
This project focuses on predicting the insurance cost for individuals based on various features such as age, gender, BMI, number of children, smoking status, and region.

## 📊 Dataset 
The dataset used for this project is stored in the file "insurance.csv."

## 🎯 Approach 
1. Data Loading and Exploration:
   - Displaying the top 5 rows of the dataset.
   - Checking for null values and data types.
   - Converting string columns ('sex', 'smoker', 'region') to numerical values.
   - Splitting the dataset into features (X) and target (y).

2. Model Training:
   - Importing four regression models: Linear Regression, Support Vector Regression (SVR), Random Forest Regressor, and Gradient Boosting Regressor.
   - Training the models on the training set.

3. Model Evaluation:
   - Predicting insurance costs on the test set using each model.
   - Comparing model performance visually and using R-squared and Mean Absolute Error (MAE).

4. Predicting Insurance Cost for New Customer:
   - Providing a GUI application to input new customer details (age, sex, BMI, children, smoker, region).
   - Using the Gradient Boosting Regressor model to predict the insurance cost for the new customer.

## 📥 Installations 
To run the code, you need to install the required Python libraries. Use the following command to install the dependencies:

```
pip install pandas scikit-learn joblib
```

## ⚙️ Setup 
1. Clone the repository.
2. Ensure you have the "insurance.csv" file in the project directory.

## 🛠️ Requirements 
- Python 3.x
- Pandas
- Scikit-learn
- Joblib

## 🚀 Technology Used 
- Python
- Machine Learning
- Data Preprocessing
- Linear Regression
- Support Vector Regression
- Random Forest Regressor
- Gradient Boosting Regressor

## ▶️ Run 
1. Execute the "code-Notebook" script to preprocess the data, train the models, and evaluate the model performance.
2. Execute the "gui application inside code notebook" script to run the GUI application for predicting insurance cost for a new customer.
3. Enter the new customer's details (age, sex, BMI, children, smoker, region).
4. Click the "Predict" button to see the estimated insurance cost.

---

📝 I frequently create content focused on complete projects in the realm of data science using Python and R.

💬 Feel free to inquire about data science, computer vision, Python, and R.

---

<p align="Right">(◕‿◕) Thank you for exploring my GitHub project repository. 👋</p>
