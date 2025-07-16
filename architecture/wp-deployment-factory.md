```md
# 🏗 Architecture – WP Deployment Factory

## ✅ Overview
Automates WordPress site provisioning using **Docker**, **WP CLI**, and **GitHub Actions**.

---

## 🔍 Diagram
```

\[Developer CLI] → \[Docker Container] → \[WP CLI Automation] → \[Deployment to Host]

```

---

## 🔧 Components
- Docker containers for local dev
- WP CLI scripts for:
    - Install WordPress core
    - Activate default theme & plugins
- GitHub Actions workflow for:
    - Syncing repos
    - Deploying changes
```