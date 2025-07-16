# 🏗 Architecture – ClientSync CRM

## ✅ Overview
ClientSync integrates with **HubSpot CRM** via OAuth2 for lead synchronization and provides a custom pipeline dashboard for local business users.

---

## 🔍 High-Level Architecture

```

\[React Frontend] ←→ \[Laravel API] ←→ \[HubSpot API]
\|                   |
(JWT Auth)         (OAuth2)
\|                   |
\[MySQL DB]        \[Queue Workers]

```

---

## 🔧 Key Components
- **Frontend (React)**
    - Pipeline visualization
    - Lead management forms
- **Backend (Laravel)**
    - REST API for React
    - OAuth2 token management
    - Webhook receiver for HubSpot updates
- **Database**
    - MySQL for leads, activities, tokens
- **Asynchronous Processing**
    - Laravel Horizon queues for:
        - Contact sync jobs
        - Webhook handling
- **Notifications**
    - Email reminders for follow-ups

---

## 🔐 Security
- OAuth2 for HubSpot API
- Signed webhook validation
- Rate limiting for internal API routes
- Laravel CSRF protection for dashboard

---

## 📈 Scalability
- Use **queue workers** for all API sync tasks
- Horizontal scaling for web + queue servers
- Database indexing for search-heavy tables
```
