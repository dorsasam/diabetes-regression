# Diabetes Disease Progression Prediction
## Project Description
This project utilises the Sklearn diabetes dataset to predict disease progression based on baseline variables. 
The primary objective is to build a predictive model to forecast the progression of diabetes. 
The process involves exploring the dataset, selecting relevant variables, analysing their distributions and correlations, and then training and evaluating a machine learning model.

## Installation
- Clone the repository:
```bash
git clone https://github.com/dorsasam/diabetes-progression-prediction.git
```
- Navigate to the project directory:
```bash
cd diabetes-progression-prediction
```
- Create a virtual environment and activate it:
```bash
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
```
- Install the required dependencies:
```bash
pip install -r requirements.txt
```
## Data Description
The Sklearn diabetes dataset includes the following variables:
- Independent Variables:
    - **age**: Age of the patient.
    - **sex**: Gender of the patient.
    - **bmi**: Body mass index.
    - **bp**: Average blood pressure.
    - **s1 to s6**: Six blood serum measurements.
- Dependent Variable:
    - **progression**: Measure of disease progression one year after baseline.
  
## Methodology
- Exploratory Data Analysis
    1. Load the dataset and inspect the first few rows.
    2. Identify and separate the independent variables (features) and the dependent variable (target).
    3. Visualise the underlying distribution of the variables.
    4. Investigate the correlation between features using a correlation matrix.
- Feature Selection
    1. Analyse the correlation matrix to identify highly correlated features.
    2. Select the most relevant features based on their correlation with the target variable.
- Model Training and Evaluation
    1. Split the dataset into training and test sets using an 80-20 split.
    2. Train the linear regression model on the training set.
    3. Evaluate the model's performance on the test set using R2 Score.
