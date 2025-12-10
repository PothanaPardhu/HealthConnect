
🚑 HEALTH CONNECT
AI-Enabled Healthcare System Built with Django
📌 Overview

The Digital Prescription & Medicine Availability Platform is a full-stack healthcare system that replaces manual prescriptions with secure digital prescriptions, helps patients locate medicines across nearby pharmacies, and provides an AI assistant for prescription analysis, reminders, and appointment support.

The platform connects Doctors, Patients, and Pharmacies into a unified digital ecosystem to ensure faster treatment, improved accessibility, and smarter healthcare decisions.

🎯 Key Objectives

Remove dependency on handwritten prescriptions

Provide a digital and centralized prescription history

Show real-time medicine availability across nearby medical shops

Help pharmacies manage stock easily

Provide AI-assisted support for patients

Enable appointment management & reminders

Increase safety by reducing fake/incorrect medicines

✨ Key Features
👨‍⚕️ Doctor Module

Create and upload digital prescriptions

Manage patient prescription history

Schedule appointments

Automatic email updates sent to patients

🧑‍⚕️ Patient Module

Access all prescriptions anytime, anywhere

Search medicines across nearby pharmacies

Get alerts when medicines are available

AI chatbot explains prescription details

Set and manage medicine reminders

Book doctor appointments

🏪 Pharmacy Module

Update and manage medicine stock

Real-time availability displayed to users

Dashboard to track stock and orders

🤖 AI Assistant

Understands uploaded prescriptions

Explains medicine usage & dosage

Sets reminders for patients

Helps with appointment bookings

Flags suspicious or fake-looking prescriptions/medicines

🔔 Notification System

Prescription email alerts

Medicine intake reminders

Appointment notifications

🏗️ System Architecture

The system follows a modular and secure architecture:

1️⃣ Frontend Layer

User dashboards for doctor, patient, pharmacy

Chatbot interface

Prescription upload UI

2️⃣ Backend Application (Django)

Prescription management

Stock management

Search engine for medicine availability

AI analysis handler

Authentication & role-based access

3️⃣ Database Layer

User accounts (Doctor/Patient/Pharmacy)

Digital prescriptions

Pharmacy stock database

Appointment & reminder tables

4️⃣ Integration Layer

Email notification APIs

Google Gemini AI (for prescription analysis & chatbot)

🧠 How It Works

Doctor uploads a prescription → Stored securely

Patient logs in → Views their history of prescriptions

Patient searches for medicine → System scans pharmacy databases

Nearby shops with stock appear

AI assistant analyzes prescription → Provides explanation + reminders

Pharmacies update stock → Shown in real-time

Reminders & notifications keep the patient on track

Appointments can be set & notified via email

🛠️ Tech Stack
Backend

Django

Python

Frontend

HTML, CSS, Bootstrap, JS

AI Integration

Google Gemini API

Database

SQLite / PostgreSQL

Other Services

Email/Notification Services

📂 Project Structure

myproject/
│
├── doctor/
│   ├── migrations/
│   ├── static/
│   ├── templates/
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
│
├── hello/
│   ├── migrations/
│   ├── static/
│   │   ├── image1.png
│   │   ├── image2.png
│   │   ├── image3.png
│   │   └── image4.png
│   ├── templates/
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
│
├── medicalshop/
│   ├── migrations/
│   ├── static/
│   ├── templates/
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
│
├── user/
│   ├── migrations/
│   ├── static/
│   ├── templates/
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
│
├── myproject/
│   ├── __pycache__/
│   ├── __init__.py
│   ├── asgi.py
│   ├── config.example.py
│   ├── config.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── static/
│
├── .env
├── db.sqlite3
├── manage.py
├── requirements.txt
├── README.md
├── venv/
└── .gitignore



🚀 Installation & Setup
git clone https://github.com/PothanaPardhu/HealthConnect.git
cd myproject
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

🖼️  UI SCREENS 

  HOME PAGE 
  <img width="1280" height="1063" alt="image" src="https://github.com/user-attachments/assets/6d80fefc-5740-4268-8bc5-8b2375c86193" />

  DOCTOR'S DIGITAL PRESCRIPTION GENERATOR
 <img width="797" height="1280" alt="image" src="https://github.com/user-attachments/assets/a331910e-f7ee-452b-9af9-1341e6a56d00" />

  USERS INTERFACE TO SEARCH MEDICINES AND THEIR AVAILABILITY IN REGISTERED PHARMACIES
  <img width="1280" height="841" alt="image" src="https://github.com/user-attachments/assets/3ed41c4e-1399-4a1a-a674-3944be9bb72b" />

  PHARMACIES/ MEDICINE SHOPS UI TO UPDATE THEIR MEDICINE STOCK 
  <img width="1280" height="788" alt="image" src="https://github.com/user-attachments/assets/35b5af26-b8b5-4d61-a074-7b8074776d7f" />

  PRESCRIPTION UPLOAD AND ANALYSER 
  <img width="1280" height="757" alt="image" src="https://github.com/user-attachments/assets/743dd6fd-2bde-4e7f-9bee-c8ddc53e7c91" />

  ANALYZED PRESCRIPTION 
  <img width="1136" height="1280" alt="image" src="https://github.com/user-attachments/assets/93fd0add-cd11-42e3-b9ef-a40ff0c96ab3" />

  CHATBOT FOR USERS 
  <img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/939d5483-7e0b-4cc0-93d6-de337367e8a3" />

  DOCTOR APPOINTMENT BOOKING UI 
  <img width="1280" height="608" alt="image" src="https://github.com/user-attachments/assets/10a0c26e-4cfd-42c8-bee8-5a47e6a646ec" />

  MEDICINE REMINDER SET UI 
  <img width="1280" height="608" alt="image" src="https://github.com/user-attachments/assets/e4b51ac2-e538-49f0-a664-14654c22a6b4" />


🔮 Future Enhancements

Mobile app (Android/iOS)

Integration with real pharmacy APIs (Apollo, MedPlus, Tata 1MG)

Live location-based pharmacy mapping

Blockchain-secured prescription verification

AI-based disease prediction from prescription patterns

Medicine delivery integration

Voice-enabled AI assistant

👥 Team

Pothana Pardhu

Merugu Venkatsai

Kasaraboina Srinu

Puppireddy Vishwateja

Mandala Sai Charan Reddy


⭐ Why This Project Matters

This platform solves real healthcare challenges:

✔ Prevents lost prescriptions
✔ Saves patient time by showing real-time medicine availability
✔ Helps pharmacies manage stock transparently
✔ Supports patients with AI-based guidance
✔ Creates a unified, digital healthcare ecosystem
