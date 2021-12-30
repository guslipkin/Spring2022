# Data Description

## Encounters.csv

- EncounterID – unique patient identifier KEY
- PatientID     
- Admit Date   
- Discharge Date      
- Gender      
- Age   
- MSDRG – (Medicare Severity Diagnosis Related Group) 
- Principal Diagnosis – what brought the patient to the hospital 
- Attending Physician – physician assigned to patient
- Attending Physician Specialty 
- Discharge Unit
- Discharge Disposition - where the patient was discharged to 
- PatientRace   
- PatientEthnicDesc    
- InsFinClassDesc – insurance class 

## Readmissions.csv

- ReadmitEncounterID – readmission unique patient identifier
- EncounterID – unique patient identifier KEY
- Index Disch Date – original visit discharge date
- Index Admit Type - original visit admit type (will get more detail on this)
- Index Admit Source – original visit point of origin for admission 
- Index Disch Disposition – original visit where the patient was discharged to 
- Readmit Date 
- Days Between Admssions – days between original admission and readmission 
- Readmit Admit Source – readmit point of origin for admission
- Readmit Admit Type – readmit visit admit type (will get more detail on this)
- Readmit Disch Disposition – readmit where the patient was discharged to
- Index MSDRG - original visit MSDRG
- Index Princ Dx  - original visit Principle diagnosis
- Readmit MSDRG – readmit visit MSDRG
- Readmit Princ Dx – readmit Principle diagnosis
- ReadmitInfo.PatientEthnicDesc
- ReadmitInfo.PatientRace    
- ReadmitInfo.InsFinClassDesc 
- Readmit Discharge Date     
- ReadmitInfo.Gender  
- ReadmitInfo.Age     
- Readmit Discharge Unit

## ConnectCalls.csv

- EncounterID – unique patient identifier KEY
- Last Status – status of the survey 
- Updated On – When last call/status/note was added or updated
- AQ# - Alert Question (can be multiple for one call. If there are multiples, it will show up as AQ1, AQ2 with the same posted date)
- Posted_Date# - when follow up call was made (multiple calls can be made)

## Surveys.csv

- SurveyID – (will get more detail on this)

- SurveyNumber – unique survey number

- AdmitDate   

- AdmitSource – (will get more detail on this)

- AgeBand – age range

- EncounterID – unique patient identifier KEY

- CMS_Reportable – is this survey reportable to CMS (official survey or unofficial)

- DepartmentNum – (will get more detail on this)

- HospServiceCode – service patient is discharged under? (will get more detail on this)

- MortalityFlag - (will get more detail on this)

- SERVICE – Inpatient (all are inpatient)

- UnitLongName – Full Discharge Unit name

  ______________________________________________________________________________

- For all of the below: Unless other wise noted with a (y/n), all questions are on a scale of Never (1), Sometimes (2), Usually (3), and Always (4). For (y/n) questions, Y (1), N (0). 
  - CMS_1 - During this hospital stay, how often did nurses treat you with courtesy and respect?
  - CMS_2 - During this hospital stay, how often did nurses listen carefully to you?
  - CMS_3 - During this hospital stay, how often did nurses explain things in a way you could understand?
  - CMS_6 - During this hospital stay, how often did doctors treat you with courtesy and respect?
  - CMS_7 - During this hospital stay, how often did doctors listen carefully to you?
  - CMS_8 - During this hospital stay, how often did doctors explain things in a way you could understand?
  - CMS_10 – During this hospital stay, how often were your room and bathroom kept clean? 
  - CMS_11 – During this hospital stay, how often was the area around your room quiet at night?
  - CMS_12 – During this hospital stay, did you need help from nurses or other hospital staff in getting to the bathroom or in using a bed pan? (y/n)
  - CMS_13 – How often did you get help in getting to the bathroom or in using a bedpan as soon as you wanted?
  - CMS_18 – During this hospital stay, were you given any medicine that you had not taken before? (y/n)
  - CMS_19 – Before giving you any new medicine, how often did hospital staff describe possible side effects in a way you could understand? 
  - CMS_20 – After you left the hospital, did you go directly to your own home, to someone else’s home, or to another health facility? 
  - CMS_21 – During your hospital stay, did hospital staff talk with you about whether you would have the help you needed when you left the hospital? (y/n)
  - CMS_22 – During your hospital stay, did you get information in writing about what symptoms or health problems to look out for after you left the hospital? 
  - CMS_23 – Using any number from 0-10, where 0 is the worst hospital possible and 10 is the best hospital possible, what number would you use to rate this hospital? 
  - CMS_24 – Would you recommend this hospital to your friends and family?
  - CMS_25 – In general, how would you rate your overall health? 
  - CMS_26 – In general, how would you rate your overall mental or emotional health? 
  - CMS_27 – What is the highest grade or level of school that you have completed? 
  - CMS_28 – Are you of Spanish, Hispanic, or Latino origin or descent? 
  - CMS_30 – What language do you mainly speak at home? 
  - CMS_33 – Before giving you any new medicine, how often did hospital staff tell you what the medicine was for? 
  - CMS_34 – I never pressed the call button
  - CMS_37 – During this hospital stay, after you pressed the call button, how often did you get help as soon as you wanted it? 
  - CMS_38 – During this hospital stay, staff took my preferences and those of my family or caregiver into account in deciding what my health needs would be when I left?
  - CMS_39 – When I left the hospital, I had a good understanding of the things I was responsible for in managing my health? 
  - CMS_40 – When I left the hospital, I clearly understood the purpose for taking each of my medications? 
  - CMS_41 – During this hospital stay, were you admitted to this hospital through the emergency room?
  - CMS_42 – do not analyze (questions not asked anymore)
  - CMS_43 - do not analyze (questions not asked anymore)
  - CMS_44 - do not analyze (questions not asked anymore)
