## Heart Failure Clinical Dataset Analysis
Project Overview
This project is focused on analyzing the heart_failure_clinical_records_dataset.csv, which contains data related to clinical features and the survival of patients with heart failure. The goal is to explore the dataset, generate insights, and provide a descriptive summary of the data.
Dataset
The dataset consists of 299 rows and 13 columns. It includes patient attributes such as age, creatinine levels, platelets count, and whether the patient died during the follow-up period (DEATH_EVENT).
Columns:
•	age: Age of the patient
•	anaemia: Whether the patient has anemia (1 = yes, 0 = no)
•	creatinine_phosphokinase: Level of the CPK enzyme in the blood
•	diabetes: Whether the patient has diabetes (1 = yes, 0 = no)
•	ejection_fraction: Percentage of blood leaving the heart each time it contracts
•	high_blood_pressure: Whether the patient has hypertension (1 = yes, 0 = no)
•	platelets: Platelet count in the blood
•	serum_creatinine: Level of creatinine in the blood
•	serum_sodium: Level of sodium in the blood
•	sex: Gender of the patient (1 = male, 0 = female)
•	smoking: Whether the patient smokes (1 = yes, 0 = no)
•	time: Follow-up period in days
•	DEATH_EVENT: Whether the patient died during the follow-up period (1 = yes, 0 = no)
Requirements
The following libraries are required to run the notebook:
bash
Copy code
pip install pandas numpy seaborn matplotlib
Usage
1.	Load the Data: The dataset is loaded using pd.read_csv() and is stored in the heart_data variable.
2.	Data Exploration: Basic descriptive statistics, including data types, the first few rows (head()), and the dataset's shape (shape), are explored to understand the distribution of features.
3.	Statistical Analysis:
o	The dataset undergoes various numerical and categorical analyses to provide insights into the relationships between features and patient survival (DEATH_EVENT).
Results
Through data exploration and statistical analysis, key patterns in patient attributes such as age, serum creatinine levels, and ejection fraction were identified in relation to patient mortality. These insights could be valuable for identifying high-risk patients.
License
This project is open-source and available for use and modification.

