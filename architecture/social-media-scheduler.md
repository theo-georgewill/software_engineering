```md
# 🏗 Architecture – Social Media Scheduler

## ✅ Overview
A SaaS-style application for scheduling posts to **Facebook** and **Reddit**, using token-based authentication and queued jobs for API posting.

---

## 🔍 System Diagram
```

\[Vue.js Frontend] ←→ \[Laravel Backend API] ←→ \[Facebook/Reddit API]
\|                      |
(JWT Session)         (OAuth2 Token Store)
|
\[MySQL DB]
|
\[Queue System] (Horizon)

```

---

## 🔧 Core Services
- **Scheduler Engine**
    - Stores posts and schedule metadata
- **API Integration Layer**
    - Handles token refresh & API posting
- **Job Queue**
    - Manages scheduled post dispatch
- **Dashboard**
    - Built in Vue.js with Pinia for state

---

## 🔐 Security
- OAuth2 for Facebook & Reddit
- Encrypted storage for tokens
- Role-based access for multi-user

---

## 📈 Scaling Plan
- Offload scheduling engine to Redis-based workers
- Implement caching for API-heavy operations
```