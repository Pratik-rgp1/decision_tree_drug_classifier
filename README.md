💊 Drug Recommendation using Decision Tree Classifier:

This project builds a Decision Tree model to predict which drug a patient should take based on medical attributes like age, blood pressure, cholesterol, sex, and sodium-to-potassium ratio. It is a simple and interpretable multiclass classification problem using real-world inspired data.

📂 Project Summary
Goal: Predict the most suitable drug (Drug A, B, C, X, or Y) for a patient.

Algorithm: Decision Tree Classifier (scikit-learn)

Evaluation: Accuracy score on test set

Visualization: Decision tree plotted using plot_tree()

🧠 Features
Feature	Type	Description
Age	Numerical	Patient’s age
Sex	Categorical	Male / Female
BP	Categorical	Blood Pressure (Low / Normal / High)
Cholesterol	Categorical	Normal / High
Na_to_K	Numerical	Sodium to Potassium ratio in the blood
Drug (Target)	Categorical	Drug prescribed (A, B, C, X, Y)

🔧 Steps Performed
🧹 Data Preprocessing
Label encoded categorical variables (Sex, BP, Cholesterol)

Mapped target classes to numerical for correlation analysis

Checked for missing values

📊 Exploratory Data Analysis (EDA)
Generated correlation heatmap between features and the target

🧪 Model Building
Used DecisionTreeClassifier with entropy criterion

Controlled model complexity using max_depth

✅ Evaluation
Accuracy checked using train-test split (≈98% accuracy)

Visualized decision rules using plot_tree()

🛠️ Tools Used
Python 3.x

pandas, numpy

scikit-learn

matplotlib, seaborn
