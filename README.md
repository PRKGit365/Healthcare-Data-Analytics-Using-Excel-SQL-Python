## 📊CLINICAL (LAB RESULTS) AND CLAIMS (PHARMACY) ANALYSIS (EXCEL, SQL AND Python)

📖 **Description**  

This skillup.online project focuses on integrating clinical and claims information using Excel, MySQL and Python.

🔍 **Dataset Overview**  

*Claims (Pharmacy) Table* 

Rows: 101  
Columns: 9  
Fields and Descriptions:
* Claim ID - unique identifier for a claim generated after a claim is submitted and is used to track, manage and verify claims for the patient over time
* Patient ID - unique identifier assigned to a patient by a healthcare facility linking to their specific medical records, treatments and services received
* Medication - medication given to a patient
* Dosage - dosage of medication given to a patient
* Fill Date - date medication for a patient was filled
* Payer - the insurer the patient used when paying for the medication
* Clinic ID - unique identifier for the clinic used by the patient
* Charge Amount - the amount charged for the medication or services rendered to the patient
* Paid Amount - the amount the patient paid for the medication or services rendered to the patient

*Clinical (Lab Results) Table*

Rows: 202  
Columns: 9  
Fields and Descriptions:
* Patient ID - unique identifier assigned to a patient by a healthcare facility linking to their specific medical records, treatments and services rendered
* Lab Test ID - internal LB variable identifier
* Collection Date - when the specimen was collected
* Test Name - name of the lab test
* Test Result Value - Raw or numeric result of lab test
* Units - mg/dL for all lab tests performed other than HbA1c, % for HbA1c
* Reference Range Low - lower bound for normal range
* Reference Range High - upper bound for normal range
* Abnormal Flag - High/Normal/Low indicator - high if higher than the normal range, normal if within the normal range, and low if lower than then normal range
* Paid Amount - the amount the patient paid for the medication or services rendered to the patient

 🛠 **Tools & Technologies**  
 
![EXCEL](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)  
![](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)  
![Python](https://img.shields.io/badge/Python-%2300C4CC.svg?style=for-the-badge&logo=Python&logoColor=white)




