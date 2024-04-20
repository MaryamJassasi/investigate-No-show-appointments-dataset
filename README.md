# project title: investigate-No-show-appointments-dataset

# description: 
This repository is focused on exploring and analyzing a dataset that contains information about medical appointments.
The main objective is to identify factors that contribute to patients not showing up for scheduled visits, 
commonly known as "no-shows". By doing so, we aim to obtain insights that can help healthcare providers 
and institutions to decrease the number of no-shows and improve patient care.

# Questions to be answerd
  What are the key factors that influence whether patients attend their appointments or not?
  - Is there a correlation between age and the number of no-shows?
  -  Is there any specific scheduled time (hour or day) when patients tend to not show up for their appointments frequently?
  - Which types of patients are more likely to miss their appointments - those with hypertension, diabetes, or alcoholism?(correlation)

# Dataset:
The dataset is available online and has been uploaded here.
THe dataset contains 14 columns and 110527 rows. 
The key features: Gender, Age, ScheduledDay, Scholarship, Hypertension, 
                  Diabetes, Alcoholism, SMS_received and No-show

# Data Preprocessing:
- check up for missing and duplicated data
- check up for unlogical data (one rwo has been deleted)

# Exploratory Data Analysis (EDA):
Visualize and analyze the data to understand patterns and potential relationships between no-show appointments and other factors. Examples include:
- Descriptive statistics for all features 
- Categorical visualizations (bar charts, pie charts) for features like count os showed and no showed patients
- Boxplots to explore differences in no-show rates across groups (e.g., age, ScheduledDay).
- correlation between no-show and other features using Chi-squared test

# Findings
All analysis and result can be find in the Jupyter notbook

Conclusion:

After analyzing the dataset of no-show appointments, it has been observed that Approximately 20% of patients did not attend their appointments on the scheduled day. Moreover, the number of female patients is higher than male patients. From bar charts the frequency of all patients and those who did not show up is the same for different variables like receiving SMS reminders and alcoholism. Also, more than half of the patients did not receive a reminder via SMS. The median age of attended patients(No) is higher than that of absent patients, indicating that older patients are more likely to show up. The median appointment hour for no-shows seems to be later in the day compared to appointments attended (based on the higher median line in the "No-Show" box). This suggests a trend where appointments scheduled for later hours might have a higher rate of no-shows. On most days, patients’ absences are highest on Tuesdays, followed by Wednesdays and Mondays for both groups. However, we cannot confirm any conclusions based solely on these observations. The Chi-Square test is condsider a poerful statistical tool for study association between two binary variables. Chi-squared tests have shown associations between no-shows and receiving an SMS, hypertension, diabetes, and scholarship, but no association with alcoholism.

# limitation: 
However, there is still more to discover in this dataset. Different statistical tests can be conducted to confirm the initial insights, and factors such as the neighborhood and handicap need to be studied, which may influence attendance.
# Important note: This analysis is for code practice only and cannot be used to draw any results or conclusions.
