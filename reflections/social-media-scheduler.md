# 🧠 Reflection – Social Media Scheduler

## 🎯 What Worked
- Multi-platform integration worked seamlessly after token refresh logic.
- Laravel Horizon managed queued jobs effectively.
- Vue.js dashboard provided a great UX for scheduling.

## ⚠️ Challenges
- Facebook API frequently changed endpoints, breaking integration.
- Reddit's rate-limiting forced a redesign of job scheduling.
- Managing OAuth tokens for multiple accounts became complex.

## ✅ Improvements
- Centralize token management as a **microservice**.
- Implement **retry policies** with better error classification.
- Add **message queue monitoring** for stuck jobs.

## 🧠 Key Takeaways
- **Third-party API volatility** can break apps; build with adaptability in mind.
- **Queue-first design** is critical for posting at scale.
