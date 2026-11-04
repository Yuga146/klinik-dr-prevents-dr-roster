# Klinik Dr. Prevents — Roster & Location Finder

A responsive, single-file web application built for **Klinik Dr. Prevents** to manage, track, and filter multi-branch medical staff rosters, shift allocations, and doctor duty locations across the network.

---

## 🌟 Key Features

* **Multi-Branch Network Support**: Covers all clinic branches including Sri Damansara (SD), Kepong (KP), Segambut (ST), Jalan Ipoh (JI), Damansara Jaya (DJ), SS15, PJ Old Town (PJOT), Bandar Puteri Puchong (BPP), Kota Kemuning (KK), and Taipan (TPN).
* **Smart Doctor Lookup & Multi-Filtering**: 
  * Search for any doctor to instantly pull up their upcoming shifts.
  * Dynamically filters results based on your selected **Branch** and/or **Date** criteria, or shows complete network-wide schedules when "ALL BRANCHES" and all dates are selected.
* **Shift Management & Roles**: Tracks Day shifts (`☀️`), Night shifts (`🌙`), and Standby / Locum notes (`⏳`).
* **Admin Portal & Security**: Secure admin mode protected by a secure master PIN gateway with decoy verification puzzles.
* **Persistent Storage**: Changes made in the admin portal are saved locally (`localStorage`) for seamless day-to-day updates.
* **Theme Customization**: Built-in toggle between a high-contrast Obsidian Slate/Charcoal dark theme and a soft warm cream light theme.

---

## 🚀 Live Preview / Usage

This application is designed as a **single-file frontend solution** (`index.html`), making it fully compatible with static hosting providers like **GitHub Pages**.

1. Clone or download the repository.
2. Open `index.html` directly in any modern web browser.
3. Use the top search bar to look up specific doctor rosters or toggle to Admin Mode to update shifts.

---

## 🔒 Admin Access
* Click **Admin Access** in the header.
* Enter your authorized master PIN to unlock shift creation, editing, and deletion capabilities.

---

## 💻 Tech Stack
* **HTML5 / CSS3** (Custom CSS Variables for dynamic theming)
* **Vanilla JavaScript** (ES6+, DOM manipulation, LocalStorage persistence)
* **FontAwesome Icons & Google Fonts** (Plus Jakarta Sans)

---

## 📄 License
Internal operational tool developed for Klinik Dr. Prevents. All rights reserved.
