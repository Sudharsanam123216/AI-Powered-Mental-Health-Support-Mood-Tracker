# AI-Powered Mental Health Support & Mood Tracker

## 📌 Problem Statement

In today's fast-paced world, mental health issues such as stress, anxiety, and depression are increasing rapidly among students and working professionals. Most people do not seek professional help due to social stigma, lack of awareness, or financial constraints.

Existing mental health applications mainly provide meditation or breathing exercises without personalized support. There is a need for an intelligent platform that tracks daily mood patterns, detects early signs of mental health issues, and provides AI-powered personalized support.

This project aims to develop a dedicated AI-powered platform that monitors daily moods, analyzes emotional patterns, and offers personalized mental health assistance.

---

## 🎯 Objectives

### Primary Objectives
- Track daily mood and emotional patterns.
- Analyze mood data using AI.
- Detect stress, anxiety, and depression signs early.
- Provide personalized mental health suggestions.
- Connect users with professional therapists.
- Ensure privacy and data security.
- Send daily mood reminders.
- Provide 24/7 AI chatbot support.
- Generate weekly and monthly mood reports.

### Secondary Objectives
- Reduce mental health stigma.
- Improve emotional well-being.
- Provide guided meditation and breathing exercises.
- Build community-based support.
- Make mental health services affordable and accessible.

---

## 📖 Project Overview

The AI-Powered Mental Health Support & Mood Tracker is a full-stack web application that helps users monitor their emotional health, identify mood trends, and receive personalized AI-driven support.

Users can:
- Log daily moods
- Maintain personal journals
- Receive AI-generated insights
- Access therapist support
- Use an AI chatbot for emotional assistance

The system includes:
1. User Portal
2. Therapist Portal
3. Admin Portal

---

## 🧩 Modules

### Module 1: User Authentication
- Registration & Login
- JWT Authentication
- Role-Based Access Control
- Anonymous Mode
- Session Management

### Module 2: Daily Mood Tracker
- Mood Check-in (1–10 Scale)
- Emotion Selection
- Journal Entry
- Voice Notes
- Reminder Notifications

### Module 3: AI Mood Analysis
- Mood Pattern Detection
- Stress Prediction
- Anxiety Prediction
- Depression Risk Analysis
- Trend Reports

### Module 4: AI Chatbot Support
- 24/7 Emotional Support
- Personalized Suggestions
- Guided Meditation
- Crisis Detection
- NLP-Based Conversations

### Module 5: Therapist Connect
- Therapist Search
- Appointment Booking
- Video Consultation
- Chat Support
- Ratings & Reviews

### Module 6: Wellness Activities
- Meditation Sessions
- Breathing Exercises
- Gratitude Journal
- Sleep Tracking
- Positive Affirmations

### Module 7: Notifications
- Daily Mood Reminders
- Motivational Messages
- Appointment Alerts
- Emergency Notifications
- Weekly Progress Updates

### Module 8: Analytics Dashboard
- Mood History
- Stress Trends
- Sleep Reports
- Activity Analysis
- Progress Tracking

### Module 9: Admin Dashboard
- User Management
- Therapist Management
- Analytics Monitoring
- Content Management
- Emergency Case Handling

### Module 10: Community Support
- Anonymous Groups
- Peer Chat Rooms
- Mental Health Resources
- Success Stories
- Wellness Challenges

---

## 🗄️ Database Tables

| S.No | Table Name | Description |
|------|------------|-------------|
| 1 | Users | User Information |
| 2 | MoodLog | Daily Mood Records |
| 3 | AIAnalysis | AI Predictions |
| 4 | Therapist | Therapist Details |
| 5 | Appointment | Appointment Records |
| 6 | ChatHistory | Chatbot Conversations |
| 7 | WellnessActivity | Wellness Activities |
| 8 | Notification | Alerts & Reminders |
| 9 | Community | Community Posts |
| 10 | Admin | Admin Information |

---

## 🏗️ ER Diagram Structure

### Users
- user_id (PK)
- name
- email
- phone
- age
- gender
- password
- created_at

### MoodLog
- log_id (PK)
- user_id (FK)
- mood_score
- emotion_type
- journal_text
- voice_note_url
- logged_at

### AIAnalysis
- analysis_id (PK)
- user_id (FK)
- stress_level
- anxiety_level
- depression_risk
- suggestions
- analyzed_at

### Therapist
- therapist_id (PK)
- name
- email
- specialization
- experience_years
- rating
- availability

### Appointment
- appointment_id (PK)
- user_id (FK)
- therapist_id (FK)
- appointment_date
- appointment_time
- status

### ChatHistory
- chat_id (PK)
- user_id (FK)
- message
- response
- sentiment_score

### Admin
- admin_id (PK)
- name
- email
- password

---

## 💻 Technology Stack

### Frontend
- HTML5
- CSS3
- Bootstrap 5
- React JS
- Chart.js
- Axios

### Backend
- Java
- Spring Boot
- Spring Security
- JWT Authentication
- REST APIs
- Python
- Flask API

### Database
- MySQL
- MongoDB
- Hibernate ORM

### AI & Machine Learning
- Python
- Scikit-learn
- NLP
- Sentiment Analysis
- Mood Prediction Models

### Tools
- Git
- GitHub
- Postman
- IntelliJ IDEA
- VS Code
- Maven

---

## 🏛️ System Architecture

```text
User Portal (React)
        │
        ▼
Spring Boot REST API
        │
 ┌──────┴──────┐
 ▼             ▼
MySQL       MongoDB
        │
        ▼
Python Flask AI API
        │
 ┌──────┴──────┐
 ▼             ▼
Mood Analysis  AI Chatbot
