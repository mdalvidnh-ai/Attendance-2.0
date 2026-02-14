# Student Attendance Tracker (SAT V1.0) 📊

**SAT V1.0** is a professional, mobile-first Progressive Web App (PWA) designed for teachers and educators to manage student attendance efficiently, even without an internet connection.



## 🚀 Key Features

-   **Offline-First:** Works anywhere, anytime using Service Workers and IndexedDB.
-   **Mobile-First Design:** Optimized for one-handed use in the classroom.
-   **Excel/CSV Integration:** Import your class list in seconds with fuzzy header matching.
-   **Professional Exports:** Generate print-ready PDF reports and data-rich Excel sheets.
-   **Backup & Restore:** Never lose data. Export your entire database to a JSON file.
-   **Smart Sorting:** Automatically sorts students numerically by Roll Number.
-   **PWA Ready:** Install it directly on your Android or iOS home screen.

## 🛠️ Tech Stack

-   **Frontend:** Tailwind CSS (UI), FontAwesome (Icons), Google Fonts (Poppins).
-   **Database:** Dexie.js (Wrapper for IndexedDB).
-   **Logic:** Vanilla JavaScript (ES6+).
-   **Libraries:** SheetJS (Excel), jsPDF & AutoTable (PDF).

## 📂 Installation & Setup

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/yourusername/attendance-tracker.git](https://github.com/yourusername/attendance-tracker.git)
    ```
2.  **Files Required:**
    - `index.html`: The main app logic and UI.
    - `manifest.json`: PWA configuration.
    - `sw.js`: Service worker for offline caching.
    - `icon.png`: App icon (512x512 recommended).

3.  **Deployment:**
    Upload these files to **GitHub Pages** or any HTTPS-enabled web host.

## 📖 How to Use

### 1. Initial Setup
Go to the **Setup Tab**, click **Import Class List**, and upload your CSV/Excel file. Ensure your file has headers like `Roll No`, `Student Name`, and `Gender`.

### 2. Daily Tracking
Select the date, then tap **P** (Present) or **A** (Absent). The app saves every change instantly to your device. Use the **Mark All P** button to speed up the process on full-attendance days.

### 3. Monthly Reports
Switch to the **Monthly Tab** to see the full grid. Enter the number of holidays to get an accurate attendance percentage. Export the data using the **Excel** or **PDF** buttons.

### 4. Backing Up
Regularly use the **Backup Data** button in the Setup tab. This saves a `.json` file of your entire history which you can restore if you change devices or clear your browser cache.

## 🛡️ Privacy
All data is stored **locally on your device**. No student information is ever sent to a server, ensuring 100% data privacy and security.

---
*Created with ❤️ for Educators.*