#  California Housing Price Prediction

## Problem Statement

The goal of this project is to predict house prices based on various features such as income, location, and housing characteristics using machine learning models.

---

## Dataset

* Source: Scikit-learn California Housing Dataset

* Number of samples: ~20,640

* Features include:

  * Median Income (MedInc)
  * House Age (HouseAge)
  * Average Rooms (AveRooms)
  * Average Bedrooms (AveBedrms)
  * Population
  * Average Occupancy (AveOccup)
  * Latitude & Longitude

* Target Variable:

  * **TargetPrice** (house price in hundreds of thousands)

---

##  Approach

### 1. Data Preparation

* Converted dataset into a Pandas DataFrame
* Checked for missing values (none found)
* Performed correlation analysis

### 2. Feature & Target Split

* Features (X): All columns except TargetPrice
* Target (y): TargetPrice

### 3. Train-Test Split

* 80% training data
* 20% testing data

---

##  Models Used

### Linear Regression

* Baseline model assuming linear relationships
* R² Score: **~0.62**

### Random Forest Regressor

* Captures non-linear relationships
* R² Score: **~0.82**

---

##  Key Insights

* Median income has the strongest influence on house prices
* Location (latitude & longitude) significantly affects pricing
* Random Forest outperforms Linear Regression, indicating non-linear patterns
* Model struggles slightly with extreme (high-value) house prices

---

##  Visualizations

* Correlation heatmap
* Feature importance plot
* Actual vs predicted price comparison

---

##  Conclusion

The project demonstrates how different machine learning models perform on housing price prediction. While Linear Regression provides a baseline, ensemble methods like Random Forest significantly improve performance.

---

##  Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib & Seaborn


---
