# 🏥 RK Health Management

### AI-Powered Smart Patient Appointment & Medication Reminder System

> An intelligent healthcare management platform that streamlines patient appointments, medication tracking, AI-generated health summaries, and secure health record management using modern web technologies and Artificial Intelligence.

---

## 🚀 Overview

RK Health Management is a full-stack AI-powered healthcare platform designed to simplify healthcare management for patients and healthcare providers. The system offers appointment scheduling, medication reminders, AI-assisted visit summaries, healthcare analytics, report generation, and secure patient record management through a responsive and user-friendly interface.

Built with scalability, security, and usability in mind, RK Health leverages cloud technologies, Artificial Intelligence, and RESTful APIs to deliver a seamless healthcare experience.

---

# ✨ Features

## 🔐 Authentication & Security

- Secure User Registration & Login
- JWT Authentication
- Password Encryption using bcrypt
- Protected API Routes
- Role-Based Access Control
- Secure Environment Configuration

## 📅 Appointment Management

- Schedule Appointments
- Update Appointments
- Cancel Appointments
- Calendar Integration
- Appointment History

## 💊 Medication Management

- Add Medications
- Edit Medication Schedules
- Smart Reminder System
- Medication Compliance Tracking
- Daily Medication Dashboard

## 🤖 AI Healthcare Assistant

Powered by **Groq LLaMA 3.3-70B**

- AI Visit Summaries
- Medical Report Simplification
- Follow-up Recommendations
- Medication Guidance
- Patient-Friendly Explanations

## 📊 Dashboard

- Health Statistics
- Upcoming Appointments
- Medication Overview
- Recent Activities
- AI Insights
- Quick Actions

## 📄 Report Management

Generate professional healthcare reports in:

- PDF
- CSV
- Excel

Includes:

- Appointment History
- Medication Records
- AI Health Summaries
- Activity Logs
- Personal Health Reports

## 👤 Profile Management

- Personal Information
- BMI Calculator
- Insurance Details
- Medical Conditions
- Allergy Records
- Emergency Contact Information

## 🔔 Notifications

- Medication Alerts
- Appointment Reminders
- System Notifications
- SMS Notifications (Twilio)

## 🌙 User Experience

- Responsive Design
- Dark & Light Theme
- Mobile Friendly
- Modern Dashboard
- Interactive UI

---

# 🏗️ System Architecture

```text
Frontend (HTML • CSS • JavaScript)

            │
            ▼

Node.js + Express REST API

            │
            ▼

JWT Authentication Middleware

            │
            ▼

Prisma ORM

            │
            ▼

Supabase PostgreSQL

            │
     ┌──────┼─────────────┐
     │      │             │
     ▼      ▼             ▼

 Groq AI  Twilio SMS  Google Calendar
```

---

# 💻 Technology Stack

## Frontend

- HTML5
- CSS3
- JavaScript (ES6+)
- Vite

## Backend

- Node.js
- Express.js

## Database

- PostgreSQL
- Supabase

## ORM

- Prisma ORM

## Authentication

- JWT
- bcrypt

## Artificial Intelligence

- Groq API
- LLaMA 3.3-70B Versatile

## Third-Party Services

- Google Calendar API
- Twilio SMS API

## Deployment

- GitHub
- Node.js Server
- Supabase Cloud

---

# 📁 Project Structure

```text
RK-Health-Management/

│
├── frontend/
│   ├── src/
│   ├── assets/
│   ├── components/
│   ├── pages/
│   ├── styles/
│   └── public/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── prisma/
│   ├── routes/
│   ├── services/
│   └── server.js
│
├── documentation/
│
├── README.md
│
└── package.json
```

---

# 🧩 Core Modules

## Authentication

- User Registration
- User Login
- JWT Authentication
- Protected Routes
- Logout

## Dashboard

- Healthcare Analytics
- Appointment Overview
- Medication Summary
- Activity Timeline
- AI Insights

## Appointment Management

- Create Appointment
- Edit Appointment
- Delete Appointment
- Calendar Integration

## Doctor Management

- Doctor Profiles
- Availability Management
- Appointment Allocation

## Medication Management

- Medication Scheduling
- Reminder Management
- Compliance Monitoring

