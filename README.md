# TEND - Mental Health Assistant App

## 📱 Project Description
**TEND** is a mobile application designed as a mental health assistant that helps users track their emotional well-being, daily habits, and personal reflections.

---

## 📋 Workshop 1 Deliverables

### 1. System Requirements
**File:** `workshop1.pdf`

**Functional Requirements:**
- Secure user registration (email, social media, biometrics)
- Daily mood tracking with colors/emojis
- Habit monitoring (sleep, nutrition, exercise)
- Personal journal with password protection
- Custom notifications and reminders
- Progress statistics with charts
- Connection with mental health professionals

**Non-Functional Requirements:**
- Maximum security: encrypted data and secure authentication
- Intuitive interface (max 3 steps for main functions)
- 24/7 availability with auto-save
- Response time < 2 seconds

### 2. User Stories

| Function | Purpose | Acceptance Criteria |
|----------|---------|---------------------|
| Registration | Manage personalized progress | Secure registration and profile setup |
| Reminders | Maintain good habits | Configurable and automatic notifications |
| Personal Journal | Reflect and express feelings | Text/images/audio with secure locking |
| Emotion Control | View trends over time | Habit tracking and visual calendar |

### 3. Interface Mockups

**Main screens designed:**
- **Login/Registration:** Secure app access
- **Main Screen:** Calendar with daily color indicators
- **Daily Registration:**
  - Emotions (feeling selection)
  - Sleep (hours slept)
  - Nutrition (daily meals)
- **Analysis:** Daily summary with recommendations

### 4. CRC Cards (Class-Responsibility-Collaborator)

**Main classes identified:**
- **Usuario:** Handles authentication and profile
- **GestorEmociones:** Records moods and habits
- **DiarioPersonal:** Manages journal entries
- **MotorRecomendaciones:** Suggests activities based on patterns
- **GestorEstadísticas:** Generates reports and charts
- **ComunicacionProfesionales:** Connects with specialists
