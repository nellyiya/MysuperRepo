# Normal Distribution, Bayesian Probability, and Gradient Descent Implementation

## Overview
This project explores three key concepts in probability and machine learning:
1. **Normal Distribution** – A fundamental probability distribution often seen in real-world data.
2. **Bayesian Probability** – A method for updating beliefs based on new evidence.
3. **Gradient Descent for Linear Regression** – An optimization technique for finding the best-fit line in regression.

Each section includes a real-world example, implementation in Python, and visualization using Matplotlib.

---

## 1️⃣ Normal Distribution Implementation
### 🎯 Objective
To analyze baby birth weights and visualize them following a normal distribution.

### 🏥 Real-World Example
- The weight of newborn babies in a hospital follows a normal distribution.

### 🛠 Implementation Steps
1. Load a dataset (`babies.csv`) containing birth weight data.
2. Compute **mean** and **standard deviation**.
3. Generate a **probability density function (PDF)**.
4. Visualize using **Matplotlib**.
5. Compare with other distributions like Poisson and Exponential.

### 📌 Key Libraries Used
- `numpy`
- `pandas`
- `matplotlib`

---

## 2️⃣ Bayesian Probability Implementation
### 🎯 Objective
To apply **Bayes' theorem** for decision-making based on new evidence.

### 🔬 Real-World Example
- **Medical Diagnosis**: Given a positive mammogram test, what is the probability a woman has breast cancer?

### 🛠 Implementation Steps
1. Define **prior probability** (e.g., base rate of breast cancer in women).
2. Define **likelihood** (test sensitivity and specificity).
3. Compute **posterior probability** using Bayes' theorem.
4. Visualize probability updates.

### 📌 Key Libraries Used
- `numpy`
- `matplotlib`

---

## 3️⃣ Gradient Descent for Linear Regression
### 🎯 Objective
To implement **Gradient Descent** for fitting a linear regression model.

### 📈 Real-World Example
- Predicting **baby weight** based on **mother’s weight** using **linear regression**.

### 🛠 Implementation Steps
1. Define **cost function** (Mean Squared Error - MSE).
2. Implement **Gradient Descent** step-by-step.
3. Use **SciPy** to optimize parameters.
4. Plot how **slope (m) and intercept (b)** change over iterations.
5. Visualize the regression line with data points.

### 📌 Key Libraries Used
- `numpy`
- `scipy.optimize`
- `matplotlib`

---

## 🚀 How to Run the Project
### 1️⃣ Install Dependencies
```bash
pip install numpy pandas matplotlib scipy
```

### 2️⃣ Run the Python Scripts
```bash
python normal_distribution.py
python bayesian_probability.py
python gradient_descent.py
```

---

## 📊 Expected Outputs
- **Normal Distribution**: A histogram of baby weights with a fitted normal curve.
- **Bayesian Probability**: Probability updates based on new evidence.
- **Gradient Descent**: A plot showing the best-fit regression line and parameter updates over iterations.

---

## 📌 Next Steps
- Extend Bayesian analysis to spam detection or disease prediction.
- Apply Gradient Descent to logistic regression for classification tasks.

---

## 📝 Contributors
- **[Your Name]** - Machine Learning Specialization at African Leadership University.

---

## 🔗 References
- Probability Distributions: [Wikipedia](https://en.wikipedia.org/wiki/Probability_distribution)
- Bayesian Probability: [Khan Academy](https://www.khanacademy.org/math/statistics-probability)
- Gradient Descent: [MIT OpenCourseWare](https://ocw.mit.edu/)

---

### 🎯 Happy Coding! 🚀

