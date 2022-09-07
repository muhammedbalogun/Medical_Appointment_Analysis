# Medical_Appointment_Analysis

The dataset used for this analysis is originally from Kaggle. It contains approximately 100 thousand observations of the medical appointment of patients in Brazil. The observations are used to examine whether a patient that was scheduled for an appointment actually turns up for the appointment or not. There are several characteristics of patient that are collected in order to understand what category of patients show up for their medical appointments. There are 14 variables in the dataset.

- PatientId: A unique number for identifying a patient
- AppointmentID: A number generated for the appointment of the patient
- Gender: Whether the patient is a male or female
- ScheduleDay: The date the appointiment was given
- AppointmentDay: The actual day of the appointiment
- Age: The age of the patience
- Neighbourhood: The location of the medical centre
- Scholarship: Whether the patient is on the Brazilian welfare program or not.
- Hipertenton: If the patient is hypertensive or not
- Diabetes: Whether the patient is diabetic or not
- Alcoholism: Whether the patient is an alcoholic addict or not
- Handcap: If the patient is physically challenged or not
- SMS_received: Whether the patient received sms notification for the appointment or not
- No-show: No-if the patient show up and Yes-if the patient did not turn up for the appointment

The are thirteen independent variables in the dataset and only one dependent variable (No-show). The no-show variable is the target vector which we want to explore how other variables in the dataset can help us to predict.

## Conclusions
After carrying out investigation on the categorical dataset to study the relationship between no_show and other features, it can be concluded that the age, gender, scholarship, medical conditions of patients, and drinking habit of patient can be useful in predicting whether a patient will show or not for a medical appointment.

Further investigation through statistical modelling and machine learning prediction should be carried out to further determine the effect of each feature in predicting the no_show outcome.

## Limitations
- The dataset contains majorly categorical data which limit the type of analaysis which can be performed on the data.
- There could be other factors that influence the no_show value of patients which are not provided in the dataset. Example may include the ease of the patient to get to the hospital at the time of appointment.
