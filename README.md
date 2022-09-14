# Project-Investigate-a-Dataset-
In this project, i analyze a dataset and communicated my findings about it
The libraries used in this project are:
- Pandas library: For storing and working with relational or labelled data.
- Numpy: NumPy is a Python library used for working with arrays.
Matplotlib: A data visualization library.For creating 2D graphs and plots. Its module named pyplot makes things easy for plotting by providing feature to control line styles, font properties, formatting axes e.t.c
- seaborn: A data visualization library. It builds on top of matplotlib and integrates closely with pandas data structures.

## Introduction

### Dataset Description 

In this project, I will analysing data from the 100k medical appointments in Brazil which was gotten from Kaggle and in this analysis i will concentrate on finding insights among patients who showed up for a scheduled appointment and how these patients are distinct from those that did not show up for their scheduled appointment.This dataset will also give insights unto why patients do not show up for appointments. Each row represent a patient and they include the following features:
<ul>
    <li> PatientId: this is the unique identification of each patient</li>
<li> AppointmentID: This identifies each appointment</li>
<li> Gender: This gives information about the gender of the patient</li>
<li> ScheduledDay: the date the patient set up the appointment</li>
<li> AppointmentDay: the date of the appointment</li>
<li> Age: The age of the patient</li>
<li> Neighbourhood: The name of the location of the hospital.</li>
<li> Scholarship: Indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.This column says 0 represents False and 1 represents True</li>
<li> Hipertension: this specifies if a patient is has hypertension.This column says 0 represents False and 1 represents True</li>
<li> Diabetes: this specifies if a patient is has diabetes.This column says 0 represents False and 1 represents True</li>
<li> Alcoholism: This shows whether or not a patient has alcoholism. This column says 0 represents False and 1 represents True</li>
<li> Handcap:  This shows whether or not a patient has a disability. This column says 0 represents False and 1 represents True</li>
<li> SMS_received: this indicates wheather any messages were sent to the patient. This column says 0 represents False and 1 represents True</li>
<li> No-show: this shows if a patient shows up to an appointment, its says "No" if the patient showed up and "Yes" if they did not show up.</li>
</ul>
These features would be helpful to determine why some patients show up for appointments and others do not.

### Files
- noshowappointments-kagglev2-may-2016 (1).csv

### Question(s) for Analysis
Some of the questions that will be explored in this analysis are:
<ul>
    <li> What locations had the hoghest number of patients that showed up? </li>
    <li>Features of Patients that showed up to appointments?</li>
    <li>What day of the week did most patients show up?</li>
</ul>
        Many other questions would also be explored. 
        
## Project Methodology
These procedures were taken in order to complete this project
- Data Wrangling
- Exploratory Data Analysis
- Conculsions

## Findings
From the Exploratory Data Analysis, these are the findings.
<ul>
<li> Patients with scholarships show up more to appointments than those without scholarships.</li>
<li> Most of the Patients with diabetes show up for appointments.</li>
<li> Most patients that recived sms before the their appointments showed up to their appointments</li>
<li>Older patients show up more to their appointments than younger patients.</li>
<li> The hospital neighbourhood that most patients showed up for their appointments is JARDIM CAMBURI</li>
    <li>Most patients show up when the day of the week of their appointment is on Wednesday</li>
    </ul>


## LIMITATION
 The limitation in my exploration, Based on the gender column, we can see that there are more females than males in the dataset which there is a disproportion in the dataset in therms of gender.
    
