
# 🌸 Iris Flower Classification — Machine Learning Project

A complete **end-to-end ML project** built using Python and Jupyter Notebook.
This project trains a machine learning model to classify Iris flower species based on sepal and petal measurements.

---

## 📂 Project Structure

```
├── iris_classification.ipynb     # Main notebook with full ML workflow
├── data/
│   ├── Iris.csv                  # Original dataset
│   └── iris_dataset_export.csv   # Cleaned/exported dataset
├── report.txt                    # Model performance summary
└── README.md                     # Project documentation
```



## 📘 About the Dataset

The dataset contains **150 samples** of Iris flowers with **4 features**:

| Feature      | Description           |
| ------------ | --------------------- |
| Sepal Length | Length of sepal in cm |
| Sepal Width  | Width of sepal in cm  |
| Petal Length | Length of petal in cm |
| Petal Width  | Width of petal in cm  |

**Target classes (species):**

* Iris-setosa
* Iris-versicolor
* Iris-virginica

---

## 🚀 Project Workflow

This project includes:

### ✔ 1. Data Loading & Cleaning

* Loading CSV
* Checking null values
* Descriptive statistics
* Visual exploration

### ✔ 2. Exploratory Data Analysis (EDA)

* Pairplots
* Correlation heatmap
* Feature distributions

### ✔ 3. Model Training

Tested ML models:

* Logistic Regression
* KNN
* Decision Tree
* Random Forest
* SVM (Support Vector Machine)

Best model: **SVM (highest accuracy)**

### ✔ 4. Evaluation Metrics

* Accuracy Score
* Confusion Matrix
* Classification Report
* ROC Curves (multi-class)
* Cross-validation scores
* Learning Curve

---

## 🏆 Final Results

| Model               | Accuracy |
| ------------------- | -------- |
| **SVM (Best)**      | ~97–99%  |
| Random Forest       | ~95%     |
| Logistic Regression | ~94%     |
| KNN                 | ~92%     |

> The SVM model delivered the **most stable and highest accuracy** across cross-validation.

---

## 📊 Visualizations Included

* Pairplot of features
* Confusion Matrix
* Cross-Validation Boxplot
* ROC curve (multi-class)
* Learning Curve
* Decision boundary (optional)

---

## 🤖 Saved Model

The trained best ML model is saved as:

```
best_iris_model_SVM.joblib
```

You can load it using:

```python
import joblib
model = joblib.load("best_iris_model_SVM.joblib")
model.predict([[5.1, 3.5, 1.4, 0.2]])
```

---

## 🛠️ Requirements

Install dependencies using:

```
pip install -r requirements.txt
```

Typical packages:

```
numpy
pandas
scikit-learn
matplotlib
seaborn
joblib
```

---

## ▶️ How to Run

1. Clone the repo:

```
git clone https://github.com/abusegithub/iris-ml-project.git
```

2. Open the notebook:

```
jupyter notebook iris_classification.ipynb
```

3. Run all cells.

---

## 📘 Author

**Akanksha (abusegithub)**
Machine Learning / Python Developer

---

## ⭐ Support the Project

If you found this project helpful, consider giving it a **star ⭐ on GitHub**!

