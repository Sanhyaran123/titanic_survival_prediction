# titanic_survival_prediction
Predict Titanic survival using python ,EDA &amp;ML.


# Titanic Survival Prediction 🚢

This project predicts whether a passenger survived the Titanic disaster using Python, exploratory data analysis (EDA), and machine learning.

## Dataset
We use the [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data), which contains data about passengers, including:
- Age
- Sex
- Passenger class
- Fare
- Cabin (many missing values)
- Embarked (port of boarding)

## Project Steps
1. **Data Loading**: Load CSV files into a Pandas DataFrame.  
2. **Exploratory Data Analysis (EDA)**: Analyze survival rates by gender, passenger class, age, and fare.  
3. **Data Cleaning**: Handle missing values and drop irrelevant columns.  
4. **Feature Engineering**: Encode categorical variables such as Sex and Embarked.  
5. **Model Building**: Train a Logistic Regression classifier to predict survival.  
6. **Evaluation**: Evaluate the model using accuracy and confusion matrix.

## Tools and Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## Insights from EDA
- **Gender:** Females had higher survival rates than males.  
- **Passenger Class:** 1st class passengers had higher survival rates.  
- **Age:** Younger passengers had higher survival probability.  
- **Fare:** Higher fare passengers had higher survival probability.

## Model Results
- Logistic Regression Accuracy: ~80%  
- Confusion matrix shows the model predicts survivors and non-survivors effectively.

## How to Run
1. Clone this repository:  
git clone https://github.com/Sandhyaran123/titanic-survival-prediction.git

markdown
Copy code
2. Navigate to the project folder.  
3. Install required libraries:  
pip install -r requirements.txt

markdown
Copy code
4. Open Jupyter Notebook and run `Titanic.ipynb`.

## Project Structure
titanic-survival-prediction/
├── titanic/ # CSV files
├── notebooks/ # Jupyter notebooks
├── results/ # plots and model outputs
├── README.md # this file
└── requirements.txt # Python libraries
