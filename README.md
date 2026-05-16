# ❤️ Heart Failure Prediction Using Multiple Machine Learning Algorithms

## 📌 Project Overview

This project presents a comprehensive machine learning and data mining workflow for predicting heart failure outcomes using clinical medical data. The notebook explores the implementation, evaluation, and comparison of multiple machine learning algorithms on the Heart Failure Clinical Records Dataset.

The project demonstrates a complete end-to-end pipeline including:

* Data preprocessing
* Missing value generation and imputation
* Exploratory Data Analysis (EDA)
* Data visualization
* Feature scaling
* Machine learning model development
* Hyperparameter tuning
* Cross-validation
* Performance evaluation
* Confusion matrix analysis
* Comparative analysis of classifiers

This notebook was developed as part of a university-level **Data Mining Project**.

---

# 👨‍💻 Authors

* Ali Rashedi
* Shayan Rokhva

Supervisor:

* Dr. Khatibi

---

# 📂 Project Structure

```bash
.
├── Data Mining Projects_Rokhva & Rashedi_Heart Failure Dataset_Different ML algorithms.ipynb
├── README.md
└── Dataset Files
```

---

# 🩺 Dataset Information

The project uses the **Heart Failure Clinical Records Dataset**, a medical dataset used for binary classification of heart failure events.

## Features

The dataset contains several medical and clinical attributes, including:

* Age
* Anaemia
* Creatinine phosphokinase
* Diabetes
* Ejection fraction
* High blood pressure
* Platelets
* Serum creatinine
* Serum sodium
* Sex
* Smoking
* Time

## Target Variable

* `DEATH_EVENT`

  * 0 → No death event
  * 1 → Death event occurred

---

# ⚙️ Technologies & Libraries Used

## Programming Language

* Python

## Data Processing Libraries

* NumPy
* Pandas

## Visualization Libraries

* Matplotlib
* Seaborn

## Machine Learning Libraries

* Scikit-learn
* XGBoost
* TensorFlow / Keras

---

# 🔄 Data Preprocessing

## 1️⃣ Data Loading

The dataset is loaded into Pandas DataFrames for preprocessing and analysis.

---

## 2️⃣ Missing Value Generation

The original dataset contains no missing values.

To simulate real-world medical datasets and fulfill project requirements, random missing values were intentionally introduced into the dataset.

### Characteristics

* Approximately 5% missing values
* Randomly distributed across features
* Designed to simulate incomplete clinical records

---

## 3️⃣ Missing Value Imputation

Missing values were handled using:

* **KNN Imputer**

Special attention was required for categorical features because KNN imputation can produce decimal values for binary variables.

Examples:

```python
0.2
0.4
0.6
0.8
```

These values were corrected and converted back to valid categorical representations.

---

# 📊 Exploratory Data Analysis (EDA)

The notebook includes extensive exploratory data analysis and visualization.

## Visualizations Included

* Feature distribution plots
* Correlation heatmaps
* Target class distribution
* Confusion matrices
* Decision tree visualizations
* Model comparison charts
* Training vs testing performance plots

## Objectives of EDA

* Understand feature relationships
* Detect patterns in medical variables
* Analyze class distribution
* Interpret model behavior
* Identify important predictive features

---

# 🤖 Machine Learning Models Implemented

The notebook compares multiple supervised learning algorithms.

---

## 🌳 1. Decision Tree Classifier

Implemented with:

* Hyperparameter tuning
* GridSearchCV
* Cross-validation
* Decision tree visualization

### Tuned Parameters

* `max_depth`
* `min_samples_split`
* `min_samples_leaf`

### Evaluation

* Accuracy score
* Confusion matrix
* Cross-validation results

---

## 🧠 2. Multi-Layer Perceptron (MLP)

A neural network architecture was implemented for binary classification.

### Architecture

The notebook includes a custom architecture with multiple hidden layers:

```text
13 → 13 → 6 → 6 → 1
```

### Features

* Standardization
* Neural network training
* Prediction analysis
* Accuracy visualization
* Confusion matrix evaluation

---

