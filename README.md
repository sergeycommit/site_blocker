# SiteBlocker

**SiteBlocker** is a modern and aesthetic extension for Google Chrome that helps you maintain focus and productivity by blocking distracting websites.

Designed using **Google Material Design 3** principles, ensuring a comfortable and pleasant user experience.

## ✨ Key Features

### 🛡️ Two Operation Modes
*   **Simple Mode**:
    *   Maximum convenience with no extra steps.
    *   Settings are changed without password confirmation.
    *   Ideal for those who want to gently correct their habits.
*   **Strict Mode**:
    *   Full protection of settings with a password.
    *   You cannot disable blocking or delete a site without entering the password.
    *   Suitable for strict control and fighting procrastination.

### 🚫 Smart Blocking
*   Blocking by exact domain or subdomains.
*   Instant redirection to a motivational page when attempting to access a blocked site.
*   Automatic suggestion to add the current site to the blocklist.

### 📂 Categories and Groups
*   Create categories (e.g., "Social Media", "Entertainment", "Work").
*   Combine sites into groups for bulk schedule management.

### 📅 Flexible Schedule
*   **Personal Site Schedule**: Configure blocking for a specific resource (e.g., YouTube only in the evening).
*   **Category Schedule**: Apply a rule immediately to the entire group (e.g., block all "Games" during working hours Mon-Fri from 9:00 to 18:00).
*   Visual weekly editor with convenient time slot selection.

### 🔐 Security and Recovery
*   Master Password protection (in Strict Mode).
*   Access recovery option via a secret code word if you forget your password.

## 🚀 Installation

Since this is an extension for developers/local use (not from the Chrome Web Store):

1.  **Download** the project source code to your computer.
2.  Open the Chrome browser and navigate to: `chrome://extensions/`
3.  In the top right corner, toggle on **"Developer mode"**.
4.  Click the **"Load unpacked"** button.
5.  Select the folder containing the project files.
6.  Done! The SiteBlocker icon will appear in the extensions panel.

## 📖 How to Use

1.  **First Launch**:
    *   Select a mode: "With password" or "Without password".
    *   If you selected "With password", create a strong password and a recovery code word.
2.  **Adding Sites**:
    *   Open the extension.
    *   In the "Sites" tab, enter the address (e.g., `vk.com`) and press Enter.
    *   Alternatively, just open the extension while on the site you want to block — the address will be pre-filled automatically.
3.  **Setting up Schedule**:
    *   Click the ⚙️ (Settings) icon next to the site or category.
    *   Select "Schedule" and define blocking days and hours.
4.  **Managing Modes**:
    *   You can go to Settings (gear icon in the header) at any time to switch the protection mode.

## 🛠 Technologies

*   HTML5, CSS3 (Vanilla + CSS Variables).
*   JavaScript (ES6+).
*   Chrome Extensions API (Manifest V3).
*   Chrome Storage Sync (for syncing settings between devices).

---
*Be productive with SiteBlocker!*
