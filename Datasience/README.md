# Task Description
 
Your task is to build a classifier to predict if a patient has diabetes.
 
## Details
1. We recommend using Python to solve the task, but you may also opt for R or any other suitable language.
2. Kindly provide your source code, and if you choose Python, utilizing a Jupyter notebook is preferable.
3. Your presentation should showcase the results, findings, and solutions. Note that PowerPoint presentations are not required; a well-structured notebook will suffice.
4. This task intentionally offers some flexibility and can be approached as intricately as you wish. However, we understand your time constraints, and we don't expect you to dedicate more than 2 hours to the solution. Feel free to focus on specific aspects, and please indicate at the beginning of your solution presentation which parts you have chosen to address.
 
## Guiding questions:
1. Begin by exploring the data. Are there any general remarks or questions that come to mind regarding the dataset?
2. Extract relevant statistics that you find interesting.
3. Choose a classifier e.g. RandomForest and train it.
 
## Dataset Overview: You will be working with synthetic datasets representing patient information, medical tests, and hospital visits for a fictional hospital. The datasets contain the following tables:
 
Patients Table:
- patient_id: Unique identifier for each patient.
- age: Age of the patient.
- gender: Gender of the patient.
- is_smoker: Boolean indicating if the patient is a smoker.

Medical Tests Table:
- test_id: Unique identifier for each medical test.
- patient_id: Unique identifier for each patient.
- bmi: Body Mass Index of the patient.
- blood_pressure: Systolic blood pressure in mmHg.
- cholesterol: Cholesterol level in mg/dL.
- glucose_level: Glucose level in mg/dL.
- test_date: Date when the test was conducted.

Hospital Visits Table:
- visit_id: Unique identifier for each hospital visit.
- patient_id: Unique identifier for each patient.
- visit_date: Date of the visit.
- department: Department where the visit occurred.
- has_diabetes: Boolean indicating if the patient has diabetes (target variable).