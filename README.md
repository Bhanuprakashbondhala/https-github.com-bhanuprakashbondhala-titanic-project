📘 Titanic Survival Prediction – Improved Model Accuracy
📌 Project Overview

This project focuses on predicting passenger survival on the Titanic dataset.
It was developed as part of a Data Science traineeship project where the goal was to improve model accuracy through data preprocessing, feature engineering, and model comparison.

🛠️ Technologies Used

Python

Pandas, NumPy (data handling)

Matplotlib, Seaborn (visualization)

Scikit-learn (machine learning)

XGBoost (advanced modeling)

📂 Project Workflow

Data Preprocessing

Filled missing values (Age, Fare) using median

Dropped uninformative columns (PassengerId, Name, Ticket, Cabin)

Encoded categorical variables (Sex, Embarked)

Feature Engineering

Created FamilySize = SibSp + Parch + 1

Created IsAlone feature

Baseline Model

Logistic Regression (~75–78% accuracy)

Model Comparison

Random Forest (~80–85% accuracy)

XGBoost (~82–86% accuracy)

Hyperparameter Tuning

Optimized Random Forest parameters → achieved up to ~88% accuracy

📊 Visualizations

Survival by Gender

Survival by Passenger Class

Age distribution of survivors vs non-survivors

Correlation heatmap

Feature importance (Random Forest / XGBoost)

📈 Results
Model	Accuracy (approx.)
Logistic Regression	75–78%
Random Forest	80–85%
XGBoost	82–86%
Tuned Random Forest	85–88%

✅ Accuracy improved significantly from baseline Logistic Regression to tuned Random Forest/XGBoost.

📎 How to Run

Clone the repository:

git clone https://github.com/your-username/Titanic-Project.git
cd Titanic-Project


Install dependencies:

pip install -r requirements.txt


Run the Jupyter Notebook:

jupyter notebook Titanic_Project.ipynb

🙌 Author

BUNNY (Bhanu Prakash Bondhala)
📧 [mr.bunny3696@gmail.com]
💼 [https://www.linkedin.com/in/bhanu-prakash-bondhala-a4a695255/]

🚀 Future Work

Try Neural Networks on Titanic dataset

Deploy the model using Flask/Streamlit
