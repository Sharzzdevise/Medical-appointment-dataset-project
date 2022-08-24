[Investigate a data set project A1.zip](https://github.com/Sharzzdevise/Medical-appointment-data-set/files/8952257/Investigate.a.data.set.project.A1.zip)
# Medical-appointment-data-set
This project is affiliated with Udacity Data Analyst Nanodegree 

In this project, I  Investigated and analyzed a Medical appointment Dataset following through the 6 data analytics process using Python, NumPy, Pandas, Matplotlib, Seaborn tools in a Jupyter notebook, after which I drew insightful and valuable conclusions from the dataset and excellently communicated project findings.

# Introduction
This dataset analyzed was gotten from Kaggle. It collected information from 100k medical appointments in Brazil and is focused on the question of whether or not patients were present or not on their appointment date. A number of characteristics about the patient were included in each row. 
a)‘ScheduledDay’ tells us on what day the patient set up their appointments. You can find the raw csv file here [noshowappointments-kagglev2-may-2016.csv](https://github.com/Sharzzdevise/Medical-appointment-data-set/files/9418278/noshowappointments-kagglev2-may-2016.csv)

b)‘Neighborhood’ indicates the location of the hospital. 
c)‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família. 
d)'PatientId': The ID of each patient. 
e)'AppointmentID': The ID of each appointment. 
f)'Gender': The gender of each patient.
g)'Age': The age of each patient.
h)'Hipertension': It indicates wether the patient suffers from Hipertension or not. 
i)'Diabetes': It indicates wether the patient suffers from Diabetes or not. 
j)'SMS_received': It indicates wether the patient received SMS or not. 
k)'No-show': It indicates wether the patient showed up for the appointment or not.

# Analysis
The analysis was carried out using Python frameworks (NumPy, Panda, Matplotlib, Seaborn). The link is attached to this commit. The analysis breakdown can be found here [Investigate a data set project A1.zip](https://github.com/Sharzzdevise/Medical-appointment-data-set/files/9418285/Investigate.a.data.set.project.A1.zip)


# Conclusion
The dataset has 110527 medical appointments samples of 62298 patients. Judging from the statistics, there is a great possibility that each patient is likely to have multiple appointment records in the dataset. The data gotten further shows that the number of times a patient is given appointments correlates positively to the number of times he is present for the appointment, which draws a conclusion that patients showed up approximately 80% and failed to show up 20% of the times they were given appointments.

From the statistical findings, More appointments were fixed on Wednesdays while Saturdays were the least. Also, appointments were fixed more during the weekdays than the weekends.Considering this statistics; it will be best to fix appointment dates during the weekdays than weekends.

From the statistical findings, 67.90%(75044) did not receive sms while 32.10%(35482) received sms. This statistics shows that sms_distribution will greatly affect the number of patients that will show up on their appointment date, as a greater majority did not receive sms which is very capable of affecting the number of patients that will show up.

The analyzed dataset shows a total of 62,298 patients,64.99% females and 35% males .The patient and gender data set numbers are almost the same, stating there is an even number of appointments distributed between both gender of patients in the dataset. From the statistics; it is clear gender do not affect the number of patients that will be present for their appointments, nevertheless females are likely to be more absent than males.

# Limitations
a)An irregularity was found in the age which is not obtainable (-1);less than 0. 0year. 
b) Very little insight from the neighbourhood feature and patientid
