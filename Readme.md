 NovaGen Health Risk Prediction (Supervised ML Project)

 Overview

This project builds a Supervised Machine Learning model to classify individuals as Healthy or Unhealthy using biomedical and lifestyle data.

The dataset simulates real-world data from NovaGen Research Labs, aiming to:
	•	Identify high-risk individuals
	•	Improve clinical trial selection
	•	Enable population health analysis

⸻

🎯 Problem Statement

Given multiple health indicators (BMI, glucose, lifestyle habits, etc.), predict whether a person is:
	•	✅ Healthy
	•	❌ Unhealthy

This is a binary classification problem.

⸻

📂 Dataset Summary
	•	~9,800 individuals
	•	Mixed features: numerical + categorical
	•	Each record represents a unique person

🔑 Key Features
	•	Age — Age of individual
	•	BMI — Body Mass Index
	•	Blood Pressure — Systolic BP
	•	Cholesterol — Cholesterol level
	•	Glucose Level — Blood sugar level
	•	Heart Rate — Resting heart rate
	•	Sleep Hours — Daily sleep duration
	•	Exercise Hours — Daily physical activity
	•	Water Intake — Daily hydration level
	•	Stress Level — Scale (1–10)
	•	Smoking — Yes/No
	•	Alcohol — Yes/No
	•	Diet — Encoded diet type
	•	Mental Health — Mental score
	•	Physical Activity — Activity level
	•	Medical History — Past conditions
	•	Allergies — Known allergies

🎯 Target Variable
	•	Target → Health outcome (Healthy / Unhealthy)

⸻

🧠 Machine Learning Pipeline

1. Data Preprocessing
	•	Handling missing values
	•	Encoding categorical features
	•	Feature scaling

2. Exploratory Data Analysis
	•	Feature distributions
	•	Correlation analysis
	•	Outlier detection

3. Model Building

Models used:
	•	Logistic Regression
	•	Decision Tree
	•	Random Forest
	•	Support Vector Machine (SVM)

4. Evaluation Metrics
	•	Accuracy
	•	Precision
	•	Recall
	•	F1 Score
	•	Confusion Matrix

⸻

📊 Results
	•	Best Model: (Update after training)
	•	Key Insights:
	•	Lifestyle features (sleep, stress, exercise) strongly impact health
	•	Medical history and glucose levels are critical predictors

⸻

⚙️ Setup & Usage
	1.	Clone the repository
	2.	Install dependencies
	3.	Run the Jupyter notebook or training script

⸻

📁 Project Structure
	•	data → dataset files
	•	notebooks → experimentation (Jupyter Notebook)
	•	src → preprocessing, model, evaluation code
	•	README.md → project documentation

⸻

🧪 Future Improvements
	•	Hyperparameter tuning (GridSearchCV)
	•	Feature importance (SHAP / Explainability)
	•	Model deployment (FastAPI / Flask)
	•	Build a dashboard UI
	•	Real-time prediction system

⸻

💡 Real-World Applications
	•	Clinical trial selection
	•	Health risk prediction systems
	•	Insurance risk scoring
	•	Preventive healthcare analytics

⸻

🧠 Key Learnings
	•	End-to-end ML pipeline building
	•	Feature engineering importance
	•	Model comparison & trade-offs
	•	Precision vs Recall decision-making

⸻

🛠️ Tech Stack
	•	Python
	•	NumPy
	•	Pandas
	•	Scikit-learn
	•	Matplotlib / Seaborn

⭐ Support

If you find this project useful, consider giving it a ⭐ on GitHub!
