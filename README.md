# 7006SCN_Manohar_P_Hiremath_16412138
This project builds a scalable PySpark-based machine learning pipeline to analyze large crime datasets, perform feature engineering, train and evaluate models (using metrics like accuracy and F1 score), and visualize insights through interactive Tableau dashboards.
#  Crime Data Analysis using PySpark & Machine Learning

##  Project Overview

This project focuses on analysing large-scale crime data using **PySpark** and applying **Machine Learning models** to predict crime-related outcomes. The dataset contains crime records including location, type of crime, arrest status, and other features.

The goal of this project is to demonstrate **big data processing, feature engineering, model training, and evaluation**, followed by **data visualisation using Tableau**.

---

##  Dataset

* Dataset: *Crimes - 2001 to Present*
* Size: Large-scale dataset (~1.9GB)
* Format: CSV
* Features include:

  * Crime Type
  * Location Description
  * Arrest Status
  * District, Ward, Community Area
  * Year, Latitude, Longitude

---

##  Technologies Used

* Python
* PySpark
* Jupyter Notebook (Anaconda)
* Machine Learning (MLlib)
* Tableau (for visualisation)

---

##  Project Workflow

### 1️ Data Loading

* Loaded dataset using PySpark
* Limited data (due to system constraints) for efficient processing

### 2️ Data Preprocessing

* Handled missing values
* Selected relevant columns
* Converted categorical data using **StringIndexer**

### 3️ Feature Engineering

* Created feature vectors using **VectorAssembler**
* Prepared dataset for machine learning models

### 4️ Model Training

Two models were implemented:

* Logistic Regression
* Decision Tree Classifier

Dataset split:

* 80% Training
* 20% Testing

---

##  Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score

The evaluation helps compare model performance and select the best model.

---

##  Tableau Dashboard

A dashboard was created using Tableau to visualise:

* Crime trends over years
* Arrest vs Non-Arrest analysis
* Crime distribution by location
* Model performance comparison

🔗 Tableau Public Link: *(Add your link here)*

---

##  Challenges Faced

* Large dataset handling (memory & disk issues)
* PySpark environment setup errors
* Kernel crashes due to storage limitations

---

##  Key Learnings

* Handling big data using PySpark
* End-to-end ML pipeline implementation
* Importance of feature engineering
* Data visualisation using Tableau

---

##  Conclusion

This project successfully demonstrates the use of **Big Data tools and Machine Learning techniques** to analyse and predict crime data patterns. The integration of **Tableau dashboards** enhances data interpretation and decision-making.

---

##  Author

**Manohar Hiremath**
MSc Data Science
Coventry University

---
