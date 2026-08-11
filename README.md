<div align="center">

# 🏋️‍♂️ Gyma Btal - Gym Management System
**Smart Management & Subscription System for Fitness Centers**

[![HTML5](https://img.shields.io/badge/Frontend-HTML5%20%7C%20CSS3%20%7C%20JS-orange)](#)
[![Database](https://img.shields.io/badge/Database-Google%20Sheets%20API-green)](#)
[![Theme](https://img.shields.io/badge/Theme-Dark%20%26%20Gold-yellow)](#)
[![Languages](https://img.shields.io/badge/Languages-Arabic%20%7C%20English-blue)](#)

---

</div>

## 📌 Overview
**Gyma Btal** is a comprehensive web-based management application tailored for gyms and fitness centers. It simplifies member tracking, daily attendance/check-ins, and financial reporting. Built with a modern Dark Gold UI and full Arabic interface support, it utilizes **Google Sheets API** as a flexible and lightweight cloud database backend.

---

## 🌐 Languages & Internationalization

* **UI Language:** Arabic (RTL support for intuitive user experience in Arabic-speaking environments).
* **Code & Documentation:** English (Clean, readable code structure, comments, and documentation).

---

## ✨ Key Features

### 1. 👥 Member & Subscription Management
* **Member Profiles:** Register and update member information (Full Name, Phone Number, Workout Type, Weight, Age, Subscription Duration, and Amount Paid).
* **Automated Expiry Calculation:** Automatically computes start and end dates upon selecting subscription terms.
* **Status Tracking:** Real-time badge indicators (`Active` | `Expiring Soon` | `Late` | `Expired`).
* **Smart Search & Filter:** Quick search by name and one-click filtering based on subscription status.

### 2. ⏱️ Daily Attendance & Quick Check-Ins
* Streamlined check-in/check-out workflow for active members and quick daily visitors.
* Real-time search with exact timestamp logging down to the second.
* Records visit types and collected fees instantly.

### 3. 📊 Financial Reports & Revenue Dashboard
* **Financial Dashboard:** Displays total collected subscription fees and daily visit earnings.
* **Expense Ledger:** Logs general operational expenses and calculates net profit automatically.
* **Member Analytics:** Tracks total registered athletes and monthly financial trends.

---

## 🛠️ Tech Stack & Languages

* **Programming & Scripting Languages:** JavaScript (ES6+), HTML5, CSS3, Apps Script (Google Apps Script / JavaScript-based)
* **Frontend:** Vanilla JavaScript, Modern CSS3 Flexbox/Grid
* **Database / Backend:** Google Sheets API (via Google Apps Script Web App)
* **Local Data Management:** IndexedDB / LocalStorage for smooth offline performance and client-side persistence

---

## 📐 Database Architecture (Google Sheets Setup)

The application communicates with a Google Sheet structured into the following tables:

| Sheet Name | Description |
| :--- | :--- |
| `Members` | Stores core member details, subscription dates, and status. |
| `Attendance` | Logs daily check-in/check-out timestamps and visit types. |
| `Finance` | Tracks total revenues, operational expenses, and net profit. |

---

## 🚀 Getting Started

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/your-username/gym-management-system.git](https://github.com/your-username/gym-management-system.git)
