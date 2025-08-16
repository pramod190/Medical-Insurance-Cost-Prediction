# 🏥 Medical Insurance Cost Prediction using Linear Regression

This project predicts **medical insurance charges** based on patient demographic and lifestyle factors using **Linear Regression**.  
It is implemented in **Python (Jupyter Notebook)** using the dataset `insurance.csv`.

---

## 📂 Dataset
- **File:** `insurance.csv`
- **Features:**
  - `age`: Age of the person
  - `sex`: Gender (male/female)
  - `bmi`: Body Mass Index
  - `children`: Number of children
  - `smoker`: Smoking status (yes/no)
  - `region`: Residential region (northeast, northwest, southeast, southwest)
  - `charges`: Target variable – Medical insurance cost

---

## ⚙️ Workflow (as per Notebook)
1. **Importing Libraries**
   - `pandas`, `numpy` for data handling
   - `matplotlib`, `seaborn` for visualization
   - `sklearn.model_selection` for train-test split
   - `sklearn.linear_model` for Linear Regression
   - `sklearn.metrics` for model evaluation

2. **Data Preprocessing**
   - Loaded dataset `insurance.csv` into a DataFrame
   - Checked for null values and dataset information
   - Converted categorical variables (`sex`, `smoker`, `region`) into numeric using **Label Encoding / One-Hot Encoding**

3. **Exploratory Data Analysis (EDA)**
   - Visualized distributions of age, BMI, charges
   - Compared charges between smokers and non-smokers
   - Correlation heatmap between features

4. **Model Building**
   - Split data into **train (80%)** and **test (20%)**
   - Applied **Linear Regression model**
   - Trained the model on training set

5. **Model Evaluation**
   - Predictions made on the test set
   - Evaluated using:
     - R² Score
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)

---

## 📊 Results
- **Smoking** and **BMI** were found to be the most influential factors affecting charges.
- Linear Regression gave a reasonable baseline performance for predicting medical costs.

---
