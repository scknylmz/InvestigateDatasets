
## Project Overview

In this project, I will analyze a dataset and then communicate MY findings about it. I will use the Python libraries NumPy, pandas, and Matplotlib to make your analysis easier.


### Question(s) for Analysis

1. Is gender effecting "No-show" data? 
2. Is there any seasonal aeffect on "No-show" data? 
3. what is the effect of age on "No-show" data?
4. what is the effect of neighbourhood on "No-show" data?
5. Is SMS effecting "No-show" data?
6. What is the most effecting illness (Hipertension, Diabetes, Alcholism, Handcap) on "No-show" data?
7. Is there any corelation between No_show and delta time ( Appointment Day - Scheduled Day)


## Conclusion Phase

The conclusion is missing the limitation of the dataset. You need to state what do you conclude from the analysis, what could be your future work or potential areas to explore. Were there some shortcommings/factors limiting your analysis. All this should be clearly stated.

According to my findings,
- %20 of all patients not comes the appointment in time.
- Both gender is nearly equal percentage for show up on their appointments.
- Huge number of data come from between 2016-04 and 2016-06.
- As patients old, they arrive **on time** for their appointments more than other ages. And also it is valid for Child ages. 
- Patients count come from different neighbourhood is not homogeneous.
- The rate of "No_show is True" is very similar for all areas except "Ilhas Oceanicas de Trindade" and "Paraque Industrial". All patients comes from "Ilhas Oceanicas de Trindade" are not attend the appointment in time. And none of patients comes from "Paraque Industrial" are not attend the appointment late.
- The most neighbroadhood which not come the appointment in time is "Jabdim Cambur". 
- Only **1/3** of patient have received SMS.
- Even the SMS Receiving count is **high** patinetn who not come appointment in time number is high.
- 65% of all patients have corelation between *received SMS* and *do not come to their appointment in time*.
- The most receiving SMS ages are between 18-30 years old. But there is no much difference between age groups except Child ages.
- Even the counts are extremly similar with hipertension and not come to their appointment in time, 67% of all patients have corelation between *hipertension* and do not come to their appointment in time.
- 75% of all patients have corelation between *diabetes* and do not come to their appointment in time.
- 78% of all patients have corelation between *Alcoholism* and do not come to their appointment in time.
- 79% of all patients have corelation between *Handcap* and do not come to their appointment in time.
- Average days between scheduled day and appointments when the patients are **not come** to their appointment on time is 15 days.
- Average days between scheduled day and appointments when the patients **come** to their appointment on time is 8 days.
- There is a negative coleration between appointment on time and days between scheduled day and appointments.

Limitations,
- some of data columns are meaningless. 
- The date before 2016-04 is not much contain data. All datas are focusing between 04-2016 and 06-2016.

- If there were appointment realized date, it can be more meaningfull. 
- Also if there were SMS sending date I would be much meaningfull. 

Future Work,
- Combunation of columns like gender x age x features can be analysis. 
- Whether the same person arrives late to the appointment or not can be analyzed.