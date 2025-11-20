# 📱 Attendance Pro

**Attendance Pro** is a lightweight, mobile-first web application designed for teachers and students to take attendance quickly and efficiently. It features a modern "Tinder-style" swipe interface, a classic grid view, and comprehensive reporting tools—all contained in a **single HTML file**.

> **Live Demo:** [Insert your GitHub Pages link here]

## ✨ Features

*   **🔄 Serial Mode (Swipe):** Take roll calls one by one with a large, distraction-free interface. Tap to mark Present/Absent.
*   **▦ Grid Mode:** View all students at once. Toggle status with a single tap.
*   **⌨️ Manual Entry:** Type a roll number (supports alphanumeric like `2023-C-3`) to quickly mark specific students.
*   **📋 Instant Reporting:** Generates a formatted text report (Subject, Date, Time, List of Roll Nos) ready to copy-paste into WhatsApp or Email.
*   **⚙️ Fully Customizable:**
    *   Add/Remove Subjects.
    *   Add Custom/Temporary Time Slots.
    *   Add new Roll Numbers on the fly with the floating `+` button.
*   **💾 Auto-Save:** Uses Browser LocalStorage. Your data persists even if you close the browser or refresh the page.
*   **📱 Android-First Design:** Optimized for mobile screens with app-like navigation and smooth animations.

## 🚀 How to Use

### 1. Hosting (Recommended)
To use this on your phone, host it for free using GitHub Pages:
1.  Upload `index.html` to a GitHub repository.
2.  Go to **Settings** > **Pages**.
3.  Select the `main` branch and save.
4.  Open the generated link on your phone and "Add to Home Screen".

### 2. Local Use
Simply download the `index.html` file and open it in any web browser (Chrome, Safari, Firefox). No installation required.

## 📖 User Guide

### The Tabs
1.  **Serial:** The "Tinder" mode. Shows one roll number at a time.
    *   **Green Button / Right:** Mark Present.
    *   **Red Button / Left:** Mark Absent.
2.  **Grid:** A scrollable overview of all students. Green = Present, Red = Absent.
3.  **Manual:** Type a roll number to quickly mark them. Useful for latecomers.
4.  **Result:**
    *   Select Subject, Date, and Time.
    *   Choose to list **Present** or **Absent** students.
    *   Click the **Copy Icon** to grab the formatted text.

### Settings & Customization
*   Click the **Hamburger Menu (☰)** in the top right.
*   **Manage Subjects:** Add or delete course names.
*   **Roll Numbers:** Add single rolls or generate a batch range. Supports letters and special characters.
*   **Time Slots:** Configure your default class timings.
*   **Quick Add:** In Serial or Grid mode, tap the **Floating + Button** to instantly add a new student to the list.

## 🛠️ Tech Stack

*   **Framework:** [Vue.js 3](https://vuejs.org/) (CDN) - For reactive state management.
*   **Styling:** [Tailwind CSS](https://tailwindcss.com/) (CDN) - For UI and responsive design.
*   **Icons:** Material Icons Round.
*   **Architecture:** Single-File HTML (No build steps, no Node.js required).

## 📝 Default Configuration

The app comes pre-loaded with specific defaults (as per requirements):
*   **Roll Nos:** Includes standard numbers (63-126, 300s, 600s) and alphanumeric formats (e.g., `2023-C-3`).
*   **Time Slots:** Standard hourly slots from 9:00 AM to 5:00 PM.

*To reset these to factory settings, go to Settings > Scroll down > **Restore Default Settings**.*

## 📄 License

This project is open-source. Feel free to modify and distribute it for your own use.
