# AttendEase – SRKR Engineering College 🎓

**AttendEase** is a modern, responsive Permission and Attendance Management web portal designed for students and faculty of **SRKR Engineering College, Bhimavaram**. It streamlines student permission requests for hackathons, internships, medical leave, and academic events.

---

## 🌟 Key Features

- **Personalized Student Dashboard**: Displays student identity, roll number, department, semester, and attendance permission overview.
- **Permission Request Workflow**:
  - Modal form to submit new requests for:
    - 🏆 **Hackathons & Competitions**
    - 💼 **Internships & Industry Training**
    - 🏥 **Medical Leave**
    - 📋 **Other Academic Reasons**
  - Period selection (e.g., Period 1–2, 1–4, Full Day).
  - Document attachment support for proof verification (PDF, JPG, PNG).
- **Request Tracking**: Real-time status badges (e.g., `APPROVED`, `PENDING FACULTY`).
- **Helpline & Technical Support**:
  - Integrated contact directory for project coordinators, system architects, and developers.
  - Direct dial, WhatsApp chat integration, and one-click email copying.
- **Interactive Profile Card**: Floating card detailing student branch, section, semester, and roll number.
- **Mobile-First & PWA-Ready**:
  - Optimized for mobile and desktop screens.
  - Safe-area inset support for modern smartphones (notch/home indicator).
  - Clean bottom navigation bar (Home, Notifications, History, Profile).

---

## 🛠️ Tech Stack

- **Core**: Semantic HTML5 & Modern Vanilla JavaScript (ES6+)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) (JIT CDN)
- **Typography**: [Google Fonts](https://fonts.google.com/) (*Outfit*, *Plus Jakarta Sans*, *Inter*)
- **Icons**: Inline SVGs & [Google Material Symbols](https://fonts.google.com/icons)

---

## 🚀 Getting Started

No build step or external package installation is required.

### 1. Clone or Download
Ensure all assets remain in the root directory:
```
attendease/
├── index.html        # Main application page
├── logo.svg          # AttendEase brand logo
├── profile.jpg       # Student profile picture
└── README.md         # Project documentation
```

### 2. Run Locally

You can serve the application using any static HTTP server:

#### Option A: Python (Recommended)
```bash
python -m http.server 5500
```
Open **[http://localhost:5500](http://localhost:5500)** in your browser.

#### Option B: Node.js / npx
```bash
npx serve -l 5500
```

#### Option C: VS Code Live Server
Right-click `index.html` in VS Code and select **"Open with Live Server"**.

---

## 👥 Project Team & Contacts

- **Chundru Gowtham Krishna** – *System Architect & Lead Developer*
- **Chandani Vivekananda** – *Full-Stack Developer & UI/UX*
- **K. V. Sunil Varma** – *AttendEase Project Coordinator*

---

## 📄 License & Attribution

© 2026 **AttendEase • SRKR Engineering College, Bhimavaram**. All rights reserved.
