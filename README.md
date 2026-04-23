# 🌸 Iris Datas
Exploratory Data Analysis (EDA)

## Overview

This project performs Exploratory Data Analysis (EDA) on the Iris dataset to identify patterns, relationships, and key features that distinguish different species. The analysis focuses on understanding data distribution, correlations, and feature importance using Python.

---

## Objectives
- Understand the structure and distribution of the dataset  
- Identify patterns and relationships between features  
- Analyse differences across species  
- Determine key features useful for classification  

---

## 🛠️ Tools & Technologies
- Python  
- Pandas 
- Numpy 
- Matplotlib  
- Seaborn  
- Jupyter Notebook 
- Visual Studio Code 

---

## 📊 Dataset
- **Name:** Iris Dataset  
- **Source:** Scikit-learn library  
- **Size:** 150 records 

---

## 🔍 Key Analysis Performed
- Data loading and cleaning  
- Summary statistics and data overview  
- Feature distribution analysis  
- Correlation analysis (heatmap)  
- Species comparison using boxplots  
- Pairwise feature relationships (pairplot)  
- Outlier detection  
- Feature variance analysis    

---

## 📈 Key Insights

- Petal length and petal width are the most significant features for distinguishing between species, showing clear variation and minimal overlap across groups.  
- Setosa is completely separable from the other species due to its consistently smaller petal measurements.  
- Versicolor and Virginica show slight overlap but can still be differentiated using petal features.  
- A strong positive correlation exists between petal length and petal width, indicating potential redundancy.  
- Sepal features show weaker separation and higher overlap, making them less reliable for classification.  
- The dataset is clean, with no significant outliers or missing values.  
- The dataset is balanced across species, reducing bias in analysis.  
- The data is suitable for classification tasks and predictive modeling.   

---
## 📊 Visualization
### 1. Data Distribution
<img width="830" height="682" alt="Histo" src="https://github.com/user-attachments/assets/8cb8f994-46c7-4f7a-9e55-5d145388b0d2" />

- The pairplot reveals clear clustering of species, especially when comparing petal length and petal width. Setosa is distinctly separable, while Versicolor and Virginica show slight overlap.

### 2. Correlation Heatmap
<img width="635" height="526" alt="correlation" src="https://github.com/user-attachments/assets/d8010e3a-d7a5-48f1-ab3f-cb572df0514a" />

- The heatmap shows a strong positive correlation between petal length and petal width, indicating that these features increase together. This highlights their importance in distinguishing species.

### 3. Species Comparison (Boxplot)
<img width="990" height="590" alt="Boxplot" src="https://github.com/user-attachments/assets/6b23428e-f6a1-4d2f-bf45-fa89b05f8ae7" />

- The boxplot demonstrates that petal length clearly separates species, with Setosa showing significantly smaller values and minimal overlap across groups. This makes it a strong feature for classification.

### 4. Pairwise Relationships (Pairplot)

<img width="1112" height="986" alt="Pairplot" src="https://github.com/user-attachments/assets/520be05b-79d8-40cf-a158-9cefefc07904" />

- The pairplot reveals clear clustering of species, especially when comparing petal length and petal width. Setosa is distinctly separable, while Versicolor and Virginica show slight overlap.
  
---
## Final Outcome

- Developed a clear understanding of data patterns, distributions, and relationships within the dataset.  
- Identified key features that influence classification through exploratory data analysis.  
- Gained practical experience in using visualizations and statistical methods to interpret data.  

---

## Interview Questions

### What is EDA?
Exploratory Data Analysis (EDA) is the process of examining and understanding a dataset using summary statistics and visualizations to identify patterns, relationships, anomalies, and insights before applying any modeling techniques.

### Why check correlation?
Correlation is used to understand the relationship between variables. It helps identify which features are strongly related, supports feature selection, and detects redundancy or multicollinearity that may affect model performance.

---
## Author
Marianne Ongondi
