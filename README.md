Employee Attrition Analysis Prediction
This project predicts employee attrition using a Random Forest Classifier trained on HR data from IBM. It includes data preprocessing, feature encoding, SMOTE for class balancing, and a UI for making predictions.

Features
Data Preprocessing: Handles categorical and numerical variables.
SMOTE: Balances the dataset for better predictions.
Random Forest Model: Trained on resampled data.
Evaluation: Includes confusion matrix and feature importance plots.
Interactive UI: Uses widgets to input employee details and predict attrition.
How It Works
Prepares Data: Encodes categorical variables, balances data with SMOTE.
Trains Model: Uses a Random Forest classifier.
Evaluates Performance: Prints a classification report and plots a confusion matrix.
User Input via Widgets: Allows entering employee details to predict attrition.

User Guide
1. Download and Install Necessary Software and Libraries
● Python 3.8 or higher
● Jupyter Notebook
2. Install the necessary libraries:
● Pandas
● Numpy
● Scikit-learn
● Imbalanced-learn
● Ipywidgets
● Matplotlib
● Seaborn
3. Download the Application Files
Download the application files from the provided link and make sure to save it locally.
4. Run the Application
● Open Jupyter Notebook
● Open the command line or terminal.
● Navigate to the directory where you saved the application files using the cd command.
For example:
bash
cd C:\(include the file path)EmployeeAttritionPredictor
●
Open the Application Script:
In the Jupyter Notebook window that opens in your web browser, navigate to the directory where
the application file is located.
Click on the EmployeeAttritionPredictor.ipynb file to open the script.
4. Execute the Application
Run the Code Cells - Go through the Jupyter Notebook, running each code cell in sequence by
clicking the “run” button.
The code will load the necessary data, preprocess it, and run the Random Forest Classifier to
predict employee attrition.
5. Use the Application Interface
● Interact with Widgets (if applicable):
186. Analyze Results
Review the results provided by the application, including the classification report,
confusion matrix, and visualizations generated using matplotlib and seaborn. These will give
insights into which employees are at risk of leaving and the factors influencing attrition.
Example Usage Scenario:
The HR team wants to identify employees at risk of attrition.
Upload the current employee dataset in the notebook where prompted. Run the application to
preprocess the data and train the model using the Random Forest Classifier. Review the
predictions to identify high-risk employees and analyze the factors that contribute to their
potential departure. Now HR has identified the employees within the particular ranges specified
and are able to hold meetings with the affected employees to prevent loss of the workforce.
