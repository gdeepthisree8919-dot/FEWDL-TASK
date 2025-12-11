# FEWDL-TASK
# EcoHero — Gamified Sustainability Web App (Pastel Theme)

EcoHero is a lightweight, browser-based web application designed to encourage sustainable living through **gamified eco-friendly challenges**. Users can complete tasks, earn points, unlock badges, and track their progress — all in a clean, pastel-themed interface.

This project works completely offline and stores data using **localStorage**, making it ideal for academic projects, demos, or beginner-friendly web development learning.

---

## 🌱 Project Overview

EcoHero motivates users to adopt environmentally responsible habits by breaking them into small challenges. The platform provides:

* A list of eco-challenges
* Points and achievement badges
* Progress tracking with leaderboard previews
* Custom challenge creation
* Social sharing support

The UI uses soft **pastel colors** to match an eco-friendly, minimal, and modern aesthetic.

---

## 🎯 Features

### **Core Functional Requirements**

* **Display sustainability challenges** (daily/weekly style)
* **Track user completion status**
* **Award points & badges** for completed tasks
* **Responsive UI** (desktop + mobile)
* **Leaderboard preview** for motivation

### **Optional Enhancements (Included)**

* Add **custom challenges** (user-generated tasks)
* Display **eco-tips & resources**
* Enable **social sharing** of achievements
* Simple **project report modal** inside the app

---

## 🛠️ Tech Stack

* **HTML5** — Structure
* **CSS3** — Pastel theme styling & responsive layout
* **JavaScript (Vanilla JS)** — App logic, progress tracking, UI updates
* **LocalStorage** — Persistence

No frameworks or backend services are required.

---

## 📂 Project Structure

This version is a **single-file web application**:

```
index.html  ← contains HTML, CSS, and JS
```

If needed, the project can be split later into separate CSS/JS files.

---

## 🚀 How to Run

1. Download or copy the `index.html` file.
2. Open the file in any modern browser:

   * Chrome
   * Edge
   * Firefox
   * Safari
3. The app loads instantly — no server required.

Your progress is automatically saved in **localStorage**.

---

## 🧩 Key Features Explained

### **1. Challenges System**

Users see a predefined list of eco-friendly actions. Each challenge includes:

* Title
* Description
* Point value
* Completion button

Completing a challenge updates the UI and increases points.

### **2. Custom Challenges**

Users can add their own tasks by entering:

* Title
* Description (optional)
* Point value

### **3. Achievements (Badges)**

Badges are awarded automatically when reaching:

* **50 points** → Bronze Hero
* **150 points** → Silver Steward
* **300 points** → Green Champion

### **4. Leaderboard Preview**

Shows top performers + your updated score.

### **5. Social Sharing Support**

Uses the Web Share API where available, otherwise falls back to clipboard.

### **6. Project Report Modal**

A built-in summary explaining:

* Introduction
* Features
* Gamification strategy
* Future improvements

---

## 📱 Responsive Design

The layout adapts for:

* Wide desktop screens (two-column layout)
* Tablets
* Mobile screens (stacked layout)

Pastel visuals and rounded components improve readability and aesthetics.

---

## 📘 Possible Extensions

If you want to expand this project, consider adding:

* **Firebase authentication**
* **Real-time leaderboard database**
* **Daily rotating challenges**
* **Push notifications for reminders**
* **Animated progress bars**
* **Seasonal challenge campaigns**

---

## 🧪 Testing

Manually test the following:

* Adding and completing challenges
* Undoing completion
* Badge unlock logic
* Leaderboard updates
* Sharing functionality
* Reset data option

LocalStorage can be inspected in browser devtools.

---

## 📄 License

This project can be used for:

* Academic submissions
* Personal learning
* Portfolio projects

Feel free to modify and distribute.

---

## 🙌 Acknowledgements

Created as part of a sustainability-focused software project to demonstrate:

* Front-end UI development
* Gamification concepts
* User-centric design practices

---


