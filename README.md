# ALL-ML-Algorithm .

This repository is only for my learning purpose .


Haan, simple way me yaad rakho 👇

## 🔵 Supervised Learning Algorithms

Supervised learning me **target/output column hota hai**.

### Classification

Jab output **category** ho:

1. **Logistic Regression**
2. **K-Nearest Neighbors (KNN)**
3. **Decision Tree Classifier**
4. **Random Forest Classifier**
5. **Support Vector Machine (SVM)**
6. **Naive Bayes**
7. **Gradient Boosting**
8. **AdaBoost**
9. **XGBoost**
10. **LightGBM**
11. **CatBoost**

**Example:**
`Spam / Not Spam`, `Pass / Fail`, `Survived / Not Survived`

### Regression

Jab output **number** ho:

1. **Linear Regression**
2. **Multiple Linear Regression**
3. **Polynomial Regression**
4. **Decision Tree Regressor**
5. **Random Forest Regressor**
6. **Support Vector Regression (SVR)**
7. **Gradient Boosting Regressor**
8. **Random Forest Regressor**
9. **XGBoost Regressor**
10. **LightGBM Regressor**
11. **CatBoost Regressor**

**Example:**
`House Price`, `Salary`, `Sales`, `Temperature`

---

# 🟢 Unsupervised Learning Algorithms

Unsupervised learning me **target/output column nahi hota**.

### Clustering

1. **K-Means Clustering**
2. **Hierarchical Clustering**
3. **DBSCAN**
4. **Mean Shift**
5. **Gaussian Mixture Model (GMM)**

**Example:** Customer ko different groups me divide karna.

### Dimensionality Reduction

1. **PCA (Principal Component Analysis)**
2. **LDA** *(Dimensionality reduction ke context me; supervised technique hai, so strictly unsupervised nahi)*
3. **t-SNE**
4. **UMAP**
5. **Truncated SVD**

**Example:** 100 features ko reduce karke 10 important dimensions banana.

---

## 🧠 Sabse easy trick

```text
                 MACHINE LEARNING
                       |
             ┌─────────┴─────────┐
             ↓                   ↓
       SUPERVISED          UNSUPERVISED
             |                   |
       ┌─────┴─────┐       ┌─────┴─────────┐
       ↓           ↓       ↓               ↓
 Classification Regression Clustering   Dimensionality
                                          Reduction
```

**Interview ke liye sabse important:**
**Supervised:** Linear Regression, Logistic Regression, KNN, Decision Tree, Random Forest, SVM, Naive Bayes, XGBoost.

**Unsupervised:** K-Means, Hierarchical Clustering, DBSCAN, PCA.


# 🤖 Machine Learning Algorithms Guide

A simple beginner-friendly guide to understand **Supervised and Unsupervised Machine Learning algorithms**, what they do, and **when to use them**.

---

## 📌 What is Machine Learning?

Machine Learning (ML) is a way of teaching computers to learn patterns from data and make predictions or decisions without explicitly programming every rule.

Machine Learning is mainly divided into:

1. **Supervised Learning**
2. **Unsupervised Learning**

---

# 1️⃣ Supervised Learning

In **Supervised Learning**, we have:

* Input features `X`
* Target/Output `y`

The model learns the relationship between `X` and `y`.

### Example

Suppose we have:

| Hours Studied | Attendance | Result |
| ------------- | ---------- | ------ |
| 2             | 60%        | Fail   |
| 5             | 80%        | Pass   |
| 8             | 90%        | Pass   |

Here:

* `Hours Studied` and `Attendance` → Features
* `Result` → Target

Supervised Learning is mainly divided into:

* **Classification**
* **Regression**

---

# 🔵 Classification Algorithms

Classification is used when the output is a **category/class**.

### Example:

* Spam / Not Spam
* Pass / Fail
* Disease / No Disease
* Survived / Not Survived

---

## 1. Logistic Regression

Despite its name, Logistic Regression is mainly used for **classification**.

### When to use?

Use it when:

* Output has categories/classes.
* Relationship is relatively simple.
* You want a simple and interpretable model.
* You need probability-based predictions.

### Example:

Predict whether a customer will leave:

`Yes / No`

