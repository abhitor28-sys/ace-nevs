# Ace News 📰

An interactive, data-driven mobile web application specifically designed to streamline preparation for **UPSC (Union Public Service Commission)** and **MPSC (Maharashtra Public Service Commission)** aspirants. Built on top of robust no-code architecture, this app aggregates crucial current affairs, syllabus trackings, and news updates tailored for civil services examinations.

## 🚀 Live Application
You can access and test the live Progressive Web App (PWA) here:
👉 **[Launch Ace News Live App](https://immense-pear-0340.glide.page)**

---

## 📱 Project Overview
Civil services exams require strict, daily tracking of high-yield news events, editorial analyses, and curriculum milestones. **Ace News** solves the issue of information overload by organizing critical updates into structured, easy-to-digest daily feeds, making preparation highly efficient and mobile-friendly.

### Key Features
* **Curated News Feed:** Daily filtered updates relevant strictly to UPSC and MPSC general studies syllabi.
* **Syllabus Categorization:** Content tagged cleanly by subjects (e.g., Polity, History, Economics, Science & Tech).
* **Progress Tracking:** Interactive dashboards for aspirants to keep tabs on completed static and dynamic topics.
* **Bookmarks & Offline Reading:** Ability to save high-importance editorials for quick revision before exams.

---

## 🛠️ Architecture & Tech Stack
Because this app prioritizes rapid deployment, seamless data synchronization, and a mobile-first responsive layout, it leverages a modern cloud-hosted no-code stack:

* **Frontend & UI Assembly:** [Glide Apps Platform](https://glideapps.com)
* **Database & Relational Schema:** Glide Tables / Google Sheets (handles structured tables for News Articles, Subjects, Users, and Saved Bookmarks).
* **Hosting Infrastructure:** Managed secure cloud hosting provisioned globally by Glide PWAs.

---

## 📊 Database Architecture (Data Schema)
While the core compiled layout execution is managed natively by Glide, the operational relational data model consists of the following key tables:

1. **`Users Table`**
   * Fields: `User ID`, `Name`, `Email`, `Target Exam (UPSC/MPSC)`, `Subscription Date`.
2. **`Articles Table`**
   * Fields: `Article ID`, `Headline`, `Content Body`, `Category (Polity/Eco/etc.)`, `Source Link`, `Date Published`.
3. **`Bookmarks Table`**
   * Fields: `Bookmark ID`, `User ID` (Relational Link), `Article ID` (Relational Link), `Timestamp`.

---

## 🎨 Preview & Interface
*(Optional: You can take 2-3 screenshots of your app on your phone, upload them to this GitHub repository, and link them here using markdown code like this: `![App Screenshot](screenshot.png)`)*

---

## 👤 Author
* **GitHub Portfolio:** [@abhitor28-sys](https://github.com)
* **Project Type:** Personal Civil Services EdTech Tool

---
*Developed as a high-utility no-code case study for portfolio evaluation.*

