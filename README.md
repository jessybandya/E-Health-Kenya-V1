
# 🏥 E-Health Kenya V1

🔗 **Live Site**: [https://e-health-kenya.web.app/](https://e-health-kenya.web.app/)  
🔐 **Super Admin Login**  
- **Email**: jessy.bandya5@gmail.com  
- **Password**: 87654321


🔗 **Demo Video**: [Link](https://unsa-feng.uonbi.ac.ke/backend/storage/media/images/20250411-2019-07.3252762.mp4)  


An intelligent, AI-powered hospital management system that automatically assigns patients to doctors based on arrival time and urgency level. Designed to enhance healthcare delivery in Kenya, the system includes role-based dashboards and GPT-powered support.

📁 **GitHub Repo**: [github.com/jessybandya/E-Health-Kenya-V1](https://github.com/jessybandya/E-Health-Kenya-V1)

---

## 📌 Overview

This system empowers healthcare institutions to:

- Automatically triage and assign patients
- Prioritize urgent cases
- Support multi-role operations (Admin, Doctor, Pharmacist, Lab Tech, Receptionist)
- Integrate AI for smart assistance

---

## 🎯 Core Features

### 🔐 Multi-Dashboard Roles

| Role             | Capabilities                                                                 |
|------------------|------------------------------------------------------------------------------|
| **Super Admin**  | Manage users: doctors, patients, pharmacists, lab techs, receptionists       |
| **Doctor**       | View assigned patients, diagnose, update treatment                           |
| **Receptionist** | Register patients, tag urgency level, assign to queue                        |
| **Lab Technician**| Receive lab test requests, upload results                                   |
| **Pharmacist**   | View prescriptions, confirm medicine dispensing, manage inventory            |

### 🤖 AI Integration

- GPT-powered assistant for patient support
- Flask API for chatbot interaction
- Female voice text-to-speech enabled
- Node.js for SMTP/email notifications

---

## 🛠 Tech Stack

| Technology     | Usage                          |
|----------------|--------------------------------|
| ReactJS        | Frontend interface             |
| PHP + MySQL    | Backend APIs & database        |
| Node.js        | SMTP (email) notifications     |
| Flask          | AI module (GPT integration)    |
| GPT/LLaMA      | Natural language understanding |

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/jessybandya/E-Health-Kenya-V1.git
cd E-Health-Kenya-V1
```

### 2. Backend (PHP + MySQL)

- Install XAMPP / WAMP / LAMP
- Import the provided `database.sql` into MySQL
- Configure DB credentials in `/backend/config.php`

### 3. Node.js Server (SMTP)

```bash
cd node-server
npm install
node index.js
```

### 4. Flask Server (AI - GPT)

```bash
cd ai-flask
pip install -r requirements.txt
python app.py
```

### 5. React Frontend

```bash
cd frontend
npm install
npm start
```

---

## 📡 API Documentation
So many endpoints that I cannot put them here all due to time is limited for submission

---

---

## 🎥 Demo & Presentation

📽 **[View PowerPoint Presentation]([https://your-link.com](https://unsa-feng.uonbi.ac.ke/backend/storage/media/images/20250411-2019-07.3252762.mp4))**  
🖼️ Screenshots
![image](https://github.com/user-attachments/assets/d87c09c7-b57e-4bfb-b119-43aef9f2eef1)
![image](https://github.com/user-attachments/assets/abb7d9a6-a4ee-4028-a4b2-8c86d0fc3c0a)
![image](https://github.com/user-attachments/assets/12cbdc4d-1711-4896-93a0-a6fa18ec6944)
![image](https://github.com/user-attachments/assets/5fe3349f-3283-46b7-9886-23671e3b189c)
![image](https://github.com/user-attachments/assets/8af0ac65-181f-4a23-bdd2-773c72c4dc49)
![image](https://github.com/user-attachments/assets/e7b04de3-f08f-4d17-b05a-7dbe3701bbba)
![image](https://github.com/user-attachments/assets/c8bb50c9-a62e-4fd7-bf9d-2d8d2994e556)
![image](https://github.com/user-attachments/assets/2ebc4fb5-8e54-44a9-a3d7-9c4d818b11b1)
![image](https://github.com/user-attachments/assets/c77a91e7-3f41-4da8-b5f3-b2ea293869a9)
![image](https://github.com/user-attachments/assets/6b7bd081-1306-48c8-900d-742ccedfa0f2)
![image](https://github.com/user-attachments/assets/2097acd4-a00b-497a-b429-79724fd8c06d)
![image](https://github.com/user-attachments/assets/0723362b-bf5a-4953-b2b3-b4937de755de)








---

## 📁 Folder Structure

```
E-Health-Kenya-V1/
├── backend/             # PHP API + DB configs
├── frontend/            # React app (6 dashboards)
├── node-server/         # Node.js SMTP server
├── ai-flask/            # Flask + GPT AI module
├── assets/              # Images, diagrams, PowerPoint
└── README.md
```

---

## 👨‍💻 Author

**Jessy Bandya**  
Full-Stack Web & Mobile Engineer | AI-Powered Healthcare Advocate  
🟢 [GitHub](https://github.com/jessybandya) • 🌐 [e-health-kenya.web.app](https://e-health-kenya.web.app/)

---

> Built for Kenya, inspired by compassion and powered by innovation.
```
