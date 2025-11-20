# Entity-Relationship-Diagram-for-Hospital-Management System
 **Hospital ERD Project**

This repository contains the Entity Relationship Diagram (ERD) for a Hospital Management System, designed as part of the course assignment IDS Fundamentals.

** Project Overview**

The goal of this project is to design a structured ERD that represents how data is stored and managed inside a hospital management system.
The ERD helps visualize the entities, their attributes, and the relationships between various components such as hospitals, departments, doctors, and patients.

Entities Included
1. Hospital

Reg No

Name

Address (City, Province, Street)

Email Address

2. Department (Dept)

Internal Phone No

Staff

Location

Department Type (ED, ICU, IPD, OR, Special Wards)

3. Doctor

Doctor ID

First Name

Last Name

Phone No

Date of Birth

Specialization

4. Patient

MR No

First Name

Last Name

Gender

Blood Type

Date of Birth

Phone No

Address (Permanent & Current)

🔗 Relationships

Hospital → Department: One-to-Many

Department → Doctor: one-to-Many (Doctors work in department)

Doctor → Patient: Many-to-Many (Doctors treat multiple patients)

Department → Patient: One-to-Many (Patients admitted to departments)

ERD Diagram

The ERD was designed using Canva.

🔗 Canva Link (View Only):
(https://www.canva.com/design/DAG5PMHCKxQ/5w1YwU3uXe2ncbn8sONYVA/edit?utm_content=DAG5PMHCKxQ&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

ERD Image:
The PNG/JPG file of the diagram is also uploaded in this repository under /images/ or root.

Project Documentation

A detailed explanation of this ERD, including diagrams and project description, is provided in the PDF file included in this repository.

👨‍💻 Designed By

Sayed Ehsanullah Majeed (4592-FOC/BSSE/F23)

Mohmmad Fahim Rafizadah (4594-FOC/BSSE/F23)

Huzaifa Jahid (4593-FOC/BSSE/F23)
