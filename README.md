
# 🌸 MotherMend: C-Section Recovery Assistant

MotherMend is a smart wound-monitoring assistant designed to support Rwandan mothers through C-section recovery. The solution consists of a mobile and web application powered by a Convolutional Neural Network (CNN) to assess wound images in real-time and guide users with healing advice or recommendations for medical attention.

---

## 🔗 GitHub Repository

📁 [https://github.com/esthermbanza/WoundTrack](https://github.com/Esther-Mbanzabigwi/Initial-Product_Mother_Mend.git)

---

## ⚙️ Project Setup

### 📦 Prerequisites

Ensure you have the following installed:

- Python 3.10+
- Node.js 18+
- npm or yarn
- Git
- Expo CLI (`npm install -g expo-cli`)
- SQLite
- Strapi (Headless CMS)

---

### 📱 Mobile Application (React Native + Expo)

```bash
cd frontend
npm install
npx expo start
```

Scan the QR code using the Expo Go app to launch on your phone.

---

### 🗂️ CMS Backend (Strapi)

```bash
cd backend
npm install
npm run develop
```

Access the Strapi admin panel at `https://wound-assitant-backend.onrender.com`

---

## 🎨 <![Diagram Circuit](<img width="1536" height="1024" alt="circuit diagram" src="https://github.com/user-attachments/assets/630d19fb-48b2-4e9e-aba3-e9ed1642b1fe" />
)


Designed in Figma and implemented in React Native. UI/UX prioritizes simplicity and clarity for mothers with low digital literacy.

**Main Screens Include:**

- Splash Screen
- Login & Registration
- Home Dashboard
- Upload Wound Photo
- Prediction Result Display
- Healing Tips Panel

📸 Figma Mockups:
<![Diagram Circuit](<<img width="1024" height="1024" alt="Mockup" src="https://github.com/user-attachments/assets/1396152f-4cb8-4a95-aa39-7975bad8e5d3" />
 />
)

---

## 🚀 Deployment Plan

| Component    | Platform     | Deployment Method      |
|--------------|--------------|------------------------|
| FastAPI API  |  Render      | Dockerized instance  |
| Strapi CMS   | Render       | PostgreSQL / SQLite DB |
| Mobile App   | Expo EAS     | Build for Android / iOS|

---

## 🎥 Live Demo

📹 **Video Duration**: 7 minutes  
🗓️ **Submitted**: July 19, 2025  
🔗 **Watch Here**: [YouTube Demo](https://www.youtube.com/watch?v=JpcSdBfA39s)

The video walks through:

- Logging in
- Uploading a wound photo
- Viewing AI prediction
- Navigating healing tips
- Using the CMS backend

---

## 📁 Project Structure

```
WoundTrack/
├── README.md
├── frontend/               # React Native App
├── backend/                # Strapi CMS Backend
├── model_api/              # FastAPI CNN Model
├── designs/                # Figma Mockups & Screenshots
│   └── 1bec10e9-mockup.png
├── video/                  # Demo video
│   └── woundtrack_demo.mp4
├── requirements.txt
└── .env.example
```

---

## 📝 Notes

> This project was submitted as a complete functional prototype (not just an MVP). All critical functionalities were tested and demonstrated. The app is fully operational across the AI backend, mobile frontend, and CMS.

---

## 👩‍💻 Author

Developed with heart by **Esther Mbanzabigwi** 🇷🇼  
2025 — for Rwandan mothers, for safer healing.

---

## 📬 Questions or Feedback?

Feel free to open an [Issue](https://github.com/esthermbanza/WoundTrack/issues) or reach out via the contact info in the GitHub profile.

---
