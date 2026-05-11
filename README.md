# meal-muse
A browser-based healthy meal planner with multi-user auth, weekly calendar, and dashboard stats
# 🥗 Meal Muse — Healthy Meal Planner

A browser-based meal planning app built with vanilla HTML, CSS, and JavaScript.
Plan your weekly meals, track your schedule, and never miss a meal time.

## ✨ Features
- User signup and login with per-user data isolation
- Add, edit, delete, and search meals
- Weekly calendar view organized by day
- Dashboard with live stats — meals today, next meal, weekly total
- Meal reminders via toast notifications
- Export your meal plan as a CSV file
- Password strength indicator and show/hide toggle
- Fully responsive — works on mobile and desktop

## 🚀 How to Run
No installation needed.
1. Download or clone this repository
2. Open `index.html` in any browser
3. Sign up and start planning

## 🛠 Built With
- HTML5
- CSS3 (Flexbox, CSS Grid, custom animations)
- Vanilla JavaScript (ES6+)
- localStorage for client-side data persistence

## ⚠️ Known Limitations
- Frontend-only authentication — passwords are stored in localStorage (no backend)
- Data is browser-specific — logging in from another device won't show your meals
- In a production app I would add a Node.js/Express backend with a real database and hashed passwords

## 🔮 Future Improvements
- Backend with Node.js + PostgreSQL
- Calorie and nutrition tracking per meal
- Browser push notifications for reminders
- Mobile app version
