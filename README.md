# Exploratory Data Analysis Project with AWS S3 + Snowflake SQL
Analyzing patients data with Snowflake SQL to investigate the impact of patient’s PHQ assessment on drug prescription and frequency

<div align="center">
    <img src="images/Whole-Health portfolio featured image.png" alt="Whole Health Logo" style="width: 800px; height: 800px;">
</div>


## Introduction

This short project was completed as part of a job interview assessment for a mental health startup. For the sake of privacy and maintaining anonymity, I am using the name "Whole-Health" instead of the actual company's name.

<br>

<div align="center">
    <img src="images/Whole Health Company Logo.png" alt="Whole Health Logo" style="width: 300px; height: 300px;">
</div>


Whole Health leverages AI, Data Science and Clinical Data to provide affordable, high-quality mental health care to patients, all from the comfort and privacy of their homes.
Senior executives of Whole Health engaged my services to help them analyzing patients data in their database, to investigate the impact of patient’s mental health PHQ assessment on drug prescription and frequency.


<br>


### Datasets
The provided data are synthetic and were simulated from patients in the Whole-Health network.
- Patients: each row represents a unique patient, along with their sex.
- Scores: each row represents a unique instance of a patient completing the [Patient Health Questionnaire (PHQ-9)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1495268/). Scores range from 0-27, with higher scores indicating greater severity of depression symptoms.
- Drugs: each row represents a unique prescription written by a clinician for a single patient.

<br>


### Business Questions to be Answered
- Provide a summary of the patients, drugs and scores datasets separately.  There are no specific guidelines for what to include but your summary should provide a thorough overview of the observations being analyzed.
- Transform the scores dataset to display a comparison view of a patient’s PHQ score on a given date, their score from their previous assessment, and the date of their previous assessment.  Calculate the delta between the current and prior PHQ scores and the amount of time elapsed between the score dates.  The final dataset should contain seven columns: patient_id, phq_score, score_date, prior_phq_score, prior_score_date, phq_score_delta, score_date_delta. 
- Facts/Stats -- report the number of patients for each question (a single number is sufficient):
    - How many patients were prescribed a drug before their first PHQ assessment?
    - How many female patients were assessed for PHQ score at least twice after the first time they were prescribed drug H?

<br>
