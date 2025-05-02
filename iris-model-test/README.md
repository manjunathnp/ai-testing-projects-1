# 🌸 AI Testing Project: Iris Model Classification

This project showcases basic AI Testing practices using a simple machine learning model (Logistic Regression) trained on the Iris dataset.

## ✅ What This Covers

- Loading the Iris dataset
- Training a Logistic Regression model
- Validating with classification report
- Exporting test artifacts
- Designed for hands-on AI testers getting started

## 📦 Project Structure

```text
iris-model-testing/
├── .gitignore              # Excludes venv, .pkl, .pyc, etc.
├── README.md               # Project overview and instructions
├── iris_model_testing.ipynb  # Jupyter notebook with model, tests, and results
├── requirements.txt        # Package list for recreating the environment
├── results/
│   ├── classification_report.csv  # Model test results (accuracy, precision, etc.)
│   └── iris_model.pkl      # Saved trained model (excluded by .gitignore)
└── venv/                   # Local virtual environment (excluded by .gitignore)
```

## 📦 About `requirements.txt`

This file lists all the Python packages used in the project, along with their exact versions.

### ✅ Why it matters

- 📌 **Reproducibility**: Anyone can recreate your Python environment reliably  
- ⚙️ **Automation-friendly**: Useful in CI/CD pipelines and virtual environments  
- 🧪 **Consistency**: Prevents "it works on my machine" issues by locking versions  
- 🤝 **Collaboration-ready**: Makes it easy for others to install everything needed

### 🚀 How to use it

After cloning the repo:

```bash
# 1. Create and activate a virtual environment (optional but recommended)
python3 -m venv venv
source venv/bin/activate

# 2. Install all required packages
pip install -r requirements.txt