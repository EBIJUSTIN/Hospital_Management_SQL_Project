# Hospital_Management_SQL_Project

EXPLORING: 7 RELATED TABLES

    Department,Patients,Doctor,Appointment,Medicines,Prescriptions,Billing
    
PROJECT Introduction
Stores hospital information in a single relational database.

Connects patients, doctors, appointments, prescriptions and billing.

Supports accurate day-to-day operations and useful analysis.

Project objectives
Design a normalized seven-table MySQL database.
Maintain reliable patient, doctor and appointment records.
Use SQL to answer operational and billing questions.

Why this project is useful
Reduces duplicate data through linked tables.

Makes appointment history easy to retrieve.

Supports inventory and payment tracking.

Provides practical SQL portfolio evidence.

Sample use case

Register a patient and schedule a doctor visit.

Identify appointments by department or status.

Calculate bills and follow up on pending payments.

Check low-stock and near-expiry medicines.

Query classification 

  <img width="1084" height="320" alt="Screenshot 2026-08-11 094147" src="https://github.com/user-attachments/assets/f20ec5e1-4eb0-498f-a2a2-8f82ca3bafd7" />

SCHEMA-STAR SCHEMA-HOSPITAL_MANAGEMENT-DATABASE

<img width="1149" height="649" alt="Screenshot 2026-08-10 211314" src="https://github.com/user-attachments/assets/659d3bf7-b3d5-4c1a-b915-3de7ce81d0c5" />

Constraints protect data quality

<img width="1134" height="253" alt="Screenshot 2026-08-11 094647" src="https://github.com/user-attachments/assets/61b64948-88e5-483c-b6ab-81f7a352936b" />

Main database tables

<img width="1136" height="407" alt="Screenshot 2026-08-11 094830" src="https://github.com/user-attachments/assets/775614c9-7d33-407e-b3ae-ffb994770d3d" />

Dataset information

<img width="981" height="483" alt="Screenshot 2026-08-11 094946" src="https://github.com/user-attachments/assets/e3b9a962-728c-4025-8220-c9a965d9af07" />

CREATE TABLE

<img width="570" height="510" alt="Screenshot 2026-08-11 043932" src="https://github.com/user-attachments/assets/2e9fd494-db77-4a80-a478-02a20ee5d35d" />

<img width="857" height="598" alt="Screenshot 2026-08-11 044037" src="https://github.com/user-attachments/assets/bf14b686-6494-4b92-9953-f2eb1c0277f7" />

<img width="745" height="530" alt="Screenshot 2026-08-11 044109" src="https://github.com/user-attachments/assets/e21cafb5-9b30-4c9c-8665-e1f7ce5189ce" />

<img width="886" height="266" alt="Screenshot 2026-08-11 044123" src="https://github.com/user-attachments/assets/31adc03d-2d26-4dfd-86be-70f53eb2b310" />

ALTER TABLE

<img width="1174" height="293" alt="Screenshot 2026-08-11 044828" src="https://github.com/user-attachments/assets/0178c118-e0c2-4358-b5cd-ce801301e8df" />

<img width="1153" height="279" alt="Screenshot 2026-08-11 044926" src="https://github.com/user-attachments/assets/413b6fe4-3eb4-45a6-a412-832e3217430a" />

Views

A view saves a frequently used join as a reusable virtual table

<img width="535" height="375" alt="Screenshot 2026-08-11 045828" src="https://github.com/user-attachments/assets/d78e548e-a44d-42e3-a3da-2558d7e6ca82" />

<img width="511" height="327" alt="Screenshot 2026-08-11 050358" src="https://github.com/user-attachments/assets/fa8a8689-1049-4296-91c6-02f5790c0ef5" />

Stored procedures

Benefits:
• Reusable logic
• Controlled access point
• Less repeated SQL

<img width="563" height="219" alt="Screenshot 2026-08-11 051207" src="https://github.com/user-attachments/assets/9dbe02a3-0872-4515-a562-3daeed7df12d" />

<img width="455" height="215" alt="Screenshot 2026-08-11 051228" src="https://github.com/user-attachments/assets/d82f8331-1de9-4c73-a856-ca352374585c" />

DISTINCT

Use DISTINCT to return each patient city once.

Useful for filter lists and data-quality checks.

<img width="338" height="322" alt="Screenshot 2026-08-11 051527" src="https://github.com/user-attachments/assets/037c4ec1-063d-4cd9-9abc-f9e8022daa6c" />

WHERE

WHERE filters rows before reporting.

<img width="529" height="357" alt="Screenshot 2026-08-11 052105" src="https://github.com/user-attachments/assets/6ec2d442-9584-4cea-894c-43df1433f86d" />

<img width="980" height="250" alt="Screenshot 2026-08-11 052141" src="https://github.com/user-attachments/assets/f997e992-37dd-459f-b262-ca87074d74ae" />

GROUP BY

Groups payments by status so the hospital can compare settled and outstanding value.

<img width="803" height="290" alt="Screenshot 2026-08-11 052526" src="https://github.com/user-attachments/assets/bb87e29b-c102-4a36-82ae-c883fa3f09f9" />

HAVING

HAVING filters aggregate results after GROUP BY.

<img width="527" height="312" alt="Screenshot 2026-08-11 053340" src="https://github.com/user-attachments/assets/dfd2efdf-4cfd-4859-af31-495ff1b16184" />

ORDER BY 

Sorts the most recent appointments first.

LIMIT supports quick report previews.

<img width="565" height="357" alt="Screenshot 2026-08-11 053711" src="https://github.com/user-attachments/assets/d82de275-25d7-4247-9874-50d72a64fdfa" />

Subqueries

A subquery provides a value or set that the outer query can compare against

<img width="589" height="325" alt="Screenshot 2026-08-11 053944" src="https://github.com/user-attachments/assets/47806ffe-296b-4178-9bae-aafe1b0fc24d" />

COMMIT and ROLLBACK

<img width="481" height="181" alt="Screenshot 2026-08-11 054246" src="https://github.com/user-attachments/assets/efe1453d-0899-4246-b6fa-82d202919648" />

<img width="496" height="159" alt="Screenshot 2026-08-11 054253" src="https://github.com/user-attachments/assets/b8d4ce6f-6d30-463d-b79a-9e52de29c45b" />

Functions

Functions transform raw values into report-ready information.

Examples: CONCAT, ROUND, UPPER, COUNT, AVG.

<img width="639" height="386" alt="Screenshot 2026-08-11 054650" src="https://github.com/user-attachments/assets/efd6ce06-0df9-4e91-a34f-6ef175a21b93" />

















