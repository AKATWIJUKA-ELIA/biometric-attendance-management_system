# Biometric Class Attendance and Tracking System (BCATS)

BCATS is a sophisticated, automated attendance management solution designed to replace traditional, manual attendance-taking methods in academic environments — specifically developed for **Bugema University**. The system aims to eliminate common issues such as time wastage during lectures, manual recording errors, and **"proxy attendance"** (where students sign in for absent peers).

## 📖 Overview

The system leverages **facial recognition technology** to automate the process of marking attendance. Instead of calling names or passing around a sign-in sheet, the system identifies students via their biometric data, ensuring that the person marking attendance is physically present in the classroom.

## 🚀 Core Features

- **Facial Recognition:** Automated attendance marking using biometric data to ensure physical presence.
- **Role-Based Access Control:** Distinct roles for Lecturers, Students, and Administrators with tailored capabilities.
- **Real-time Tracking:** Instant updates and monitoring of attendance statistics and history for both students and lecturers.
- **Tamper-proof Verification:** Biometric-based presence confirmation eliminates proxy attendance.

## 👥 Key User Roles

### 🎓 Lecturers
- Create and manage class sessions.
- Enroll students into specific courses.
- Generate detailed attendance reports to track student consistency.

### 🧑‍🎓 Students
- Register biometric facial data during an enrollment phase.
- Use the facial recognition interface to mark attendance for sessions.

### 🛡️ Administrators
- Oversee the entire system.
- Manage user accounts and access control.
- Generate high-level institutional reports.

## 🏆 Project Goals

- **Efficiency:** Reduce the time spent on administrative tasks at the start of every class.
- **Accuracy:** Provide a tamper-proof method of verifying student presence.
- **Transparency:** Give both students and lecturers real-time access to attendance statistics and history.

## 🛠️ Tech Stack

The project is built using a modern, reactive web stack:

- **Frontend:** [Next.js](https://nextjs.org/) with React, providing a fast, responsive Single Page Application (SPA) experience.
- **Backend & Database:** [Convex](https://www.convex.dev/), used as a reactive backend and database platform for real-time data synchronization.
- **AI/Biometrics:** [face-api.js](https://github.com/justadudewhohacks/face-api.js/) and [TensorFlow.js](https://www.tensorflow.org/js), which enable the browser to perform face detection and recognition locally.
- **Security:** Implements secure authentication using **JWT (JSON Web Tokens)** and encryption for biometric templates to ensure student privacy and data protection.

## 🏁 Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

## 📚 Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) — your feedback and contributions are welcome!

## 🌐 Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.