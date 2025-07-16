# 🧠 Reflection – Bookr Booking System

## 🎯 Successes
- Conflict-free booking logic worked well under high concurrency.
- Role-based access control improved security and usability.
- Email notifications reduced no-shows by 40% (client feedback).

## ⚠️ Challenges
- Time zone handling was complex, especially for multi-location businesses.
- Managing overlapping schedules required extra DB constraints.

## ✅ Future Enhancements
- Add **calendar sync (Google Calendar, iCal)**.
- Build **analytics dashboard** for usage metrics.
- Introduce **real-time availability** with WebSockets.

## 🧠 Lessons
- **Domain modeling** is critical for time-based systems.
- Always test with **edge cases** (e.g., daylight savings).
