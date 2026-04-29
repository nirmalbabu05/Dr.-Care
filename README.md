# 🏥 Dr. Care - Smart Hospital Management System
  
## 🚀 Overview

**Dr. Care** is a 100% cloud-connected, paperless, and real-time clinic management ecosystem. It completely eliminates crowded waiting rooms by providing patients with live queue tracking and seamlessly connects all hospital departments through specialized, role-based portals using a high-performance, serverless architecture.

**Demo Website**
https://drcare2026.netlify.app/

## ✨ Key Features

* ⏱️ **Live Queue Tracking:** Patients can view their exact wait times, token numbers, and live queue status directly from their mobile portal.
* 👨‍⚕️ **Role-Based Workspaces:** Dedicated operational terminals for Admin (CMS control), Reception (Walk-ins), Nurse (Triage vitals), Doctor (Consultation & E-Prescriptions), and Pharmacy (Dispensing & Receipts).
* 🔒 **Patient E-Vault:** A secure digital vault for patients to access their past prescriptions and medical certificates anytime.
* 📺 **Bilingual Smart TV Lounge:** A high-tech digital signage system for the clinic waiting area featuring automated Voice Paging (English & Tamil), rotating health tips, and a Live Weather widget.
* 📱 **Dynamic QR Kiosk:** Instantly generates a live "Scan to Book" QR code on the TV screen linking directly to the clinic's booking portal.
* 💎 **Enterprise UI/UX:** Built with modern CSS variables, Bento grid layouts, Glassmorphism design principles, and custom keyframe animations.

## 🛠️ Tech Stack

**Frontend**
* HTML5 & CSS3 (Glassmorphism & Complex Grid Layouts)
* Vanilla JavaScript (ES6+, DOM Manipulation & State Management)
* Phosphor Icons & Google Fonts ('Plus Jakarta Sans')

**Backend & Database**
* Google Firebase (Realtime Database via ES Modules for millisecond syncing)

**APIs & Microservices**
* Web Speech API (Automated Bilingual Voice Announcements)
* Open-Meteo API (Live Local Temperature/Weather)
* QR Server API (Dynamic Booking Link Generation)

**Deployment**
* Netlify (Fast, secure cloud hosting)

## 💻 Running the Project Locally

### 📦 Installation

Since this project utilizes a serverless architecture with Firebase, setting it up locally is incredibly fast. Follow these steps:

**1️⃣ Clone the repository**
```bash
git clone [https://github.com/yourusername/Dr-Care-Clinic.git](https://github.com/yourusername/Dr.-Care.git)
cd Dr.-Care
```

**2️⃣ Open the project in your favorite editor**
```bash
code .
```

**3️⃣ Start a local development server**
If you are using VS Code, simply install the **Live Server** extension and click "Go Live" on `index.html`. Alternatively, you can use Python:
```bash
python -m http.server 8000
```

**4️⃣ Open the project in your browser at:**
```text
http://localhost:8000/
```

## 📜 License

This project is for educational and portfolio purposes, aimed at demonstrating a real-world, real-time Hospital Management System using modern framework-free web technologies and cloud databases.

Made with ❤️ by Nirmal Babu V M
