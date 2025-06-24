# 📊 Contributing to the Data Decoders Project

Welcome, to **Data Decoders** - This guide will help you contribute effectively
, ensuring our work remains high-quality, ethical, and reproducible.

---

## 🚀 Embarking on Your Contribution Journey

### 1. Setting Up Your Development Environment

Get your local environment squared away:

```bash
# First, clone the Data Decoders repository to your local machine
git clone https://github.com/MIT-Emerging-Talent/ET6-CDSP-group-18-repo.git
cd ET6-CDSP-group-18-repo

# Install the essential project dependencies
pip install -r requirements.txt

# Install development tools for linting and formatting
pip install ruff pylint
````

### 2. Core Requirements

To ensure a smooth experience, please have the following ready:

* **Python 3.10+**: Our primary language
* JupyterLab, VS Code
* Git (version control)

---

## 🔄 Contribution Workflow

### Step 1: Initiating Your Task

Before you dive into the code:

1. **Synchronize with the Latest Base:**
   Always start by pulling the freshest version of our `main` branch.

    ```bash
    git checkout main
    git pull origin main
    ```

2. **Define Your Mission:** Consult our **open issues** to pick a task, or, if
you've identified a new challenge or enhancement, create a new issue to outline
your proposed work.

3. **Create a new branch** using a clear, descriptive name:

    ```bash
    git checkout -b data-cleaning-gov-expenditure
    ```

### Step 2: Crafting Your Contribution

As you develop:

1. Follow our repository structure (see below).

2. Document decisions, assumptions, and approaches in notes/ if helpful to the team.

3. Respect naming conventions and maintain clarity for reviewers.

### Step 3: Submitting Your Impact (Pull Request)

Once your contribution is ready for review:

1. **Launch Your Branch:** Push your newly crafted branch to GitHub.

    ```bash
    git push origin your-feature-branch-name
    ```

2. **Open a Pull Request (PR):** Initiate a pull request to merge
   your work into `main`. Remember to:
   * Link the related issue
   * Add the corresponding milestone
   * Use a clear and informative PR title
   * Request a review
   * Ensure all CI checks pass before requesting a merge

---

## 💡 Elevating Quality: Our Code & Documentation Standards

Excellence in code and clarity in documentation are cornerstones of the
Data Decoders philosophy.

### Python Code Excellence

* Use clear, self-explanatory variable and function names.
* Modularize your work with reusable functions and descriptive docstrings.
* Maintain readability, split logic into steps, and add comments where needed.
* Adhere to project formatting and linting standards.

✅ **All Python code must pass:**

* **`ruff`** (for formatting and fast checks)
* **`pylint`** (for code correctness and best practices)

### Jupyter Notebook

* **Structure** notebooks using proper Markdown headers (#, ##, etc.).
* **Add** contextual explanations before or after code cells.
* **Remove** unnecessary outputs before committing.
* **Use** descriptive filenames following snake\_case
  (e.g., `eda_domestic_spending.ipynb`, `model_funding_priorities.ipynb`).

---

## 🧪 Pre-Flight Checks: Ensuring Your Code is CI/CD Ready

To make sure your changes pass our CI/CD pipeline, run:

```bash
# Format code
ruff format .

# Run style and lint checks
ruff check .
pylint **/*.py
```

*Note: Markdown formatting within your
files is automatically verified by our CI pipeline.*

---

## 🤝 Collaboration Principles

We believe in a culture of open communication, mutual respect, and constructive feedback.

### Transparent Communication

* Use GitHub Issues to discuss tasks, bugs, or ideas.
* Document crucial discussions and decisions in `notes/meeting_minutes/`.

### Constructive Code Reviews

* Offer respectful and actionable feedback.
* Focus on improving clarity, logic, and reproducibility.
* Accept alternative approaches where possible.

---

## 🔐 Data Handling & File Naming

Handling data responsibly and maintaining consistent naming are paramount to
our project's integrity.

* Do not commit restricted or sensitive data.
* Use only public or anonymized datasets, with sources cited in datasets/README.md.
* Use `snake_case` for all filenames (e.g., `expenditure_trends.csv`, `forecast_model.py`).

---

## ☑️ Your Pull Request Checklist: The Final Review

Before marking your PR as ready for review, please ensure all the
following points are checked:

* Code is well structured and documented
* Jupyter Notebook outputs have been cleaned
* PR links to an issue and includes a clear summary
* All linting and formatting checks pass (ruff, pylint)
* CI pipeline passed
  
---

## 🎯 Our Collective Mission: Beyond the Code

We're not merely writing lines of code,we are contributing to better resource
allocation, transparency, and data-driven public policy. Your contributions
matter, and together we build not only models but impact.

Thank you for being part of this mission!
