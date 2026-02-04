This project represents an Entity Relationship (ER) Diagram for a Clinic Appointment Booking System.
It models how patients book appointments with doctors at clinics and how bookings are managed efficiently.

The system is designed to handle:

Patient information

Doctor details and specialization

Clinic details

Appointments and booking status

📊 ER Diagram

Below is the ER diagram illustrating entities, attributes, and relationships:

Note: The diagram shows how Patient, Doctor, Clinic, Appointment, and Booking entities are connected.

🧩 Entities & Attributes
Patient

patient_id (Primary Key)

name

contact_info

Doctor

doctor_id (Primary Key)

name

specialization

Clinic

clinic_id (Primary Key)

name

location

Appointment

appointment_id (Primary Key)

date

time

Booking

booking_id (Primary Key)

patient_id (Foreign Key)

doctor_id (Foreign Key)

clinic_id (Foreign Key)

appointment_id (Foreign Key)

status

🔗 Relationships

A Patient schedules an Appointment

A Doctor conducts an Appointment

A Clinic is associated with Appointments

A Booking links Patient, Doctor, Clinic, and Appointment

Each Booking has a status (Booked / Cancelled / Completed)

🎥 ER Diagram Explanation (Video)

I have explained the ER diagram in detail using a Loom video:

👉 Watch here:
https://www.loom.com/share/cc88931b597c42fdbf005c9a84ffd712



## Author
Aditya Sharma
## Version
v1.0
