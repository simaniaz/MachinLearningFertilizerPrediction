# 🧪 Fertilizer Prediction Using Machine Learning  
*Playground Series - Season 5, Episode 6 (Kaggle Competition)*  
Author: [Sima Niaz](https://github.com/simaniaz)

---

## 🎯 Project Overview

This project is part of an academic machine-learning exercise aimed at solving a real-world classification problem from the **Kaggle Playground Series S5E6**.

Given agricultural features such as **temperature, humidity, soil type, crop type, and nutrient levels**, the goal is to **predict the appropriate fertilizer** for a given situation.

The challenge is a **multi-class classification** problem with 7 possible fertilizer labels.

---

## 📁 Repository Structure

```bash
MachinLearningFertilizerPrediction/
│
├── data/              # Input datasets (train.csv, test.csv, sample_submission.csv)
├── notebooks/         # Main Jupyter notebook with a full pipeline
├── outputs/           # Model predictions, submission.csv
├── reports/           # Final report (DOCX/PDF)
├── models/            # (Optional) Saved model files
├── requirements.txt   # Python dependencies
└── README.md          # You're here!
🚀 Tools and Libraries Used
Python 3.9+

pandas, numpy, scikit-learn – data processing & ML models

xgboost – main classification model

matplotlib, seaborn – visualization

shap – explainability and model interpretation

🔎 ML Techniques Applied
Exploratory Data Analysis (EDA)

Label encoding & One-Hot Encoding

Feature engineering (e.g., N_to_P, P_to_K)

Model testing: SVM, SGDClassifier, XGBoost, VotingClassifier

SHAP for feature importance and interpretation

Binary vs. Multiclass strategy testing

📉 Best Result
The best model (XGBoost) achieved a validation accuracy of ~56% on binary classification (DAP vs. Urea), and ~19% on multiclass prediction (7 fertilizer types).
This submission was uploaded to Kaggle to benchmark and complete the project cycle.

📌 Future Work
Include weather and soil chemistry data

Use expert-curated domain knowledge to guide feature creation

Apply model selection techniques (Bayesian optimization, ensemble stacking)

Test with ranking models instead of forced single-label classification

🗂️ Dataset Reference
Competition: Kaggle Playground Series S5E6

🛠️ Setup & Installation
Clone this repository:

bash
Copy
Edit
git clone https://github.com/simaniaz/MachinLearningFertilizerPrediction.git
cd MachinLearningFertilizerPrediction
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook:

bash
Copy
Edit
cd notebooks
jupyter notebook Fertilizer\ Prediction.ipynb
📬 Sima Niaz
Feel free to reach out or connect with me on LinkedIn
⭐ If you found this project useful, give it a star!

