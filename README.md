# Data-Analytics - Supportive-Machine-Learning

Welcome to the most hands-on, intuitive, and self-contained data analytics course you’ll ever find.  
**No external datasets needed.** Every concept is illustrated with synthetic data you generate right in your notebook.  
You’ll learn not just *how* to analyze data, but *why* each method works – and when to use it.

---

## Why This Course?

- **100% self-contained** – all data is generated with Python (NumPy, pandas). No downloading, no licenses.
- **Every line of code explained** – no black boxes, no copy‑pasting without understanding.
- **Story‑driven analogies** – connect concepts to real life so you remember them.
- **Hands‑on from day one** – write code, experiment, and build intuition.
- **Covers everything** – from Python basics to advanced modeling, exactly the topics of a top-tier data analytics syllabus.
- **Free, open, and forever yours** – no subscriptions, no paywalls. Fork it, share it, improve it.

---

## Course Structure

The course is divided into **12 weeks**, each with a dedicated folder containing:
- A Jupyter notebook (`notebook.ipynb`) with step‑by‑step code, explanations, and exercises.
- An optional `solutions.ipynb` with exercise answers.
- A short `README.md` inside the week folder (if needed).

Each week follows the same friendly format:
- **Learning Objectives** – what you’ll achieve.
- **Key Concepts with Analogies** – intuitive explanations.
- **Python Code with Synthetic Data** – fully runnable.
- **Line‑by‑line Code Explanation** – never left guessing.
- **Common Pitfalls & Tips** – avoid mistakes.
- **Exercises with Solutions** – test yourself.

---

## 📖 Course Overview

| Week | Topic |
|------|-------|
| 1 | Python Fundamentals & Data Analytics Introduction |
| 2 | Probability |
| 3 | Sampling & Sampling Distributions |
| 4 | Hypothesis Testing |
| 5 | Two‑Sample Testing & ANOVA |
| 6 | Two‑Way ANOVA & Linear Regression |
| 7 | Multiple Regression & Model Building |
| 8 | Maximum Likelihood Estimation & Logistic Regression |
| 9 | ROC Curves & Regression Model Validation |
| 10 | Chi‑Square Test & Introduction to Clustering |
| 11 | Clustering Analysis (k‑means, Hierarchical) |
| 12 | Classification & Regression Trees (CART) + Final Project |

By the end of the course, you will:
- Write clean, reusable Python code for data analysis.
- Understand and apply statistical inference.
- Build predictive models (linear, logistic, decision trees).
- Evaluate and validate models.
- Perform clustering to discover patterns.
- Complete a realistic final project.

---

## Prerequisites & Installation

### Prerequisites
- Basic computer literacy (files, folders).
- No prior Python or statistics experience required – we start from scratch.

data-analytics-course/
│
├── README.md                 # This file
├── requirements.txt          # List of required libraries
│
├── week01/                   # Python fundamentals
│   └── week01.ipynb
├── week02/                   # Probability
│   └── week02.ipynb
├── week03/                   # Sampling & distributions
│   └── week03.ipynb
├── week04/                   # Hypothesis testing
│   └── week04.ipynb
├── week05/                   # Two‑sample & ANOVA
│   └── week05.ipynb
├── week06/                   # Two‑way ANOVA & linear regression
│   └── week06.ipynb
├── week07/                   # Multiple regression
│   └── week07.ipynb
├── week08/                   # MLE & logistic regression
│   └── week08.ipynb
├── week09/                   # ROC & model validation
│   └── week09.ipynb
├── week10/                   # Chi‑square & clustering intro
│   └── week10.ipynb
├── week11/                   # Clustering in depth
│   └── week11.ipynb
├── week12/                   # CART & final project
│   ├── week12.ipynb
│   └── final_project.ipynb
│
└── solutions/                # Exercise solutions (optional)
    └── ...

Week‑by‑Week Breakdown

Week 1: Python Fundamentals & Data Analytics Introduction
- What is data analytics? – the cooking analogy.
- Python basics: variables, data types, lists, dictionaries, conditionals, loops, functions.
- Generating synthetic data with numpy and pandas.
- First look at a DataFrame: filtering, grouping, basic statistics.

