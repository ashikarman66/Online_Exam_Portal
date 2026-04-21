# Online Examination System

A web‑based platform that allows registered students to take multiple‑choice quizzes (exams) in a timed environment. The system includes user registration/login, an exam engine with a 60‑second per question timer, automatic scoring, and an administrative panel for managing questions and users.

---

## Features

### Student/user Features
- User registration with duplicate email detection
- Secure login (MD5 hashed – to be upgraded)
- Timed exam: 60 seconds per question
- Automatic progression to next question on timer expiry
- Manual “Next Question” button
- Automatic score calculation
- Final score display
- View correct answers after exam

### Admin Features
- Separate admin login panel
- Add new questions (with 4 answer choices)
- View all questions in a list
- Delete questions (cascades to associated answers)
- Manage users: enable, disable, or delete accounts

---

## Technology Stack

| Layer          | Technologies                                   |
|----------------|------------------------------------------------|
| **Frontend**   | HTML5, CSS3, JavaScript (jQuery for AJAX)      |
| **Backend**    | PHP 7.4+ (procedural with MySQLi)              |
| **Database**   | MySQL (phpMyAdmin)                             |
| **Server**     | Apache (XAMPP)                                 |
| **Testing**    | Chrome, Firefox, Apache JMeter                 |

---

## System Architecture


- **Presentation layer:** HTML/CSS/JS, timer, AJAX requests  
- **Logic layer:** PHP classes handle registration, login, exam flow, admin actions  
- **Data layer:** MySQL stores users, questions, answers  

---

## Installation

### Prerequisites
- XAMPP (or any Apache + PHP + MySQL stack)
- PHP 7.4 or higher
- MySQL 5.7 or higher

### Steps

1. **Clone or download the project** into your web server’s document root.
   ```bash
   git clone https://github.com/your-repo/online-examination-system.git


The application follows a classic **three‑tier architecture**:
