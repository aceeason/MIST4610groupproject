# MIST4610groupproject
Group 2 Project

# Members:
1. Aaron Eason - [@aceeason](https://github.com/aceeason)
2. Kiera Lumley - [ksl05149](https://github.com/ksl05149)
3. Navi Khan - [@NaviKhan15](https://github.com/NaviKhan15)
4. Sean Donovan - [@sean4565](https://github.com/sean4565)
5. Gilbert Fahnbulleh -
6. Steven Thomas - 

## **Scenario Description**
Our groups task is to build a database to manage virtual clinic througput and insurance reimbursment. The central entity of the model is the patients. The patients are the clients that the physicians manage. Patience can interact with the model two ways by booking virtual appointments, and by getting their appointments insured. Patients work conjuctively with physicians, appointments, medical encounters, prescriptions and insurance providers. Our group wants to accurately model the patient to medical system interaction, generate sample data, and create a model that manages these relationships. We are performing queries on this data to provide business insight about the telehealth patient and provider portal.

## **Explanation of Data Model**

## **Core Entities:**
1. Patients
2. Physicians
3. Appointments
4. Prescriptions
5. insuranceProvider
6. medicalEncounters
7. Billing
8. Payments
9. medicalRecords
10. consentForms
11. insuranceClaims
12. Availability

# Database Model
![DB Model](dbmodel.png)

# Data Dictionary 

![patients](https://github.com/aceeason/MIST4610groupproject/blob/2af36acab55e5c68239dffc78ba08546825d2dc1/patients.png)

# Query 1
![Query 1](query1.png)

Query 1 shows all patients who have appointments scheduled in March 2026 that have a billing amount higher than average. This helps make sure to follow up with patients it returns that may make them more money.

# Query 2
![Query 2](query2.png)

Query 2 shows all the departments that have the phrase ‘ology’ in their name. This helps management judge the size of each department. 

# Query 3
![Query 3](query3.png)

Query 3 shows the total amount billed by each physician. This allows the administration to track the revenue generation of individual practitioners and evaluate their financial contribution to the clinic. 

# Query 4
![Query 4](query4.png)

Query 4 lists all the dates of all the medical encounters that have not been paid for. This helps the billing department to identify lost revenue or patients who have received care but have not yet initiated a payment. 

# Query 5
![Query 5](query5.png)

Query 5 shows which patients under 30 received a prescription that costs more than $50. This helps identify younger patient demographics that may require financial assistance or high-cost chronic care management.

# Query 6
![Query 6](query6.png)

Query 6 shows which prescriptions were filled at CVS in Athens or Savannah with a quantity over 20. This query analyzes supply chain and pharmacy partnership volume in specific geographic regions.

# Query 7
![Query 7](query7.png)

Query 7 shows which patients have individual bills that are larger than an average of $200.00. This query shows high-cost medical events that might trigger insurance audits or require specialized payment plans. 

# Query 8
![Query 8](query8.png)

Query 8 shows which cities have more than one patient but fewer than 3 total appointments scheduled. This query identifies regions where the practice has a presence but perhaps insufficient appointment conversion or outreach. 

# Query 9
![Query 9](query9.png)

Query 9 shows the total claim amount associated with each insurance plan type. It evaluates which insurance plans are the most "active" within the practice to negotiate better provider rates. 

# Query 10
![Query 10](query10.png)

Query 10 shows the total amount paid per payment method for bills greater than $150.00. This helps management understand how patients prefer to settle larger balances (credit card vs. cash), which can influence decisions on payment processing fees and financial policies. 

