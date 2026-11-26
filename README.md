# Machine Learning – 4 Days of Hands-on Projects 🚀

A practical Machine Learning learning journey covering essential concepts, data preprocessing, exploratory data analysis, supervised learning, and unsupervised learning using Python.

This repository contains four hands-on Jupyter Notebook projects developed while learning Machine Learning fundamentals and implementing algorithms using real-world datasets.

## 📌 Projects Overview

### Day 1 – Python Data Analysis & Data Preprocessing

**Technologies:** NumPy, Pandas

- Introduction to NumPy arrays and mathematical operations.
- Calculating sum, mean, median, and standard deviation.
- Matrix operations and linear algebra.
- Loading and exploring CSV datasets using Pandas.
- Understanding dataset shape, columns, and data types.
- Statistical analysis using `describe()`.
- Identifying and handling missing values.
- Removing unnecessary columns and filling missing values using mean and mode.

**File:** `Day_1.ipynb`

### Day 2 – Medical Insurance Cost Prediction

**Algorithm:** Linear Regression  
**Technologies:** Pandas, NumPy, Matplotlib, Scikit-learn

A supervised Machine Learning project that predicts medical insurance charges based on customer information.

**Features:**
- Age
- Sex
- BMI
- Number of Children
- Smoking Status
- Region

**Target Variable:** Insurance Charges (`charges`)

**Implementation:**
- Dataset exploration and statistical analysis.
- Duplicate and missing value handling.
- Exploratory Data Analysis (EDA).
- Feature encoding using One-Hot Encoding.
- Splitting data into training and testing sets.
- Feature scaling using StandardScaler.
- Training a Linear Regression model.
- Making predictions on test data.
- Model evaluation using MAE, MSE, RMSE, and R² Score.
- Saving the trained model using Joblib.

**File:** `Day_2.ipynb`

### Day 3 – Diabetes Prediction Using Decision Tree

**Algorithm:** Decision Tree Classifier  
**Technologies:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

A supervised Machine Learning classification project that predicts whether a person has diabetes based on medical measurements.

**Features:**
- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

**Target Variable:** Outcome

**Implementation:**
- Dataset exploration and statistical analysis.
- Identifying duplicate and missing values.
- Handling invalid zero values.
- Visualizing numerical feature distributions.
- Calculating skewness.
- Handling missing values using mean and median.
- Splitting data using stratified sampling.
- Training a Decision Tree Classifier.
- Handling class imbalance using `class_weight="balanced"`.
- Evaluating the model using accuracy, classification report, and confusion matrix.
- Visualizing the trained decision tree.

**File:** `Day_3.ipynb`

### Day 4 – Iris Flower Clustering Using K-Means

**Algorithm:** K-Means Clustering  
**Technologies:** Pandas, NumPy, Matplotlib, Scikit-learn

An unsupervised Machine Learning project that groups Iris flower samples based on their measurements.

**Features:**
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

**Implementation:**
- Dataset exploration and statistical analysis.
- Checking and removing duplicate records.
- Handling missing values.
- Visualizing feature distributions.
- Feature scaling using StandardScaler.
- Finding the optimal number of clusters using the Elbow Method.
- Calculating inertia for different cluster values.
- Applying K-Means clustering.
- Assigning cluster labels to the dataset.

**Number of Clusters:** 3

**File:** `Day_4.ipynb`

---

## 🛠️ Technologies & Tools

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| NumPy | Numerical Computing |
| Pandas | Data Manipulation |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-learn | Machine Learning Algorithms |
| Jupyter Notebook | Development Environment |
| Joblib | Model Serialization |

---

## 📂 Repository Structure

```text
machine-learning-4-days/
│
├── Day_1.ipynb
├── Day_2.ipynb
├── Day_3.ipynb
├── Day_4.ipynb
│
├── train.csv
├── insurance.csv
├── diabetes.csv
├── iris.csv
│
├── model.pkl
├── requirements.txt
└── README.md
```

**Note:** All datasets are stored directly in the main project folder along with the Jupyter Notebooks.

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/irxx-sudo/Machine-Learning-4-Days-of-Hands-on-Projects.git
```

### 2. Navigate to the project directory

```bash
cd machine-learning-4-days
```

### 3. Install the required libraries

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter joblib
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebooks and execute the cells to explore the projects.

---

## 🎯 Learning Outcomes

Through these four projects, I explored and practiced:

- Python libraries used in Machine Learning.
- Data cleaning and preprocessing techniques.
- Exploratory Data Analysis (EDA).
- Handling missing values and duplicate records.
- Feature encoding and feature scaling.
- Training and testing datasets.
- Supervised Learning: Regression and Classification.
- Unsupervised Learning: Clustering.
- Linear Regression, Decision Tree, and K-Means algorithms.
- Model evaluation and visualization.

---

## 📈 Learning Journey

| Day | Topic | Learning Focus |
|---|---|---|
| 01 | Data Analysis | NumPy & Pandas |
| 02 | Regression | Linear Regression |
| 03 | Classification | Decision Tree |
| 04 | Clustering | K-Means |

---

## 👨‍💻 Author

**Mohamed Irshad Ibrahim**

Aspiring Machine Learning Engineer | AIML Student

Currently learning and building practical projects in Python, Data Science, and Machine Learning.

---

⭐ If you find this repository useful, consider giving it a star!

*Learning by building, improving one project at a time.*