## 📈 3. Support Vector Classifier (SVC)

Implemented using standardized data.

### Features

* Classification analysis
* Performance evaluation
* Confusion matrix analysis

---

## 👥 4. K-Nearest Neighbors (KNN)

### Features

* Distance-based classification
* Feature scaling
* Accuracy evaluation

---

## 🌲 5. Random Forest Classifier

### Features

* Ensemble learning
* Multiple decision trees
* Improved generalization
* Performance comparison

---

## 🚀 6. XGBoost Classifier

### Features

* Gradient boosting
* High-performance ensemble learning
* Advanced classification capability

---

## 📉 7. Logistic Regression

### Features

* Linear classification baseline
* Binary prediction analysis

---

## ⚡ 8. AdaBoost Classifier

### Features

* Adaptive boosting
* Weak learner optimization
* Ensemble-based prediction

---

# 📏 Feature Scaling

Several algorithms required feature normalization and standardization.

## Scaling Technique Used

* `StandardScaler`

## Models Requiring Scaling

* MLP
* SVC
* KNN
* Logistic Regression

## Models Less Sensitive to Scaling

* Decision Tree
* Random Forest

---

# 🔍 Hyperparameter Tuning

The notebook uses:

* `GridSearchCV`
* `Cross Validation`
* `Stratified K-Fold`

to optimize model parameters and improve performance.

## Benefits

* Better generalization
* Improved robustness
* Reduced overfitting
* More reliable evaluation

---

# 🧪 Model Evaluation

Models were evaluated using multiple classification metrics.

## Evaluation Metrics

* Accuracy Score
* Confusion Matrix
* Classification Report
* Cross Validation Accuracy

---

# 📉 Confusion Matrix Analysis

Both:

* Normalized confusion matrices
* Non-normalized confusion matrices

were visualized and analyzed for model interpretation.

---

# 🎯 Learning Objectives

This project demonstrates several important concepts in:

## Data Mining

* Data preprocessing
* Missing value handling
* Data cleaning
* Feature engineering

## Machine Learning

* Classification algorithms
* Model comparison
* Ensemble methods
* Neural networks
* Hyperparameter tuning
* Cross-validation

## Medical Data Analysis

* Clinical data interpretation
* Binary classification
* Predictive analytics

---

# 🧠 Key Concepts Covered

* Supervised Learning
* Medical Classification
* Decision Trees
* Neural Networks
* Ensemble Learning
* Feature Scaling
* KNN Imputation
* Cross Validation
* Confusion Matrix Interpretation
* Model Evaluation Techniques

---

# ⭐ Project Highlights

✅ Complete end-to-end ML pipeline

✅ Multiple machine learning algorithms

✅ Missing value simulation and imputation

✅ Comprehensive preprocessing workflow

✅ Visualization-rich notebook

✅ Hyperparameter tuning

✅ Cross-validation analysis

✅ Educational and research-oriented implementation

---

# ▶️ How to Run the Project

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```

---

## 2️⃣ Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost tensorflow keras
```

---

## 3️⃣ Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```bash
Data Mining Projects_Rokhva & Rashedi_Heart Failure Dataset_Different ML algorithms.ipynb
```

---

# 📚 Academic Purpose

This project was developed for educational and research purposes as part of a university-level Data Mining course.

The notebook demonstrates practical implementation of:

* Data mining methodologies
* Machine learning workflows
* Medical dataset analysis
* Experimental evaluation

---

# 🙌 Acknowledgements

Special thanks to:

* Dr. Khatibi
* Scikit-learn developers
* TensorFlow / Keras contributors
* XGBoost contributors
* Open-source Python community

---

# 📜 License

This project is intended for:

* Educational use
* Academic research
* Portfolio demonstration

Feel free to fork, modify, and improve the implementation.

---

# 📬 Contact

For collaboration, academic discussions, or questions:

* Ali Rashedi
* Shayan Rokhva

Connect through GitHub or academic platforms.

---

# ⭐ Support

If you found this project useful:

* Star the repository ⭐
* Fork the project 🍴
* Share feedback 💡
* Contribute improvements 🚀
