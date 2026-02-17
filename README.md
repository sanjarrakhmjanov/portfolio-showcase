# 🌐 7SR Portfolio Website

Modern full-stack portfolio website featuring a high-end animated frontend and a Django REST backend for contact handling with Telegram notifications and database storage.

🚀 **Live Demo:**  
https://sanjar-raximjonov.vercel.app/

---

## ✨ Features
- Animated hero section with interactive icon cloud
- Dark / Light theme toggle
- Projects, Skills, About, Contact sections
- Contact form with validation and rate-limiting
- Telegram notifications for new messages
- Message storage in database
- Responsive modern UI

---

## 🛠 Tech Stack
**Frontend**
- Next.js (App Router)
- TypeScript
- CSS Modules

**Backend**
- Django
- Django REST Framework
- PostgreSQL

**Infrastructure**
- Render, Vercel deployment
- Gunicorn
- WhiteNoise

---

## 📩 Contact API Example
POST `/api/contact/`

```json
{
  "name": "Sanjar",
  "email": "sanjar@gmail.com",
  "message": "Hello!"
}