---

## 2. K-Nearest Neighbors (KNN)

KNN predicts a new data point based on the classes of its **nearest data points**.

### When to use?

Use it when:

* Dataset is small or medium-sized.
* Similar data points are likely to have similar outputs.
* You want a simple algorithm.

### Avoid when:

* Dataset is extremely large.
* Number of features is very high.

### Example:

Classifying a fruit based on:

* Weight
* Size
* Color

---

## 3. Decision Tree

A Decision Tree makes decisions using a tree-like structure of **questions/conditions**.

### When to use?

Use it when:

* You want an easy-to-understand model.
* Data contains both numerical and categorical features.
* You need to explain the model's decisions.

### Example:

Loan approval:

```text
Income > 50K?
      |
    Yes
      |
Credit Score > 700?
      |
    Yes → Approve
```

---

## 4. Random Forest

Random Forest creates **many Decision Trees** and combines their predictions.

### When to use?

Use it when:

* You want better performance than a single Decision Tree.
* Dataset has many features.
* You want a strong general-purpose model.
* Overfitting is a concern with a single tree.

### Example:

* Customer churn prediction
* Titanic survival prediction
* Fraud detection

---

## 5. Support Vector Machine (SVM)

SVM tries to find the best boundary that separates different classes.

### When to use?

Use it when:

* Dataset is small or medium-sized.
* Classes are clearly separable.
* Number of features is relatively high.

### Example:

Classifying:

`Positive Review / Negative Review`

---

## 6. Naive Bayes

Naive Bayes is a probability-based classification algorithm.

### When to use?

It works particularly well for:

* Text classification
* Spam detection
* Sentiment analysis
* Document classification

### Example:

Email:

`"Congratulations! You won a prize!"`

Prediction:

`Spam`

---

# 🟢 Regression Algorithms

Regression is used when the output is a **continuous numerical value**.

### Examples:

* House price
* Salary
* Temperature
* Sales
* Stock-related numerical predictions

---

## 1. Linear Regression

Linear Regression finds a relationship between input features and a continuous target.

### When to use?

Use it when:

* Relationship between features and target is approximately linear.
* You need a simple and interpretable model.
* You want a baseline model.

### Example:

Predict house price using:

* Area
* Number of bedrooms
* Location

---

## 2. Decision Tree Regressor

A Decision Tree can also predict continuous numerical values.

### When to use?

Use it when:

* Relationship is non-linear.
* Data has complex patterns.
* You want an easy-to-understand model.

### Example:

Predict house prices.

---

## 3. Random Forest Regressor

Random Forest Regressor combines multiple regression trees.

### When to use?

Use it when:

* Data has non-linear relationships.
* You have many features.
* You want a strong general-purpose regression model.

### Example:

Predict:

* House price
* Sales
* Customer spending

---

## 4. Support Vector Regression (SVR)

SVR is the regression version of Support Vector Machine.

### When to use?

Use it when:

* Dataset is small or medium-sized.
* You need to model non-linear relationships.
* Accuracy is important.

---

# 2️⃣ Unsupervised Learning

In **Unsupervised Learning**, we don't have a target/output column.

The model tries to discover hidden patterns or structures in the data.

### Example:

Suppose we have customer data:

* Age
* Income
* Spending

But we don't know customer groups.

The model can discover groups such as:

* High-income / high-spending customers
* Low-income customers
* Medium-spending customers

Main types include:

* **Clustering**
* **Dimensionality Reduction**

---

# 🟣 Clustering Algorithms

Clustering groups similar data points together.

---

## 1. K-Means Clustering

K-Means divides data into a specified number of clusters.

### When to use?

Use it when:

* You know approximately how many groups you want.
* Data points can be represented numerically.
* You want simple and fast clustering.

### Example:

Customer segmentation:

```text
Cluster 1 → High spending customers
Cluster 2 → Medium spending customers
Cluster 3 → Low spending customers
```

---

## 2. Hierarchical Clustering

Hierarchical Clustering creates a hierarchy of clusters.

It can be visualized using a **dendrogram**.

### When to use?

Use it when:

* You want to understand relationships between groups.
* You don't know the exact number of clusters initially.
* Dataset is relatively small.

