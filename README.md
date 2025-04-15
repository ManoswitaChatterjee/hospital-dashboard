# Hospital-dashboard
It is an Interactive dashboard to help visualize and analyze key patient and hospital performance metrics for data-driven insights and decision making.

### Introduction
A comprehensive dashboard built to analyze and derive insights regarding hospital admission numbers, hospitals admitted to, patient details, and healthcare KPIs using real-world hospital data.

### Goal 
1. To perform data cleaning to ensure data quality and consistency
3. Visualize key hospital metrics such as admissions, discharges, and patient demographics

### About the Dataset
1. All the data used in this dashboard is from the "healthcare_dataset", available in Kaggle (https://www.kaggle.com/datasets/prasad22/healthcare-dataset?resource=download)
3. This dataset contains fictional hospital data hospital data including patient details, admission/discharge dates, department, diagnosis, and billing information.

____________________________________________________________________________________________________________________________________________________________________________________________________________________

### Data Cleaning - Power BI

#### Steps followed - 
![Screenshot_19](https://github.com/user-attachments/assets/68a3c8b0-f08c-4d81-bc67-4d277fc8876f)


1. **Changed Type -** Changed the type of the following cloumns from "text" to their appropriate types.
  "Age" and "Room Number" to Whole Number
  "Date of Admission" and "Discharge Date" to Date
  "Billing Amount" to Decimal Number

2. **Capitalized Each Word -** For the column "Name", the data was as follows.

![Screenshot_23](https://github.com/user-attachments/assets/79925f66-9112-4600-b1ee-5e5be1c08f29)

This was corrected with proper First Name and Last name capitalization

![Screenshot_27](https://github.com/user-attachments/assets/73e70a7e-7cd2-4e23-979f-10ee8444fba4)

4. **Added Custom -** Created a new column in the data called "Hospitalization Duration (days)" to calculate the total number of days a patient is hospitalized. It is calculated as adifference of "Date of Admission" and "Discharge Date" columns.
  
5. **Changed Type1 -** Changed the type of the new column to Whole Number.

6. **Rounded Off -** Rounded off the "Billing Amount" column vales to two decimal places.

### KPIs 
1. **Patients -** This KPI represents the total number of patients hospitalized in the hospital.
   **Formula :** Count(Name)
   
2. **Avg. Bill (usd) -** This KPI lists the average bill charged per person in the hospital i.e the avergae bill one can expect if being hospitalized.
   **Formula:** Average(Billing Amount)
   
### Analysis
This dashboard aims to provide a detailed analysis of hospital performance and patient-related trends using key healthcare indicators.

The dashboard offers a broad understanding of patient admissions, hospitalization duration, and overall hospital metrices. By highlighting these areas, the report supports better understanding for people like - what bill they might expect, best insurance provider and so on.

### Overview 

1. Total Patient Count - 55.50k
2. Average Bill for patients (in usd) - 25.54k

![Screenshot_15](https://github.com/user-attachments/assets/17b7424c-6248-4c80-99ea-a29e150d69b6)

#### Insight:
Helps to understand the amount of bill one might expect if hospitalized in the hospital.

#### Average Billing Amount by Insurance Provider

This Donut chart shows which insurance provider is mostly availed by the hospitalized patients. "Medicare" ranks first by a small margin.

![Screenshot_17](https://github.com/user-attachments/assets/20c663be-3616-4081-83fa-bfa1adfc918d)

#### Average Billing Amount by Age Group

This bar chart categorizes patients in age groups and shows which age group gets the higher end of the hosiptal bill.

![Screenshot_18](https://github.com/user-attachments/assets/50c0e8ac-0e88-4817-81cc-f4b4ffb335cb)

#### Hospitalization Duration (days) by Age Group

This line chart displays which age group patients has to be hospitalized for an average of how many days with obvioulsy 65+ people average being the higehest at about 15.59 days.

![Screenshot_21](https://github.com/user-attachments/assets/3a242b92-c38f-4bfe-a0e2-1a1a8d883399)


#### Count of Name by Admission Type

This pie chart displays the distribution of admission type in the hospital. Most patients are hospitalized under elective.

![Screenshot_25](https://github.com/user-attachments/assets/bceca7d3-d4ef-4deb-acad-96f44adb1ff4)

#### Count of Patients by Doctor

It displays the top 3 doctors who have treated the most patients with "Michael Smith" being at the first position with a count of 27 patients under him.

![Screenshot_20](https://github.com/user-attachments/assets/d51c361b-1471-4266-ae49-51ad68a63a25)

#### Average Age by Gender

It displays the gender ratio of patients admitted to the hospitals with the female patient count being slightly higher.

![Screenshot_22](https://github.com/user-attachments/assets/047e1c66-aafc-441c-a200-87db84c3ae9a)

### Final Dashboard 

![Screenshot_26](https://github.com/user-attachments/assets/523d2318-e28c-444c-aaf5-99267889773f)

### Filters 
1. **Admission Year -** To filter patients data w.r.t the year they are admitted in the hospital.
2. **Age Group -** To filter data by patient age group.
3. **Medical Condition -** This filters patients by their diagnosed medical condition.
4. **Hospital -** To filter data by the hospital name.
5. **Insurance Provider -**  This filters data by the insurance provider patients are under.

![Screenshot_16](https://github.com/user-attachments/assets/30d03354-8718-4573-bb48-0824b0cf1cd3)


### Conclusion 

The Hospital-dashboard provides a analysis of both hospital and patient data using the sample kaggle data set. The data is first cleaned and made appropriate for analysis and the vizualized into the dashboard using Power BI. The report highlighted essential performance metrics and uncovered valuable insights into hospital utilization, patient trends, and operational efficiency.

#### Recommendations and Key Takeaways

1. Unsurprisingly 65+ people are hospitalized for the most number of days and thus need more attention and regular check-ups.
2. Patients with 0-18 age have higher bill amount which may indicate that they are mostly hospitalized for some serious injury or immediate operations.
3. The KPI "Avg. Bill (Usd) indicates that a patient if hospitalized can expect an average bill amount of $25,540. Ofcourse this data varies hospital to hospital and can be checked using the "Hospital" filter.

This project helps visualize data and uncover insights, enabling both patients and hospitals to understand key metrics and support better decision-making for patient care and hospital operations.
