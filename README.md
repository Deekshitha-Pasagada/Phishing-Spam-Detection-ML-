# Phishing-Spam-Detection-ML
Phishing detection system that extracts URL-based features and applies classical ML models (e.g., Random Forest, SVM, Naive Bayes, XGBoost) to classify sites as legitimate or phishing. The repository includes clean notebooks, a saved model artifact and a simple Flask web interface for quick demos.

# Phishing & Spam Detection using Machine Learning
This repository combines two parts:
1) **ML notebooks** for phishing URL and spam email classification (MDP-2018, UCI Phishing, UCI Spambase).
2) **Flask web app** (`app.py`) with HTML templates to demo phishing detection using a saved model (`model_phish.pkl`).

# Features
- URL-based **phishing detection** and **email spam** classification
- Multiple models: Random Forest, SVM, Naive Bayes, XGBoost
- Ready-to-run notebooks: `MDP-2018.ipynb`, `UCI-Phishing.ipynb`, `UCI-Spambase.ipynb`
- Flask app with routes and templates (`templates/`, `static/`)
- Custom **C4.5** decision tree implementation (`c45/`) for experimentation
- Documentation

# Setup
1) Clone:
   ```bash
   git clone https://github.com/Deekshitha-Pasagada/Phishing-Spam-Detection-ML-.git
   cd Phishing-Spam-Detection-ML

2) Create venv (optional but recommended):
   ```bash
   python -m venv .venv   # Windows: .venv\Scripts\activate
   source .venv/bin/activate   # macOS/Linux

3) Install dependencies:
   ```bash
   pip install -r requirements.txt

# Run notebooks
   ```bash
   jupyter notebook

# Run Flask app

