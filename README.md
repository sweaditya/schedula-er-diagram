This project represents an Entity Relationship (ER) Diagram for a Clinic Appointment Booking System.
It models how patients book appointments with doctors at clinics and how bookings are managed efficiently.

The system is designed to handle:

Patient information

Doctor details and specialization

Clinic details

Appointments

Booking status and relationships between all entities

🧩 Entities & Attributes
1️⃣ Patient

Represents users who book appointments.

Attributes:

Patient_ID (Primary Key)

Name

Contact_Info

Relationships:

A patient schedules appointments

A patient has bookings

2️⃣ Doctor

Represents medical professionals.

Attributes:

Doctor_ID (Primary Key)

Name

Specialization

Relationships:

A doctor conducts appointments

A doctor has bookings

3️⃣ Clinic

Represents healthcare centers where appointments take place.

Attributes:

Clinic_ID (Primary Key)

Name

Location

Relationships:

A clinic is associated with appointments

A clinic has bookings

4️⃣ Appointment

Represents a scheduled visit between a patient and a doctor.

Attributes:

Appointment_ID (Primary Key)

Date

Time

Relationships:

An appointment is scheduled by a patient

An appointment is conducted by a doctor

An appointment is associated with a clinic

An appointment is linked to a booking

5️⃣ Booking

Represents confirmation and status of an appointment.

Attributes:

Booking_ID (Primary Key)

Patient_ID (Foreign Key)

Doctor_ID (Foreign Key)

Clinic_ID (Foreign Key)

Appointment_ID (Foreign Key)

Status (Booked / Cancelled / Completed)

Relationships:

A booking belongs to one patient

A booking belongs to one doctor

A booking belongs to one clinic
