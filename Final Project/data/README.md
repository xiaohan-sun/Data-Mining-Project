# Data

We have filtered out all the missing value and unknown value in state/ age_group/ sex/ race/ exposure_yn/ symptom_status/ hosp_yn/ icu_yn/ death_yn columns.

* Cleaned Data [here](https://drive.google.com/file/d/158sOsgAKiuG0DVC-0CrCDPE8I9qftumi/view?usp=sharing)

* Source: [CDC](https://data.cdc.gov/Case-Surveillance/COVID-19-Case-Surveillance-Public-Use-Data-with-Ge/ynhu-f2s2)

# Codebook

* **case_month:** The earlier of month the Clinical Date (date related to the illness or specimen collection) or the Date Received by CDC.
* **res_state:** State of residence.
* **race:** American Indian/Alaska Native; Asian; Black; Multiple/Other; Native Hawaiian/Other Pacific Islander; White; Unknown; Missing; NA, if value suppressed for privacy protection.

* **ethnicity:** Hispanic; Non-Hispanic; Unknown; Missing; NA, if value suppressed for privacy protection.
* **age_group:** 0 - 17 years; 18 - 49 years; 50 - 64 years; 65 + years; Unknown; Missing; NA, if value suppressed for privacy protection.
* **sex:** Female; Male; Other; Unknown; Missing; NA, if value suppressed for privacy protection.
* **underlying_conditions_yn:** Did the patient have one or more of the underlying medical conditions and risk behaviors: diabetes mellitus, hypertension, severe obesity (BMI>40), cardiovascular disease, chronic renal disease, chronic liver disease, chronic lung disease, other chronic diseases, immunosuppressive condition, autoimmune condition, current smoker, former smoker, substance abuse or misuse, disability, psychological/psychiatric, pregnancy, other.
* **process:** Under what process was the case first identified? (Clinical evaluation; Routine surveillance; Contact tracing of case patient; Multiple; Other; Unknown; Missing)
* **case_positive_specimen_interval:** Weeks between earliest date and date of first positive specimen collection.
* **case_onset_interval:** Weeks between earliest date and date of symptom onset.
* **exposure_yn:** In the 14 days prior to illness onset, did the patient have any of the following known exposures: domestic travel, international travel, cruise ship or vessel travel as a passenger or crew member, workplace, airport/airplane, adult congregate living facility (nursing, assisted living, or long-term care facility), school/university/childcare center, correctional facility, community event/mass gathering, animal with confirmed or suspected COVID-19, other exposure, contact with a known COVID-19 case? (Yes, Unknown, Missing)
* **death_yn:** Did the patient die as a result of this illness? (Yes; No; Unknown; Missing; NA, if value suppressed for privacy protection.)
* **symptom_status:** What is the symptom status of this person? [Asymptomatic, Symptomatic, Unknown, Missing]
* **hosp_yn:** Was the patient hospitalized? (Yes, No, Unknown, Missing)
* **icu_yn:** Was the patient admitted to an intensive care unit (ICU)? (Yes, No, Unknown, Missing)


Source: [CDC](https://data.cdc.gov/Case-Surveillance/COVID-19-Case-Surveillance-Public-Use-Data-with-Ge/ynhu-f2s2)
