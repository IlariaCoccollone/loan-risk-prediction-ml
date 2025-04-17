# loan-risk-prediction-ml
A Machine Learning Project implemented in KNIME focused on predicting loan applicant risk, based on demographic and financial attributes.

## Abstract  
This project explores loan applicant characteristics and performs risk assessment using a complete machine learning workflow in KNIME. The dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/rohit265/loan-approval-dataset), includes 252,000 entries with both numerical and categorical features. The analysis focuses on predicting high-risk applicants to support decision-making in the lending process through data preprocessing, model training, and deployment.

## File Structure 📁

1. **[loan_approval_dataset.csv](./loan_approval_dataset.csv)**  
   The original dataset containing information on loan applicants, including demographic   details, financial status, and the `Risk_Flag` target variable.

2. **[ml_project_dataapp.knwf](./ml_project_dataapp.knwf)**  
   KNIME workflow for data exploration. Visualizing and analyzing the data using various charts and graphs and identifying correlations and patterns in the features.

3. **[ml_project_training.knwf](./ml_project_training.knwf)**  
   KNIME workflow for training machine learning models:

4. **[ml_project_deploying.knwf](./ml_project_deploying.knwf)**  
   KNIME workflow for applying the trained model and predicting loan risk on new data


5. **[Predicting_Loan_Risk.pdf](./Predicting_Loan_Risk.pdf)**  
   Final report summarizing the methodology, model performance, and conclusions drawn from the analysis.

## How to Use the Project 🛠️

1. **Explore the Data**  
   Start with `ml_project_dataapp.knwf` in KNIME to explore and visualize the dataset using graphs, correlations, and initial analyses.

2. **Train ML Models**  
   Use `ml_project_training.knwf` to train and evaluate classification models.

3. **Deploy the Best Model**  
   Apply the model on new data using `ml_project_deploying.knwf`.

4. **Read the Report**  
   See `Predicting_Loan_Risk.pdf` for a complete summary of the project’s findings.

## Dataset 📊  
📂 Source: [Loan Approval Dataset on Kaggle](https://www.kaggle.com/datasets/rohit265/loan-approval-dataset)

## Author 👩🏻‍💻  
**Name**: Ilaria Coccollone  
**Email**: i.coccollone@campus.unimib.it