### Example:

Grouping customers based on purchasing behavior.

---

## 3. DBSCAN

DBSCAN groups points based on **density** and can identify noise/outliers.

### When to use?

Use it when:

* Clusters have irregular shapes.
* You have noisy data.
* You want to detect outliers.
* You don't want to specify the number of clusters beforehand.

### Example:

Detecting unusual locations or abnormal transactions.

---

# 🟠 Dimensionality Reduction

Dimensionality Reduction reduces the number of features while trying to preserve important information.

It is useful when datasets contain many features.

---

## 1. PCA — Principal Component Analysis

PCA converts many features into a smaller number of important components.

### When to use?

Use PCA when:

* Dataset has many numerical features.
* You want to reduce dimensions.
* You want to visualize high-dimensional data.
* You want to reduce computational complexity.

### Example:

100 features → PCA → 10 important components

---

# 📊 Quick Algorithm Selection Guide

| Problem                      | Recommended Algorithms                                 |
| ---------------------------- | ------------------------------------------------------ |
| Binary Classification        | Logistic Regression, Decision Tree, Random Forest, SVM |
| Multi-Class Classification   | KNN, Decision Tree, Random Forest, SVM, Naive Bayes    |
| Simple Regression            | Linear Regression                                      |
| Complex Regression           | Random Forest Regressor, Decision Tree Regressor       |
| Text Classification          | Naive Bayes, Logistic Regression, SVM                  |
| Customer Segmentation        | K-Means, Hierarchical Clustering, DBSCAN               |
| Outlier Detection            | DBSCAN                                                 |
| High-Dimensional Data        | PCA                                                    |
| Need Interpretability        | Linear/Logistic Regression, Decision Tree              |
| Strong General-Purpose Model | Random Forest                                          |

---

# 🧠 Supervised vs Unsupervised

| Feature                       | Supervised                 | Unsupervised                         |
| ----------------------------- | -------------------------- | ------------------------------------ |
| Target available?             | ✅ Yes                      | ❌ No                                 |
| Main goal                     | Prediction                 | Find patterns                        |
| Main types                    | Classification, Regression | Clustering, Dimensionality Reduction |
| Example                       | House Price Prediction     | Customer Segmentation                |
| Output known during training? | Yes                        | No                                   |

---

# 🔥 Simple Decision Guide

```text
Do you have a target/output column?
            |
       ┌────┴────┐
      YES        NO
       |          |
 Supervised   Unsupervised
       |          |
   ┌───┴───┐   ┌──┴─────────────┐
   |       |   |                |
Classification Regression  Clustering   Dimensionality
                                       Reduction
```

---

# 🚀 Important Tips

Choosing an algorithm depends on:

* Dataset size
* Number of features
* Type of target
* Linear or non-linear relationship
* Presence of outliers
* Model interpretability
* Training time
* Accuracy requirements

There is **no single best algorithm for every dataset**.

A good approach is to try a few suitable algorithms and compare their performance using appropriate evaluation metrics.

---

# 📈 Common Evaluation Metrics

### Classification

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC
* Confusion Matrix

### Regression

* MAE
* MSE
* RMSE
* R² Score

### Clustering

* Silhouette Score
* Davies-Bouldin Index
* Inertia (mainly for K-Means)

---

# 🛠️ Basic Machine Learning Workflow

```text
Collect Data
     ↓
Data Cleaning
     ↓
EDA
     ↓
Feature Engineering
     ↓
Train-Test Split
     ↓
Feature Scaling / Encoding
     ↓
Choose Algorithm
     ↓
Train Model
     ↓
Make Predictions
     ↓
Evaluate Model
     ↓
Hyperparameter Tuning
     ↓
Final Model
```

---

# 🎯 Purpose of This Repository

This repository is created as a **beginner-friendly Machine Learning reference** to understand:

* Different ML algorithms
* What each algorithm does
* When to use each algorithm
* Classification vs Regression
* Supervised vs Unsupervised Learning
* Common evaluation metrics
* Basic ML workflow

---

## 👨‍💻 Author

**Kishan Kumar**

B.Tech — Artificial Intelligence & Data Science

Learning Machine Learning, Data Science and AI 🚀
