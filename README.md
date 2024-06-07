# Capstone-AI-Academy

**Data Set : Breast Cancer Wisconsin (Diagnostic) Data Set**

https://www.kaggle.com/datasets/roustekbio/breast-cancer-csv

## Project Summary

This project aims to develop a predictive model to distinguish between benign and malignant breast tissues using tabular data. The project follows the standard data science steps:

1. **Business Understanding**: 
   - **Objective**: The project aims to develop a machine learning-based predictive model to improve the accuracy of diagnosing breast cancer as malignant or benign. This model intends to assist clinicians in their decision-making, enhancing the precision and speed of breast cancer diagnoses by focusing on the differentiation of complex tissue abnormalities. The ultimate goal is to integrate the model into clinical practice, thereby advancing breast cancer diagnostics and patient care outcomes.
   - **Benefits**: Early and accurate diagnosis can lead to more effective treatment and better patient outcomes.

2. **Data Understanding**: 
   - **Data Description**: 30 features: **field 3** is Mean Radius, **field 13** is Radius SE, **field 23** is Worst Radius.
All feature values are recoded with four significant digits.

Missing attribute values: none

Class distribution: 357 benign, 212 malignant
   - **Data Exploration**: Exploratory Data Analysis (EDA) was conducted to understand the distribution of features and their relationship with the target variable.

3. **Data Preparation**:
   - **Data Cleaning**: In the data preparation phase of the project, we removed entries containing unexpected characters and verified the absence of missing values. Additionally, features exhibiting the lowest correlation to our target variable were excluded to optimize the machine learning model's performance.

4. **Modeling**:
   - **Baseline Models**: A logistic regression model was implemented as a benchmark.
   - **Advanced Models**: XGBoost was used to improve the accuracy and performance of the model.

5. **Evaluation**:
   - **Evaluation Metrics**: Accuracy, precision, recall, false positive rate, and confusion matrix.
   - **Model Comparison**: The results of the logistic regression model and the XGBoost model were compared to determine the best approach, both got a very good performance, reaching 96% of accuracy in croos validation.

## Project Presentation

For a detailed overview of the project, please refer to the presentation at the following link:

[PowerPoint Presentation](https://amedeloitte.sharepoint.com/:p:/r/sites/Ext-AIAcademyVirginiaTech-FY24D4February12Cohort/Shared%20Documents/FY24%20D4%20%E2%80%93%20February%2012%20Cohort/Capstone/Proposals/Group%204/Breast%20Cancer%20Detection%20Group%204.pptx?d=w40f1196c412d4d6c991c7b9bb7c45327&csf=1&web=1&e=XfsH5j)

## Repository Navigation

The repository is structured as follows:

- **data/**: Contains the data used in the project.
  - `breastCancer.csv`

- **notebooks/**: 
  - **Clay/**: Jupyter notebook with code from team member 1.
    - `Clay.ipynb`
  - **Fernando/**: Jupyter notebook with code from team member 2.
    - `Fernando.ipynb`
  - **Gerardo/**: Jupyter notebook with code from team member 3.
    - `Gerardo.ipynb`
  - **Nicholas/**: Jupyter notebook with code from team member 4.
    - `Nicholas.ipynb`
  - **Paula/**: Jupyter notebook with code from team member 5.
    - `Paula.ipynb`
  - **Final Project Notebook**: Final Jupyter notebook containing all the necessary code for reproducing the project.
    - `Final_notebook.ipynb`

Each Jupyter notebook in the subfolders of the team members contains the code and analysis conducted by each member. The final notebook combines the work of all team members and presents the complete project workflow.

---

If you have any questions or suggestions, feel free to open an issue or contact us.

Thank you for your interest in our project!
