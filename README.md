# 👥 Customer Segmentation and Classification

This project aims to segment customers based on their behavior and characteristics using clustering (unsupervised learning), and then build a classification model (supervised learning) to predict a customer’s segment. The process includes complete EDA, feature engineering, clustering using KMeans, and classification using Decision Tree.

---

## 🧾 About

A comprehensive machine learning project combining unsupervised and supervised learning techniques.  
First, customers are segmented using **KMeans Clustering**, and then a **Decision Tree Classifier** is trained to predict these segments.  
This can be used by businesses for **targeted marketing, personalized services, or customer prioritization**.

---

## 📌 Objective

- Understand customer patterns through segmentation
- Label segments for future predictions
- Predict customer segments based on new data

---

## 🧠 Project Workflow

### 🔹 1. Data Understanding & EDA

- Loaded customer data and performed **data cleaning**
- Conducted detailed **exploratory data analysis**:
  - Distribution of numerical features
  - Correlation matrix
  - Boxplots for outlier detection
  - Pairplots and clustering tendency checks
- Derived insights on customer spending, frequency, and behavior

---

### 🔹 2. Feature Engineering

- Selected relevant features for clustering 
- Performed scaling using `StandardScaler`
- Addressed skewed data if needed

---

### 🔹 3. Customer Segmentation using KMeans

- Applied **KMeans Clustering** on scaled features
- Used:
  - **Elbow Method** to identify the optimal number of clusters
- Visualized clusters in 2D space using scatter plots
- Assigned cluster labels to each customer as a new feature (`Segment`)

---

### 🔹 4. Classification using Decision Tree

- Used the cluster labels as target classes
- Applied **DecisionTreeClassifier** to predict customer segments
- Split data into training and testing sets
- Evaluated model performance using accuracy and classification report


---

### 🙌 Acknowledgements
This project was completed as a hands-on practice to explore both clustering and classification workflows in a single pipeline. It helped reinforce concepts of unsupervised learning, EDA, and supervised ML model training for real-world business applications.
