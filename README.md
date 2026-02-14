# 🏠 Linear Regression House Price Prediction

This project builds a **Linear Regression Machine Learning model** to predict house prices based on important housing features such as:

* **GrLivArea** – Ground living area (square footage)
* **BedroomAbvGr** – Number of bedrooms
* **FullBath** – Number of bathrooms

The model is trained on a housing dataset and evaluated using common regression metrics.

---

## 📌 Project Workflow

1. **Import Libraries**

   * Pandas, NumPy for data handling
   * Matplotlib for visualization
   * Scikit-learn for machine learning

2. **Load Dataset**

   * Training data is loaded from a CSV file.

3. **Feature Selection**

   * Selected relevant numerical features:

     * Living area
     * Bedrooms
     * Bathrooms

4. **Data Preprocessing**

   * Checked missing values
   * Filled missing values with column mean

5. **Train–Test Split**

   * 80% training data
   * 20% testing data

6. **Model Training**

   * Used **Linear Regression** from Scikit-learn
   * Trained on the training dataset

7. **Prediction & Evaluation**

   * Predicted house prices on test data
   * Evaluated using:

     * **Mean Squared Error (MSE)**
     * **R² Score**

8. **Feature Importance**

   * Displayed coefficients to understand how each feature affects price.

9. **New House Prediction**

   * Example prediction for a house with:

     * 2000 sq ft
     * 3 bedrooms
     * 2 bathrooms

10. **Visualization**

* Scatter plot comparing **Actual vs Predicted Prices**.

---

## 📊 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## 🚀 How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/Diya805137/SCT_ML_1.git
   ```

2. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```

3. Open the notebook:

   ```bash
   jupyter notebook Linear_Regression_Model.ipynb
   ```

4. Run all cells to train the model and view results.

---

## 📈 Output

* Model evaluation metrics (MSE and R² score)
* Predicted house price for a sample input
* Scatter plot of actual vs predicted prices

---

## 🎯 Purpose of This Project

This project is useful for:

* Beginners learning **Machine Learning Regression**
* Understanding **data preprocessing and evaluation**
* Practicing **real-world prediction problems**

---

## 📬 Author

**Diya**
Data Analyst & Machine Learning enthusiast . 

---

⭐ If you like this project, don't forget to **star the repository**!


