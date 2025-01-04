Here's the updated version with your GitHub link:

---

# Titanic Survival Prediction Project 🚢

Welcome to the **Titanic Survival Prediction Project**! This repository demonstrates a machine learning workflow to predict the survival of Titanic passengers based on various features. The project includes steps like data cleaning, exploratory data analysis (EDA), model training, and evaluation using a custom Decision Tree classifier.

---

## 🗂️ Project Structure

- **Section 1**: Import Libraries
- **Section 2**: Load Titanic Dataset
- **Section 3**: Data Cleaning and Preprocessing
- **Section 4**: Feature Selection via Correlation Analysis
- **Section 5**: Train-Test Split Preparation
- **Section 6**: Implement Custom Decision Tree Classifier
- **Section 7**: Train the Decision Tree Model
- **Section 8**: Model Evaluation
- **Section 9**: Make Predictions and Save Results

---

## 🔧 Libraries Used

- **pandas**: Data manipulation and analysis
- **numpy**: Numerical computations
- **matplotlib**: Data visualization
- **seaborn**: Enhanced visualization
- **collections.Counter**: Counting elements in an iterable

---

## 🛠️ Steps to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/Astik83/Titanic_Survival_ML.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Titanic_Survival_ML
   ```

3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

4. Run the Python script:

   ```bash
   python titanic_prediction.py
   ```

---

## 💡 Key Highlights

### 1. **Data Cleaning and Preprocessing**

- **Gender Mapping**: Converted `Sex` to numeric values (1 for male, 0 for female).
- **Handling Missing Values**: Filled missing `Age` values with the mean.
- **One-Hot Encoding**: Encoded categorical `Embarked` values.
- **Feature Reduction**: Dropped low-correlation features such as `SibSp` and `Age` after examining the correlation matrix heatmap.

### 2. **Custom Decision Tree Classifier** 🌳

- A fully implemented Decision Tree classifier capable of:
  - Splitting data based on the best threshold.
  - Using the Gini Index for split evaluation.
  - Recursively growing the tree up to a set maximum depth.

### 3. **Performance Evaluation** 📊

- Training set metrics:
  - **Accuracy**: 83.39%
  - **Precision**: 0.86
  - **Recall**: 0.68
  - **F1 Score**: 0.76

### 4. **Results** 📂

- Predictions for the test set are saved in `titanic_predictions.csv`.

---

### Decision Tree Predictions

- Confusion Matrix:
  ```
                 Predicted Positive   Predicted Negative
  Actual Positive     233                  109
  Actual Negative      39                  510
  ```

---

## 🚀 Future Improvements

- Explore advanced models like Random Forest or XGBoost.
- Incorporate hyperparameter tuning to optimize performance.
- Improve visualizations for better interpretability.

---

## 📝 Author

**Astik Shah**

- Passionate About Web Development, AI, & ML

Thank you for exploring the Titanic Survival Prediction Project! 🌟