## AI Summary

Generate intelligent healthcare summaries using:

- Appointment Details
- Doctor Notes
- Diagnosis
- Prescription
- Follow-up Instructions

Powered by **Groq LLaMA 3.3-70B**

## Reports

Export reports in:

- PDF
- CSV
- Excel

Includes:

- Appointment Reports
- Medication Reports
- AI Reports
- Activity Reports

---

# 🔒 Security Features

- JWT Authentication
- Password Hashing (bcrypt)
- Protected REST APIs
- Input Validation
- Environment Variables
- Secure Database Access
- Secure API Communication

---

# 🤖 Artificial Intelligence

RK Health integrates **Groq LLaMA 3.3-70B Versatile** to provide:

- AI Healthcare Summaries
- Follow-up Recommendations
- Medication Guidance
- Healthcare Insights
- Patient-Friendly Medical Reports

---

# 🗄️ Database

Supabase PostgreSQL with Prisma ORM

### Tables

- Users
- Doctors
- Appointments
- Medications
- AI Summaries
- Reports
- Notifications
- Activity Logs
- User Settings

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/Boyina-Gowri-Sankar/RK-HEALTH-MANAGEMENT.git

cd RK-HEALTH-MANAGEMENT
```

## Install Dependencies

### Frontend

```bash
cd frontend
npm install
```

### Backend

```bash
cd backend
npm install
```

---

# 🔑 Environment Variables

Create a `.env` file inside the backend folder.

```env
PORT=5000

DATABASE_URL=

DIRECT_URL=

JWT_SECRET=

SUPABASE_URL=

SUPABASE_ANON_KEY=

SUPABASE_SERVICE_ROLE_KEY=

GROQ_API_KEY=

TWILIO_ACCOUNT_SID=

TWILIO_AUTH_TOKEN=

TWILIO_PHONE_NUMBER=
```

---

# 🗄️ Prisma Setup

Generate Client

```bash
npx prisma generate
```

Run Migration

```bash
npx prisma migrate dev
```

---

# ▶️ Running the Project

### Backend

```bash
npm run dev
```

### Frontend

```bash
npm run dev
```

---

# 📸 Screenshots

| Module | Screenshot |
|----------|------------|
| Landing Page | docs/images/landing.png |
| Login | docs/images/login.png |
| Dashboard | docs/images/dashboard.png |
| Appointments | docs/images/appointments.png |
| Medications | docs/images/medications.png |
| AI Summary | docs/images/ai-summary.png |
| Reports | docs/images/reports.png |
| Profile | docs/images/profile.png |

---

# 🚀 Future Enhancements

- 📱 Mobile Application
- 👨‍⚕️ Doctor Portal
- 🏥 Hospital Management Dashboard
- 🎥 Video Consultation
- ⌚ Wearable Device Integration
- 📄 OCR Prescription Scanner
- 🎙 Voice Assistant
- 🚑 Emergency SOS
- 👨‍👩‍👧 Family Health Management
- 🧠 AI Disease Prediction

---

# 📚 Documentation

The project documentation includes:

- API Documentation
- Database Design
- Software Architecture
- Deployment Guide
- User Manual
- Security Documentation
- Testing Reports
- Developer Guide
- Final Project Report

---

# 👥 Development Team

| Name | Role |
|------|------|
| **Member 1** | Team Lead & Full Stack Developer |
| **Member 2** | Frontend Developer |
| **Member 3** | Backend Developer |
| **Member 4** | Database & API Developer |
| **Member 5** | AI Integration & Testing |

> Replace the member names with your actual team members.

---

# 🙏 Acknowledgements

Special thanks to:

- Groq AI
- Supabase
- Prisma ORM
- Twilio
- Google Calendar API
- Node.js
- Express.js
- PostgreSQL
- Vite
- GitHub

---

# 📄 License

This project is developed for **academic, educational, and research purposes**.

Licensed under the **MIT License**.

---

# ⭐ Support

If you found this project helpful, please consider giving it a **⭐ Star** on GitHub to support future development.

---

## 👨‍💻 Maintained By

**Boyina Gowri Sankar**

B.Tech Computer Science Engineering Student

AI • Full Stack Development • Cloud Computing • Healthcare Technology
