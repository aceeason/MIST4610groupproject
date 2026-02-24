# MIST4610groupproject
Group 2 Project

# Members:
1. Aaron Eason - [@aceeason](https://github.com/aceeason)
2. Kiera Lumley - [ksl05149](https://github.com/ksl05149)
3. Navi Khan - [@NaviKhan15](https://github.com/NaviKhan15)
4. Sean Donovan - [@sean4565](https://github.com/sean4565)
5. Gilbert Fahnbulleh -
6. Steven Thomas - 

## **Explanation of Data Model**
Our groups task is to build a database to manage virtual clinic througput and insurance reimbursment. The central entity of the model is the patients. The patients are the clients that the physicians manage. Patience can interact with the model two ways by booking virtual appointments, and by getting their appointments insured. Patients work conjuctively with physicians, appointments, medical encounters, prescriptions and insurance providers. Our group wants to accurately model the patient to medical system interaction, generate sample data, and create a model that manages these relationships. We are performing queries on this data to provide business insight about the telehealth patient and provider portal.

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



# Query 1
![Query 1](query1.png)



# Query 2
![Query 2](query2.png)



# Query 3
![Query 3](query3.png)



# Query 4
![Query 4](query4.png)



# Query 5
![Query 5](query5.png)



# Query 6
![Query 6](query6.png)



# Query 7
![Query 7](query7.png)



# Query 8
![Query 8](query8.png)



# Query 9
![Query 9](query9.png)



# Query 10
![Query 10](query10.png)

Query 10 shows the total amount paid per payment method for bills greater than $150.00. This helps management understand how patients prefer to settle larger balances (credit card vs. cash), which can influence decisions on payment processing fees and financial policies. 

