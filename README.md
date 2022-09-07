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
