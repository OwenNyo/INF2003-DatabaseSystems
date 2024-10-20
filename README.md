# 🏥 E-Doc Healthcare Management System

This project, *E-Doc*, is a digital healthcare management platform developed for the **INF2003 - Database Systems** course. It streamlines healthcare processes by allowing users to book appointments, track vital health metrics, and manage medications, all through a centralized platform.

## 📜 Project Overview

### E-Doc Features:
- **Appointment Scheduling**: Users can book and manage doctor appointments.
- **Health Metrics Tracking**: Patients can log and monitor vital signs such as blood pressure and blood sugar.
- **Medical Records Management**: Doctors can access patient health histories and issue medical certificates.
- **Medication Tracking**: The system stores and tracks prescribed medications and dosage details.

## 🛠️ System Design

The E-Doc system is built using:
- **Flask Web Framework**: The backend serves as the interface for handling user interactions.
- **SQLite3 Database**: A lightweight, serverless database is used for managing user data, appointments, health metrics, and medical history.
- **Python**: Handles backend logic, with `sqlite3` for database interactions and `bcrypt` for secure password handling.

## 🏗️ Database Schema

The system comprises several key tables:
- **Users**: Stores user details such as name, role (patient/doctor), and contact information.
- **Appointments**: Manages the scheduling of appointments with doctors.
- **Clinic Schedule**: Tracks available time slots for appointments.
- **User Health**: Logs patient health metrics like blood pressure and blood sugar.
- **Medical History**: Stores detailed records of patient visits, doctor notes, and prescribed medications.
- **Medical Certificates**: Tracks certificates issued to patients.

## 🔐 Security Features
- **User Authentication**: Secure login with hashed passwords using `bcrypt`.
- **Role-based Access Control (RBAC)**: Doctors and patients have different levels of access.
- **Session Management**: User sessions ensure personalized and secure access to the system.

## 🚀 Future Improvements
- **Scalability**: The system is currently using SQLite, but future iterations could migrate to MySQL or PostgreSQL for larger datasets.
- **Real-Time Data Visualization**: Future improvements could involve real-time health metric tracking using dynamic charting libraries like Plotly.

## 📋 Team Members
- Owen Nyo Wei Yuan
- Tan Yan An
- Ong Hong Liang
- Rayner Tan Jian Wen
- Kerwin Loh

## 📝 Repository
The source code for this project is available [here](https://github.com/OwenNyo/INF2003-DatabaseSystems).