Week 2: Probability
- Why probability? – measuring uncertainty.
- Random variables – coin tosses, dice rolls.
- Probability distributions: binomial, Poisson, normal.
- Python simulation of random processes.

Week 3: Sampling & Sampling Distributions
- Population vs. sample – the art of generalization.
- Central Limit Theorem – the magic of averages.
- Simulating sampling distributions with exponential and uniform populations.
- Standard error and its meaning.

Week 4: Hypothesis Testing
- Null vs. alternative hypotheses – the courtroom analogy.
- Type I and Type II errors – convicting an innocent vs. freeing a guilty.
- One‑sample z‑test and t‑test.
- p‑values – what they are (and what they are not).

Week 5: Two‑Sample Testing & ANOVA
- Comparing two independent groups – pooled t‑test vs. Welch’s t‑test.
- Paired t‑test – before‑after designs.
- One‑way ANOVA – comparing three or more groups.
- Post‑hoc analysis with Tukey’s HSD.

Week 6: Two‑Way ANOVA & Linear Regression
- Two‑way ANOVA – main effects and interaction.
- Simple linear regression – the best‑fit line.
- Least squares – deriving the slope and intercept.
- Interpretation of \(R^2\).

Week 7: Multiple Regression & Model Building
- Multiple linear regression – adding more predictors.
- Adjusted \(R^2\) – the honest measure.
- Dummy variables – including categorical predictors.
- Stepwise selection and regularization (ridge, lasso).

Week 8: Maximum Likelihood Estimation & Logistic Regression
- MLE intuition – finding parameters that make data most likely.
- MLE for normal distribution – sample mean and variance.
- Logistic regression – predicting binary outcomes.
- Log‑odds and odds ratios – interpreting coefficients.

Week 9: ROC Curves & Regression Model Validation
- ROC curves – trade‑off between true positives and false positives.
- AUC – measure of discrimination.
- Cross‑validation – k‑fold, leave‑one‑out.
- Bias‑variance trade‑off – overfitting vs. underfitting.

Week 10: Chi‑Square Test & Introduction to Clustering
- Chi‑square test for independence – are two categorical variables related?
- Contingency tables – observed vs. expected frequencies.
- Introduction to clustering – unsupervised learning.
- Distance metrics – Euclidean, Manhattan.

Week 11: Clustering Analysis
- k‑means – algorithm, elbow method, silhouette score.
- Hierarchical clustering – dendrograms, linkage methods.
- Standardization – why it’s crucial.

Week 12: Classification & Regression Trees (CART) + Final Project
- Decision trees – splitting criteria (Gini, entropy, MSE).
- Pruning – avoiding overfitting.
- Random forest – bagging many trees.
- Final project – churn prediction for a telecom company.

---

🧪 Final Project: Churn Prediction

**Scenario:** A telecom company wants to reduce customer churn. You are given synthetic data of 5,000 customers with features like:
- `tenure` (months)
- `monthly_charges`
- `contract_type` (month‑to‑month, one year, two years)
- `paperless_billing`
- `total_charges`
- `churn` (target: 1 = churned, 0 = stayed)

**Tasks:**
1. Load and explore the data (visualizations, summary statistics).
2. Perform any necessary preprocessing (handle missing values, encode categorical variables).
3. Build a logistic regression model to predict churn. Interpret the odds ratios.
4. Build a decision tree classifier. Visualize the tree.
5. Compare models using cross‑validation and ROC‑AUC.
6. Identify the top three factors that influence churn.
7. Write a one‑page executive summary with actionable recommendations.

**Data generation code is provided** in `week12/final_project.ipynb`. You run it once and you have your dataset.

---

💡 How to Get the Most Out of This Course

- **Run every code cell.** Experiment by changing parameters.
- **Try the exercises** before looking at solutions.
- **Explain the concepts** to someone else – that’s the best way to solidify your understanding.
- **Take breaks** and revisit topics when you’re fresh.
- **Join the community** (if available) – ask questions, share insights.

---

This course draws from the rich tradition of open education and the wonderful Python scientific ecosystem. Special thanks to the creators of NumPy, pandas, Matplotlib, scikit‑learn, statsmodels, and SciPy.
