# python-ci-cd-github-actions


# 🧪 Python CI/CD Pipeline with GitHub Actions

This is a beginner-friendly Python project that demonstrates how to set up an automated CI/CD pipeline using **GitHub Actions**. It includes:

- ✅ A simple Python function (`add`)
- ✅ Unit tests using `pytest`
- ✅ Code linting with `flake8`
- ✅ Automated GitHub Actions pipeline
- ✅ Zero local setup — 100% cloud-based

---

## 🚀 How it works

Every time you push code to the `main` branch or open a pull request, GitHub Actions:

1. Checks out your code
2. Installs dependencies
3. Lints the code with `flake8`
4. Runs tests with `pytest`

---

## 📁 Project Structure

.
├── app.py # Python function to test
├── requirements.txt # Dependencies
├── tests/
│ └── test_app.py # Unit test for the function
└── .github/
└── workflows/
└── ci.yml # GitHub Actions pipeline


---

## 🧪 Run Locally (Optional)

If you want to test locally:

```bash
# Clone the repo
git clone https://github.com/iam-Yamini/python-ci-cd-github-actions.git
cd python-ci-cd-github-actions

# Install dependencies
pip install -r requirements.txt

# Run linter
flake8 .

# Run tests
PYTHONPATH=. pytest


Requirements
Python 3.9+

pytest

flake8

