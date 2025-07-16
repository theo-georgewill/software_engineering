# 🗂️ ClientSync CRM

## 📌 Overview
ClientSync is a lightweight **Customer Relationship Management (CRM) system** built to help professionals manage leads, automate follow-ups, and synchronize data with **HubSpot CRM**.  

It demonstrates **API integration**, **OAuth2 token lifecycle management**, **webhooks**, and **asynchronous job handling** — core skills in modern SaaS architecture.  

---

## 🎯 Problem
Nigerian surveyors and SMEs lacked structured tools for lead tracking, resulting in poor follow-up and lost revenue. Manual processes were unreliable, and third-party CRMs were too complex or expensive.

---

## ✅ Solution
A streamlined CRM with:
- **Lead Pipeline** – Track stages (New → In Progress → Closed)
- **HubSpot Integration** – Sync contacts & deals via OAuth2
- **Email Automation** – Follow-up reminders & notifications
- **Activity Dashboard** – Pipeline insights for better decisions

---

## 🛠 Technical Highlights
- **OAuth2 Authentication** with HubSpot API  
- **Queue-Based Sync Jobs** using Laravel Horizon  
- **Webhook Handling** for real-time updates from HubSpot  
- **Email Notification System** with Laravel Mail  
- **Role-Based Access Control (RBAC)** for team users  
- **Data Persistence** with Eloquent ORM and migrations  

---

## ⚙️ Tech Stack
- **Backend:** Laravel  
- **Frontend:** React (React Router + Bootstrap)  
- **Database:** MySQL  
- **Integrations:** HubSpot API, OAuth2  
- **Deployment:** GitHub Actions → DigitalOcean  

---

## 🖼 Screenshots
*(Add UI mockups or dashboard screenshots)*

---

## 🧠 Lessons Learned
- Designing **async-safe API sync** using queues & retries
- Managing **OAuth2 token refresh logic**
- Building scalable CRM architecture with Laravel’s modular design

---

## 🔗 Repo
[github.com/theo-georgewill/clientsync-alpha](#)
