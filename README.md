# TASK-6-ELEVATE-LABS-INTERNSHIC
# 🌸 Iris Flower Classification using K-Nearest Neighbors (KNN)

## 📌 Objective

This project demonstrates the implementation of the **K-Nearest Neighbors (KNN)** algorithm for solving a classification problem using the **Iris dataset**. The main goal is to classify iris flowers into species based on sepal and petal measurements.

---

## 🧰 Tools & Libraries Used

- **Python**
- **Scikit-learn**
- **Pandas**
- **Matplotlib**
- **Seaborn**

---

## 🗄️ Dataset Overview

The **Iris dataset** is a classic machine learning dataset that includes 150 samples of iris flowers from three species:

- **Setosa**
- **Versicolor**
- **Virginica**

Each sample contains the following features:

- Sepal Length (cm)  
- Sepal Width (cm)  
- Petal Length (cm)  
- Petal Width (cm)  

---

## 🔍 Data Exploration and Visualization

### 📏 Data Shape

- **Total Samples:** 150  
- **Features:** 4  
- **Target Variable:** Species (3 classes)

### 📊 Visualizations

- **Pairplot:** Highlights relationships between all feature pairs, revealing separable clusters per species.  
- **Boxplots:** Illustrate feature distribution and help spot potential outliers for each species.

---

## 🛠️ Model Building

### 📎 Data Preprocessing

- **Normalization:** All features were normalized using standard scaling to improve KNN performance.  

### ✂️ Train-Test Split

- **Training Set:** 80% (120 samples)  
- **Testing Set:** 20% (30 samples)  
- Data split ensures stratified distribution of species for balanced evaluation.

### 🧮 KNN Classifier

- **Classifier Used:** `KNeighborsClassifier` from Scikit-learn  
- **Chosen Value of K:** 5 (based on the square root of dataset size)  
- The model classifies a new point based on the majority class among its 5 nearest neighbors.

---

## ✅ Model Evaluation

### 📈 Metrics

- **Accuracy:** Achieved **100% accuracy** on the test set.  
- **Confusion Matrix:** Displays perfect classification with no misclassified instances.  
- **Classification Report:** Provides detailed precision, recall, and F1-scores, all showing excellent performance across all classes.

---

## 🖼️ Visualization of Decision Boundaries

Using 2D projections of the feature space, decision boundaries were visualized to illustrate how the KNN classifier separates the classes.

---

## 🏁 Conclusion

The KNN model performed exceptionally well on the Iris dataset:

- Achieved **100% accuracy** on the test set.
- Clear and distinct clusters in the dataset made it ideal for KNN.
- The choice of **k=5** provided optimal classification performance.
- Visualization of decision boundaries offered insights into the classifier's behavior.

---

## 📁 How to Run

1. Clone the repository  
2. Install required libraries  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Python script or Jupyter notebook to explore and execute the full KNN classification workflow.
