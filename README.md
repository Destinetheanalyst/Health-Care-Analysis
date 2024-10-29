# Health-Care-Analysis

### Project Overview
The goal of this project is to analyze and interpret a healthcare dataset that includes key variables such as total billing amount, number of doctors, medical conditions, and number of hospitals. The analysis aims to uncover insights into healthcare billing trends, resources allocation, and the impact of medical conditions on costs.

### Data Source

Health Care Dataset: The primary data set used for this analysis is the "healthcare_dataset.csv", which contains a comprehensive informations about various illnesses, healthcare providers, insurance etc.

### Data Dictionary
1.	Billing Amount: The total amount billed for healthcare services within a specific timeframe.
2.	Doctors: The count of medical professionals available in the dataset, and their names indicating healthcare providers availability.
3.	Medical Conditions: A list of medical conditions treated, which may impact billing and resources needs.
4.	Number of Hospitals: The count of hospitals included in the datasets, providing context for the distributions.
5.	Date of Admission: This is the date, which a patient is being admitted in a hospital.
6.	Medication: This is the drug given to different patients with different medical conditions. 
7.	Blood Type: The different blood types associated with different patients.
8.	Test: The different test carried out on patients with different medical conditions.
9.	Full Name: The count of patients with different medical conditions, and their full names
10.	Discharge Date: This is the date, which a patient is being discharged from the hospital.
11.	Room Number: The different room number in the different hospitals.
12.	Gender: The sex of different patient.
13.	Admission Type: The different admission status of patients with different medical conditions.


### Tools

- Excel - Data collection and Data Cleaning
- Power Bi - Data Visualization and Dashboard.
- PowerPoint -  Creating reports

### Data Collection and Data Cleaning

In the initial data preparation phase, we performed the following tasks:

  1. Data Collection- This is a secondary data collected from Kaggle
  2. Data loading and inspection.
  3. Handling missing values.
  4. Data cleaning and formatting.

### Exploratory Data Analysis

EDA involved exploring the Health Care data to answer key questions, such as:

  - Mean age of patients.
  - Distribution of blood type among patients.
  - Frequency of patients’ admission by gender.
  -	Most prevalent medical conditions and their frequency
  -	Medications prescribed for different medical conditions and their frequency.
  -	Total billing amount.
  -	Average billing amounts associated with different medical conditions and different admission type
  -	Patients’ preference for insurance providers.
  -	Frequency of patients across different years, quarters, months, and days.

### General Insights
- The total number of patients are 54964 with their average age of 51.54.
- Sum of billing amount is $1.4bn.
- 6 years was considered in the analysis, ranging from 2019-2024.
- The total number of doctors are 40341.
- The total number of hospitals are 39876.
- A total of 400 rooms was used by the hospitals.
- 8 blood types were discovered during analysis.
- The analysis was carried out on 6 medical conditions.
- The patients used a total of 5 insurance providers.

### Health Insights
- The most frequent blood type is A blood type having a total of 6898 patients which makes up 12.6% of total patients. O- blood type is the least blood type having a total of 6804 patients and 12.4% of the total patients.
-	The frequent medical condition is Arthritis with a total of 9218 patients, Diabetes has a total of 9216 patients. Asthma is the medical condition with the least patients with 9095 patients and a percentage of 16.5%
-	The most consistent admission type is Elective. With a total of 18473 and a percentage of 33.61%. Emergency admission type is the least with 18101 patients and at the rate 32.93% 
-	In terms of gender, the males are the most diagnosed patients, with 27495 patients and 50.02% while the females have a rate of 49.98% and they are 27469 patients.
-	The most prescribed medication is Lipitor and it was used 11038 patients. It was most used on patients with urgent admission type with a percentage of 34.21% and a total of 3776 patients. It was used by 9415 doctors.
-	2020 has the most patients, with a total of 11172 patients and the percentage of 20.03%. With Qtr. 3 having the most patients and a total of 2902 patients. 
-	2019 has a total of 7299 patients, with Qtr. 4 having the most with 2864.
-	2021 has a total of 10816 patients, with Qtr. 4 having the most with 2728.
-	2022 has a total of 10914, with Qtr. 3 having the most with 2794.
-	2023 has a total of 10936, with Qtr. 3 having the most with 2788.
-	2024 has a total of 3827 so far since just 2 Qtrs. records has been collected. With Qtr. 1 having the most with 2674.

### Financial Insights
- The sum of billing amount is $1.4bn.
- The sum of $236.49m was made from Diabetes.
- The sum of $236.01m was made from Obesity.
- The sum of $235.17m was made from Arthritis.
- The sum of $233.38m was made from Hypertension.
- The sum of $233.14m was made from Asthma.
- The sum of $229.85m was made from Cancer.
- The total of $473.13m was made from Elective admission type. With Hypertension being the highest with a sum of $81.32m and Obesity being the least with $77.45m.
- The total of $469.21m was made from Urgent admission type. With Diabetes being the highest with a sum of $81.47m and Cancer being the least with $75.63m.
- The sum of $461.67m was made from Emergency admission type. With Obesity the highest with $80.04m and Cancer the least with $74.28m.

### Recommendation
The followings are my recommendations 
1.	Citizens are advised to eat healthy, drink enough water and sleep regularly. 
2.	Citizens are advised to reduces stress.
3.	Citizens are advised to exercise regularly.
4.	Citizens are advised to maintain a healthy weight.
5.	NGOs are advised to go for outreaches to educate citizens on the importances of living a healthy life.

### Limitations
- I had to remove all zero values from age column because they would have affected the accuracy of my conclusions from the analysis.
- Feature Selection
- Data Availability and Quality
- Unobserved Heterogeneity
- Risk Compensation

### Conclusion
This healthcare dataset was gotten from 39876 hospitals, testing 6 medical conditions, and total patients of 54964. These hospitals have a total of 40431 doctors, and 400 rooms. 27495 Male patients were diagnosed of these medical conditions which makes of 50.02% of the patients. The female patients are 27469, which makes up 49.98% of the total patients. This data was collected between 2019-2024, with 2020 having the greatest number of patients. They patients with Elective admission type consists of 33.61% of the total patients. The made a total sum of $1.4bn between 2019-2024.
