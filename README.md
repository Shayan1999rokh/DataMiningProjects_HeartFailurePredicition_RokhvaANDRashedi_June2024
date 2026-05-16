❤️ Heart Failure Prediction Using Multiple Machine Learning Algorithms
📌 Project Overview

This project presents a comprehensive data mining and machine learning pipeline for predicting heart failure outcomes using a structured medical dataset. The notebook explores the complete workflow of a real-world classification problem, including:

Data preprocessing
Missing value simulation and imputation
Exploratory Data Analysis (EDA)
Data visualization
Feature preparation
Model training and evaluation
Comparison of multiple machine learning algorithms
Hyperparameter tuning and cross-validation
Performance analysis using confusion matrices and accuracy metrics

The project was developed as part of a Data Mining course project by:

Ali Rashedi
Shayan Rokhva

Under the supervision of:

Dr. Khatibi
📂 Notebook Content

The notebook contains a complete end-to-end workflow for solving a medical classification problem using several supervised learning algorithms.

Main sections include:

Dataset loading and preparation
Data cleaning and preprocessing
Artificial missing value generation
Missing value imputation using KNN Imputer
Exploratory Data Analysis (EDA)
Feature scaling and normalization
Model building using different ML algorithms
Hyperparameter tuning with GridSearchCV
K-Fold Cross Validation
Performance evaluation
Confusion matrix visualization
Comparative analysis of models
🩺 Dataset Description

The project uses a Heart Failure Clinical Records Dataset, which contains clinical and medical features used to predict heart failure events.

Typical features include:

Age
Anaemia
Creatinine phosphokinase
Diabetes
Ejection fraction
High blood pressure
Platelets
Serum creatinine
Serum sodium
Sex
Smoking
Time
Death event (target variable)

The target variable is a binary classification label indicating whether a heart failure event occurred.

⚙️ Technologies & Libraries Used

The project uses Python and several popular data science and machine learning libraries.

Core Libraries
Python
NumPy
Pandas
Matplotlib
Seaborn
Machine Learning Libraries
Scikit-learn
XGBoost
Keras / TensorFlow
Important Modules Used
Preprocessing
StandardScaler
KNNImputer
Model Selection
GridSearchCV
StratifiedKFold
Train-Test Split
Evaluation Metrics
Accuracy Score
Classification Report
Confusion Matrix
🔄 Data Preprocessing Pipeline
1️⃣ Dataset Combination

The training and testing datasets are initially separated and later concatenated for comprehensive preprocessing and analysis.

2️⃣ Missing Value Analysis

The dataset originally contains no missing values.

To simulate real-world conditions and fulfill the project requirements, the notebook intentionally introduces random missing values into the dataset.

Artificial Missing Values
Approximately 5% missing values are generated randomly.
The missing values are distributed randomly to avoid introducing bias.
3️⃣ Missing Value Imputation

Missing values are handled using:

KNN Imputer

Special attention is given to categorical variables because KNN imputation may generate non-binary decimal values such as:

0.2
0.4
0.6
0.8

These values are corrected to restore proper categorical integrity.

📊 Exploratory Data Analysis (EDA)

The notebook performs extensive visualization and analysis of the dataset after preprocessing.

Visualizations include:

Feature distributions
Correlation analysis
Target class analysis
Confusion matrices
Decision tree visualization
Model comparison plots
Training vs testing performance charts

The EDA section helps understand:

Feature relationships
Dataset balance
Important variables
Model behavior
🤖 Machine Learning Models Implemented

The notebook explores and compares several machine learning algorithms.

🌳 1. Decision Tree Classifier

Features:

Hyperparameter optimization using GridSearchCV
K-Fold Cross Validation
Decision tree visualization
Max depth analysis
Confusion matrix analysis
Tuned Parameters

Examples include:

max_depth
min_samples_split
min_samples_leaf
🧠 2. Multi-Layer Perceptron (MLP)

A custom neural network architecture is implemented.

MLP Architecture

The notebook mentions a customized architecture with:

