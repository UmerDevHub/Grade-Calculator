<div align="center">
  <h1>🎓 COMSATS Grade Calculator & Degree Dashboard</h1>
  <p>A beautiful, highly interactive academic planning suite built specifically for COMSATS University Islamabad.</p>
</div>

---

## 🌟 Overview

The **COMSATS Grade Calculator** is a fully-featured, client-side web application designed to help university students track their academic progress seamlessly. Unlike generic GPA calculators, this suite is hard-coded with the **Official COMSATS 11-Tier Absolute Grading Scale** (A=4.00 down to F=0.00), ensuring mathematical accuracy for every calculation.

With a premium **SaaS-inspired UI**, Dark/Light mode persistence, and real-time calculation engines, students can instantly visualize their current standing and plan their academic future.

## ✨ Core Features

### 1. 📊 Advanced Grade Calculators
* **Full Course Calculator:** Calculates aggregate scores combining Theory (67%) and Lab (33%) weights, including exact breakdowns for Mids, Finals, Quizzes, and Assignments.
* **Theory-Only Calculator:** A streamlined calculator for non-lab courses.
* **Real-time Engine:** As you type your marks, the Animated Progress Ring instantly updates your predicted Grade and GPA without page reloads.
* **Target Predictor:** Type in the grade you *want* to achieve, and the engine will instantly tell you exactly how many marks you need on the Final Exam to get it!

### 2. 🎓 Comprehensive Degree Dashboard
* **Semester Tracking:** Add your current courses to a dynamic table to instantly calculate your Semester GPA.
* **True Degree CGPA:** Input your previous credits and previous CGPA. The dashboard automatically mathematically merges your past history with your current semester to reveal your true Overall Degree CGPA.
* **Probation Alerts:** A dynamic Status Badge actively monitors your True CGPA. It glows green for "Good Standing" and flashes red for "Probation Risk" if you drop below the COMSATS 2.0 minimum.
* **Target Degree Planner:** Type in your dream graduation CGPA. The planner will calculate the exact Semester GPA you must average *this* semester to hit your lifelong goal!

### 3. 💾 Secure Cloud Backup (Offline First)
Because the app is blazing fast and runs entirely in your browser's local storage (no backend required), we built an Export/Import system:
* **Export Data:** Download your entire dashboard history (courses, past CGPA, and targets) as a secure `.json` file.
* **Import Data:** Clear your cache, or switch to your mobile phone, and upload the `.json` file to instantly restore your entire dashboard exactly as you left it.

## 🛠️ Technology Stack

This application is built for maximum performance and zero-dependency portability:
* **Architecture:** Pure HTML5
* **Styling:** Vanilla CSS3 (Custom Grid/Flexbox Layouts, Glassmorphism, CSS Variables)
* **Logic & State:** Vanilla JavaScript (ES6+), DOM Manipulation, `localStorage` API
* **Animations:** Canvas Confetti (CDN), Custom SVG Progress Rings

## 🚀 How to Run

1. Clone or download this repository.
2. Double-click **`index.html`** to open the Course Calculator in any modern web browser.
3. Use the top navigation bar to seamlessly switch between the Course Calculator, Theory Calculator, and Degree Dashboard.
4. *No `npm install`, Node.js, or local servers required!*

---
*Developed with a focus on premium UI/UX and accurate mathematical modeling for CUI students.*
