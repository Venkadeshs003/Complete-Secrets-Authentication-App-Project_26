# 🔐 Secrets Authentication App
now user can submit there own secret


A Node.js authentication app built with **Express.js, Passport.js, PostgreSQL, and EJS**.  
Users can **register, login, and authenticate** using **email-password (bcrypt) or Google OAuth 2.0**.  
Authenticated users can submit and view **secrets** securely.

---

## 🚀 Features
- User registration & login (local authentication with bcrypt)
- Google OAuth 2.0 authentication
- Secure session management with `express-session`
- PostgreSQL database integration
- Protected routes (`/secrets`) accessible only after login
- Submit and view secrets anonymously

---

## 🛠 Tech Stack
- **Node.js** & **Express.js**
- **PostgreSQL**
- **Passport.js** (Local + Google OAuth)
- **bcrypt** for password hashing
- **EJS** for templating

---

## ⚡ Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/secrets-auth-app.git
   cd secrets-auth-app
