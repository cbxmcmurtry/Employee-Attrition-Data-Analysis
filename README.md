# Employee Attrition Analysis & Prediction
This project predicts employee attrition using a Random Forest Classifier trained on HR data from IBM. It includes data preprocessing, feature encoding, SMOTE for class balancing, and an interactive UI for making predictions.

## Features
Data Preprocessing: Handles categorical and numerical variables.
SMOTE (Synthetic Minority Over-sampling Technique): Balances the dataset for better predictions.
Random Forest Model: Trained on resampled data for robust classification.
Evaluation Metrics: Generates a classification report, confusion matrix, and feature importance plots.
Interactive UI: Uses widgets to input employee details and predict attrition.
⚙️ How It Works
Prepares Data: Encodes categorical variables and balances data using SMOTE.
Trains Model: Uses a Random Forest Classifier on the resampled dataset.
Evaluates Performance: Displays the classification report and confusion matrix.
User Input via Widgets: Allows entering employee details to predict attrition.

## User Guide
1️⃣ Install Necessary Software & Libraries
### Required Software:
Python (Version 3.8 or higher)
Jupyter Notebook
Required Libraries:
Install the necessary Python libraries using the following command:

pip install pandas numpy scikit-learn imbalanced-learn ipywidgets matplotlib seaborn

### Download the Application Files
Download the application files from the provided link and save them locally.

### Run the Application
Open Jupyter Notebook
Open the command line or terminal.
Navigate to the project directory using the cd command:
bash
cd /path/to/EmployeeAttritionPredictor
Launch Jupyter Notebook by running:
bash
jupyter notebook
In the Jupyter Notebook interface, navigate to the project directory and open the EmployeeAttritionPredictor.ipynb file.

## Execute the Application
Run all code cells in sequence by clicking the “Run” button in Jupyter Notebook.
The code will:
Load the dataset
Preprocess the data
Train the Random Forest Classifier
Make predictions on employee attrition

## Use the Application Interface
Interact with Widgets: Enter employee details using sliders, dropdowns, and input fields.
Predict Attrition: Click the Predict button to generate a result.

## Analyze Results
Review Predictions: The model will predict if an employee is at risk of attrition.
Check Insights: The classification report, confusion matrix, and visualizations will highlight key factors influencing attrition.

## Example Usage Scenario
Objective: The HR team wants to identify employees at risk of leaving.

Upload the current employee dataset into the notebook.
Run the application to preprocess the data and train the model.
Review predictions to identify high-risk employees.
Analyze contributing factors and take action to prevent workforce loss.

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License.
