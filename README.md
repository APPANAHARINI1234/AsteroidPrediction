#  Asteroid Collision and Impact Prediction using Machine Learning

> A machine learning-based predictive system to assess asteroid collision risks and estimate potential damage — combining space science and AI for planetary defense.

---

##  Project Overview

Asteroid impacts pose significant risks to Earth, ranging from local destruction to global catastrophes. This project presents a machine learning-based system that:

- **Classifies whether an asteroid is hazardous**
- **Predicts its diameter and potential impact severity**

By analyzing data from NASA’s Near-Earth Object (NEO) database, we apply supervised learning techniques to support disaster preparedness and planetary defense strategies.

---

##  Objectives

- Predict asteroid impact severity based on parameters like size, speed, and trajectory
- Classify asteroids into hazardous and non-hazardous
- Provide scientific insights for evacuation planning and asteroid deflection
- Aid disaster preparedness using real-time risk assessment

---

##  Machine Learning Techniques

### 1. Hazardous Classification (Binary Classification)

- **Models**:  
  - Logistic Regression  
  - Decision Tree  
  - Support Vector Machine (SVM)  
  - XGBoost Classifier (**Best Accuracy: 99.43%**)

- **Evaluation Metrics**:  
  Accuracy, Precision, Recall, F1-score, Confusion Matrix

### 2. Asteroid Diameter Prediction (Regression)

- **Models**:  
  - Ridge Regression (R² Score: **0.9837**)  
  - K-Nearest Neighbors  
  - Random Forest  
  - Gradient Boosting (for missing value handling)

---

##  Dataset Information

- **NASA NEO Dataset**  
  - 4,687 entries  
  - Features: diameter, mass, speed, trajectory, orbital elements

- **Asteroid Open Dataset**  
  - 827,646 entries  
  - Features: orbital parameters, perihelion distance, diameter

- **Sources**:  
  - [NASA NEO](https://neo.jpl.nasa.gov/)
  - [Kaggle Dataset](https://www.kaggle.com/datasets/brsdincer/asteroid-classification-for-hazardous-prediction)

---

##  Tech Stack & Tools

- **Language**: Python  
- **Libraries**: scikit-learn, pandas, NumPy, seaborn, matplotlib, XGBoost  
- **Environment**: Google Colab  


---

##  Evaluation Metrics Summary

| Task                    | Metric     | Best Model         | Result     |
|-------------------------|------------|---------------------|------------|
| Hazard Classification   | Accuracy   | XGBoost             | 99.43%     |
| Diameter Prediction     | R² Score   | Ridge Regression    | 0.9837     |

---

##  Project Workflow

1. **Data Preprocessing**  
   - Handle missing values, outliers, normalization, and encoding

2. **Exploratory Data Analysis**  
   - Heatmaps, box plots, scatter plots, PCA for dimensionality reduction

3. **Model Training & Evaluation**  
   - Used GridSearchCV & RandomizedSearchCV for hyperparameter tuning

4. **Deployment (Planned)**  
   - Real-time alert system with visualization

---

##  Future Scope

- Integration with real-time NASA APIs  
- Deep Learning (CNNs/LSTMs) for advanced predictions  
- Web-based asteroid alert systems for public & researchers  
- Geological & climate impact prediction models  
- Validation with mission data (e.g., NASA’s DART, ESA’s Hera)

---

##  References

- [Kaggle Dataset](https://www.kaggle.com/datasets/brsdincer/asteroid-classification-for-hazardous-prediction)  
- [IEEE Research Paper](https://ieeexplore.ieee.org/document/10481589)  
- [IOSR Journal](https://www.iosrjournals.org/iosr-jce/papers/Vol26-issue6/Ser-1/F2606013744.pdf)

---


