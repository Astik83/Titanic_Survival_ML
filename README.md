# Titanic Survival Prediction Project 🚢

Welcome to the **Titanic Survival Prediction Project**! This repository demonstrates a machine learning workflow for predicting the survival of passengers aboard the Titanic based on various features. The project covers data cleaning, exploratory data analysis (EDA), model training, and evaluation using a custom Decision Tree algorithm.

---

## 🗂️ Project Structure

- **Section 1**: Import Necessary Libraries
- **Section 2**: Load the Titanic Dataset
- **Section 3**: Data Cleaning and Preprocessing
- **Section 4**: Correlation Analysis for Feature Selection
- **Section 5**: Prepare Train-Test Split
- **Section 6**: Implement Custom Decision Tree Classifier
- **Section 7**: Train the Decision Tree Model
- **Section 8**: Evaluate Model Metrics
- **Section 9**: Predict and Save Results

---

## 🔧 Libraries Used

- **pandas**: For data manipulation and analysis
- **numpy**: For numerical computations
- **matplotlib**: For visualization
- **seaborn**: For enhanced visualizations
- **collections.Counter**: For counting elements in an iterable

---

## 🛠️ Steps to Run the Project

1. Clone the repository:

   ```bash
  https://github.com/Astik83/Titanic_Survival_ML.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Titanic_Survival_ML
   ```

3. Ensure you have all required libraries installed:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

4. Run the Python script:

   ```bash
   python Titanic_Survival_ML
   ```

---

## 💡 Key Highlights

### 1. **Data Cleaning and Preprocessing**

- **Gender Mapping**: Converted `Sex` into numeric values (1 for male, 0 for female).
- **Missing Values**: Filled missing `Age` values with the mean.
- **One-Hot Encoding**: Encoded categorical values for `Embarked`.
- **Feature Reduction**: Dropped less correlated features like `SibSp` and `Age` based on the correlation matrix heatmap.

### 2. **Custom Decision Tree Classifier** 🌳

- A fully implemented custom Decision Tree classifier capable of:
  - Splitting data based on optimal thresholds.
  - Calculating Gini Index for split evaluation.
  - Recursively growing the tree up to a specified maximum depth.

### 3. **Performance Evaluation** 📊

- Metrics calculated on the training set:
  - **Accuracy**: 83.39%
  - **Precision**: 0.86
  - **Recall**: 0.68
  - **F1 Score**: 0.76

### 4. **Results** 📂

- Predictions for the test set are saved to `titanic_predictions.csv`.

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

- Implement advanced models like Random Forest or XGBoost.
- Include hyperparameter tuning for improved performance.
- Enhance visualizations for better interpretability.

---

## 📝 Author

**Astik Shah**

-  Passionate About Web Development, AI, & ML


Thank you for exploring the Titanic Survival Prediction Project! 🌟.

