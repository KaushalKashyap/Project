🩺 Chronic Liver Disease Prediction

📌 Project Overview
This Project is Basically related to an Health Care . Here, specifically all the features indicates on one and only one part of the Human body i.e, Liver.
Our Motive here is to find out that which factor or factors is actintg as Big influencer in that dataset which leading to Chronical Liver Disease.

Inside this model we have gone through all the insights and analysis tried to reach according to our objective by using graphs and calculation ..
As per this dataset, it is non-linear data, So we proceed with Classification algorithms and based on that evaluation metrics have been modified.

🎯 Objectives

Explore and understand the available healthcare dataset.

Identify relevant variables and patterns in patient data.

Perform data cleaning and preprocessing.

Develop a machine learning classification model, where implemented.

Evaluate predictive performance using suitable metrics.

Examine the potential and limitations of data-driven healthcare analysis.

dataset=pd.read_csv('indian_liver_patient.csv')
dataset.head().transpose()
![image](https://user-images.githubusercontent.com/103347507/209311285-97d1cce5-9b99-451c-8ecb-b555f7533a95.png)

⚙️ Project Workflow

Dataset Loading: Import the available patient dataset.

Data Inspection: Review features, data types, missing values, and duplicates.

Data Preprocessing: Prepare variables and handle missing data using an appropriate method.

Exploratory Data Analysis: Analyze distributions and relationships between features.

Feature Preparation: Encode categorical variables and scale numerical variables when required.

Model Training: Train the classification algorithm used in the implementation.

Model Evaluation: Assess performance on held-out data.

Result Interpretation: Summarize findings and acknowledge limitations.



Before moving to features, first explore about it what exactly role they are playing...

**# total bilirubin Range are 1.2 milligrams per deciliter (mg/dL)
**# Normal range of direct bilirubin for adults is 0.3
**# Alkaline_Phosphotase normal range of total Protein is 6 - 8.3  (g/dL) for adults
**# Alamine_Aminotransferase normal range is 44 to 147 international units per liter (IU/L) or 0.73 to 2.45 microkatal per liter (µkat/L)****
# The normal range for adults is 4 to 36 U/L
# Aspartate_Aminotransferase normal range is 8 to 33 U/L
# Total protein normal range is 6.0 to 8.3 grams per deciliter (g/dL) or 60 to 83 g/L
# Albumin normal range is 3.4 to 5.4 g/dL (34 to 54 g/L
# Albumin_and_Globulin_Ratio and normal serum protein level is 6 to 8 g/dl. Albumin makes up 3.5 to 5.0 g/dl,****


Installation

git clone https://github.com/KaushalKashyap/Project.git
cd Project

Navigate to the Chronic Liver Disease directory. If the project includes a requirements.txt file, install the listed dependencies:

pip install -r requirements.txt

Open the notebook or Python entry point included in the project. Make sure the dataset path matches the location of your local files before running the code.