5 layers
Hidden neuron configuration:
13
13
6
6
1

Features:

Standardization
Neural network training
Accuracy analysis
Confusion matrix visualization
Train/Test charts
📈 3. Support Vector Classifier (SVC)

Features:

Standardization
Classification performance evaluation
Confusion matrix analysis
👥 4. K-Nearest Neighbors (KNN)

Features:

Standardization
Neighbor-based classification
Performance evaluation
🌲 5. Random Forest Classifier

Features:

Ensemble learning
Improved generalization
Classification performance analysis
🚀 6. XGBoost Classifier

Features:

Gradient boosting framework
High-performance classification
Advanced ensemble learning
📉 7. Logistic Regression

Features:

Baseline linear classification
Binary classification analysis
⚡ 8. AdaBoost Classifier

Features:

Adaptive boosting
Weak learner optimization
🧪 Model Evaluation

The notebook evaluates models using several standard classification metrics.

Evaluation Metrics
Accuracy
Confusion Matrix
Classification Report
Cross Validation
Confusion Matrix Analysis

Both:

Normalized confusion matrices
Non-normalized confusion matrices

are visualized and analyzed.

📉 Feature Scaling

Some models require normalization/standardization.

The project uses:

StandardScaler

Models requiring scaling:

MLP
SVC
KNN
Logistic Regression

Models not requiring scaling:

Decision Tree
Random Forest
🔍 Hyperparameter Tuning

The notebook uses:

GridSearchCV
Cross Validation

for identifying optimal parameters for several machine learning models.

This improves:

Generalization
Model robustness
Prediction performance
📁 Project Structure
.
├── Data Mining Projects_Rokhva & Rashedi_Heart Failure Dataset_Different ML algorithms.ipynb
├── README.md
└── Dataset Files
▶️ How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
2️⃣ Install Required Libraries
pip install numpy pandas matplotlib seaborn scikit-learn xgboost tensorflow keras
3️⃣ Launch Jupyter Notebook
jupyter notebook

Then open:

Data Mining Projects_Rokhva & Rashedi_Heart Failure Dataset_Different ML algorithms.ipynb
🎯 Learning Objectives of This Project

This notebook demonstrates several important concepts in:

Data Mining
Data preprocessing
Missing value handling
Feature engineering
Data visualization
Machine Learning
Classification algorithms
Model comparison
Hyperparameter tuning
Cross validation
Neural networks
Ensemble learning
Real-World Data Challenges
Artificial missing value generation
Imputation strategies
Handling categorical inconsistencies
Generalization analysis
📚 Key Concepts Covered

The project is suitable for learning and demonstrating:

Supervised learning
Medical data classification
Ensemble methods
Neural networks
Tree-based methods
Feature preprocessing
KNN imputation
Cross validation
Confusion matrix interpretation
Model evaluation techniques
🧠 Highlights of the Project

✅ Complete machine learning workflow

✅ Multiple ML algorithms in one notebook

✅ Missing value simulation and imputation

✅ Comprehensive preprocessing pipeline

✅ Advanced model evaluation

✅ Visualization-rich implementation

✅ Educational and research-oriented structure

✅ Hyperparameter tuning and cross-validation

🔬 Academic Purpose

This project was developed for educational and research purposes as part of a university-level Data Mining course.

It demonstrates practical implementation of:

Data mining methodologies
Machine learning techniques
Medical dataset analysis
Experimental evaluation
📜 License

This project is intended for:

Educational use
Research purposes
Portfolio demonstration

Feel free to fork, study, and improve the implementation.

🙌 Acknowledgements

Special thanks to:

Dr. Khatibi
Open-source Python community
Scikit-learn developers
TensorFlow / Keras developers
XGBoost contributors
📬 Contact

For questions, collaboration, or academic discussions:

Ali Rashedi
Shayan Rokhva

You can connect through GitHub or academic platforms.

⭐ If You Found This Helpful

If you found this project useful:

Star the repository ⭐
Fork the project 🍴
Share feedback 💡
Contribute improvements 🚀
