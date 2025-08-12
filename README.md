# KNN Classifier – Iris Flower Classification

## 📌 Overview
This project implements a **K-Nearest Neighbors (KNN)** classifier to classify Iris flower species based on sepal and petal measurements.  
It covers data preprocessing, PCA dimensionality reduction, hyperparameter tuning with GridSearchCV, and evaluation with visualizations.

## 📊 Dataset
- **Samples:** 150  
- **Features:** Sepal length, Sepal width, Petal length, Petal width  
- **Classes:** setosa, versicolor, virginica  

## 🛠️ Installation
```bash
git clone https://github.com/yourusername/knn-iris-classifier.git
cd knn-iris-classifier
pip install -r requirements.txt


📜 Usage
Run the notebook
jupyter notebook "KNN Clf.ipynb"

Or convert to Python script:
jupyter nbconvert --to script "KNN Clf.ipynb"
python "KNN Clf.py"


📈 Workflow
1.Load dataset (iris.csv or sklearn built-in)

2.Preprocess with StandardScaler

3.Apply PCA (optional)

4.Train KNN model

5.Optimize parameters with GridSearchCV

6.Evaluate with accuracy, classification report, confusion matrix

7.Plot confusion matrix

📦 Requirements

. numpy
. pandas
. matplotlib
. seaborn
. scikit-learn
. jupyter

📂 Project Structure

 KNN Clf.ipynb       # Main notebook
 iris.csv            # Dataset (optional)
 task6_outputs/      # Plots and results
 requirements.txt    # Dependencies
 README.md           # Documentation
 

 📚 Learnings
1.  How to prepare and clean data for machine learning.

2.  Applying feature scaling and dimensionality reduction.

3.  Building and tuning a KNN model for classification tasks.

4.  Measuring model performance with key evaluation metrics.

5.  Presenting results clearly through visualizations.