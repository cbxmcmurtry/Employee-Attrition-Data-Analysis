# **Employee Attrition Analysis & Prediction**
This project predicts employee attrition using a Random Forest Classifier trained on **HR data from IBM**. It includes data preprocessing, feature encoding, SMOTE for class balancing, and an interactive UI for making predictions. The Random Forest model was trained using a balanced dataset to ensure fair representation of both employees who stayed and those who left. Key settings, such as the number of trees and the depth of each tree, were fine-tuned using techniques like grid search and cross-validation to enhance the model’s accuracy.

## **Features**
* **Data Preprocessing:** Handles categorical and numerical variables.
* **SMOTE (Synthetic Minority Over-sampling Technique):** Balances the dataset for better predictions.
* **Random Forest Model:** Trained on resampled data for robust classification.
* **Evaluation Metrics:** Generates a classification report, confusion matrix, and feature importance plots.
* **Interactive UI:** Uses widgets to input employee details and predict attrition.

## **How It Works**
* **Prepares Data:** Encodes categorical variables and balances data using SMOTE.
* **Trains Model:** Uses a **Random Forest Classifier** on the resampled dataset.
* **Evaluates Performance:** Displays the classification report and confusion matrix.
* **User Input via Widgets:** Allows entering employee details to predict attrition.

## **User Guide**

### **1. Install Necessary Software & Libraries**
#### **Required Software:**
* **Python** (Version 3.8 or higher)
* **Jupyter Notebook**

#### **Required Libraries:**
Install the necessary Python libraries using the following command:
pip install pandas numpy scikit-learn imbalanced-learn ipywidgets matplotlib seaborn

### **2. Download the Application Files**
Download the application files from the provided link and save them locally.

### **3. Run the Application**
* **Open Jupyter Notebook** and open the command line or terminal.
* **Navigate to the project directory** using the `cd` command:
cd /path/to/EmployeeAttritionPredictor
* Launch Jupyter Notebook by running:
jupyter notebook

* In the Jupyter Notebook interface, navigate to the project directory and open the employee_attrition_prediction.ipynb file.

### 4. **Execute the Application**
* Run all code cells in sequence by clicking the “Run” button in Jupyter Notebook.
The code will:
* Load the dataset
* Preprocess the data
* Train the Random Forest Classifier
* Make predictions on employee attrition

### 5. **Use the Application Interface**
* **Interact with Widgets:** Enter employee details using sliders, dropdowns, and input fields.
* **Predict Attrition:** Click the Predict button to generate a result.

### 6. **Analyze Results**
* **Review Predictions:** The model will predict if an employee is at risk of attrition.
* **Check Insights:** The classification report, confusion matrix, and visualizations will highlight key factors influencing attrition.

## 7. **Example Usage Scenario**
**Objective:** The HR team wants to identify employees at risk of leaving.

1. Upload the current employee dataset into the notebook.
2. Run the application to preprocess the data and train the model.
3. Review predictions to identify high-risk employees.
4. Analyze contributing factors and take action to prevent workforce loss.

## **Contributing**
Contributions are welcome! Feel free to open an issue or submit a pull request.

## **License**
This project is licensed under the MIT License.
