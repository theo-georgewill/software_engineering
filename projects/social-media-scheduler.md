# 📆 Social Media Scheduler

## 📌 Overview
A **Laravel-powered scheduling tool** for posting content across **Facebook** and **Reddit** with full **OAuth2 token management** and **Laravel Queues** for async posting.  

---

## 🎯 Problem
Clients managing multiple social accounts struggled with inconsistent posting and platform API complexity.

---

## ✅ Solution
- **Multi-Account OAuth Integration** (Facebook Graph API + Reddit API)
- **Token Auto-Renewal** to keep sessions alive
- **Queued Scheduling** using Laravel Horizon
- **Post Retry Mechanism** for failed API calls

---

## 🛠 Technical Highlights
- **API Integration:** Facebook & Reddit OAuth2
- **Scheduling Engine:** Laravel Queues + Jobs
- **Error Handling:** Logging & fallback retries
- **Vue.js Dashboard:** Post preview, scheduling calendar
- **Role Management:** Basic user control & permissions

---

## ⚙️ Tech Stack
- Laravel, Vue.js, TailwindCSS, Pinia  
- MySQL, Horizon for queues  
- Facebook Graph API, Reddit API  

---

## 🧠 Lessons Learned
- Handling **rate limits** and **API failure states**
- Building a **queue-driven workflow** for async reliability
