# At-Risk Student Prediction System
This repository contains the project files for an At-Risk Student Prediction System using machine learning techniques. The project focuses on predicting at-risk students, utilizing binary and multi-class classification models and deploying the solution with XGBoost.

## Folder Structure
### 1. `Binary/`
Contains the machine learning code for binary classification, focusing on distinguishing between at-risk and non-at-risk students.
### 2. `Multi/`
Holds the machine learning code for multi-class classification, predicting multiple risk levels or categories (`Pass`, `Fail`, `Withdraw`) for students.
### 3. `Deployment/`
This folder includes the code for deploying the machine learning model using XGBoost with Streamlit. The deployment is designed to display the outcomes of the predictions effectively.

## Key Files
- **Common Key for Data Integration.ipynb**: Notebook for managing and integrating common keys across datasets.
- **FYP_PreProcessing_Final.ipynb**: Final preprocessing script, handling data cleaning and preparation for analysis.
- **FeatureSelection.ipynb**: Notebook for feature selection to identify important variables.
- **Last10RowsFromDataset.xlsx**: Sample file showcasing the last 10 rows of the dataset used.
- **Model_Comparison.ipynb**: Compares the performance of different machine learning models.
- **OULAD_AtRiskStudentPrediction_Document.docx**: Detailed documentation of the project.
- **Relationships between tables.png**: Diagram showing the relationships between tables in the dataset.
- **model_performance_metrics.png**: Image summarizing the performance metrics of the models.
studData.csv: The primary dataset used for training and testing.

## Original Dataset
The original dataset used in this project can be downloaded from the Open University Learning Analytics Dataset (https://analyse.kmi.open.ac.uk/open_dataset).

## Highlights
- Utilizes **XGBoost** for its robust prediction capabilities.
- Implements both binary and multi-class classification to address different levels of prediction granularity.
- Provides deployment-ready code for showcasing predictions.

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/ChristineFJT/OULAD_AtRiskStudentPrediction_Python
2. Navigate to the relevant folder (Binary, Multi, or Deployment) to explore or run the code.

## Dependencies
Ensure you have the following libraries installed:
- Python (>= 3.7)
- Jupyter Notebook
- XGBoost
- pandas, numpy, matplotlib, seaborn
- sklearn

## Contributors
This project is developed as part of a final year project on predicting at-risk students.
