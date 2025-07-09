# 🎯 Customer Satisfaction Prediction Using Machine Learning

This project builds an end-to-end machine learning pipeline to analyze and predict customer satisfaction (CSAT) scores based on historical customer support interaction data. From data cleaning and exploratory analysis to model evaluation, this notebook demonstrates the power of data-driven insights in improving customer experience.

---

## 📌 Problem Statement

Customer support teams handle thousands of interactions every day. Understanding how these interactions impact customer satisfaction is critical for improving service quality and agent performance. This project uses machine learning to predict satisfaction scores based on features like issue type, agent shift, tenure, and support category.

---

## 🔍 Key Features

- 📊 **Data Cleaning & Preprocessing**  
  Handles missing values, drops sparse features, and encodes categorical variables.

- 📈 **EDA & Visualization**  
  Uncovered business insights using charts: CSAT trends across categories, agent shifts, sub-categories, and tenure.

- 🧠 **Modeling & Evaluation**  
  Built two classification models:
  - Logistic Regression
  - Random Forest (tuned)
  
  Evaluated using accuracy, precision, recall, and F1-score.

- 🎯 **Hyperparameter Tuning Ready**  
  Includes a base structure for extending with `GridSearchCV` or `RandomizedSearchCV`.

---

## 📊 Sample Insights

- Certain sub-categories like delivery or technical support correlate with lower CSAT scores.
- New agents tend to receive lower satisfaction ratings.
- Evening and late-night support shifts show different CSAT patterns.

These insights help prioritize training, resource allocation, and automation in support systems.

---

## 🚀 Tech Stack

- Python 3.x
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

## 🛠 How to Run

```bash
# Clone the repo
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

# Create virtual environment (recommended)
python -m venv venv
venv\\Scripts\\activate  # or source venv/bin/activate (Linux/Mac)

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter (or use VS Code)
jupyter notebook
