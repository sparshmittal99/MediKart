# 💊 MediKart - Online Medicine Ordering App

MediKart is a full-stack web application that enables users to order medicines online and get reminders for timely intake. The system includes secure authentication, intuitive navigation, order tracking, and a customizable notification system.

---

## 🚀 Tech Stack

| Layer        | Technology       | Version |
|--------------|------------------|---------|
| Frontend     | Angular          | 17+     |
| Backend      | NestJS (Node.js) | 10+     |
| Database     | PostgreSQL       | 14+     |
| Authentication | JWT            | ✓       |
| Notifications | Node Cron       | ✓       |

---

## ✨ Features

- Secure user registration and login using JWT
- Browse available medicines and place orders
- Set custom daily or weekly medicine intake reminders
- Fully responsive and user-friendly Angular UI
- Admin APIs for managing inventory (optional)

---

## 📁 Project Structure

medikart/
├── backend/
│ ├── src/
│ │ ├── modules/
│ │ │ ├── auth/
│ │ │ ├── medicine/
│ │ │ └── reminder/
│ │ ├── config/
│ │ └── main.ts
│ ├── .env
│ └── package.json
├── frontend/
│ ├── src/
│ │ ├── app/
│ │ │ ├── components/
│ │ │ │ ├── auth/
│ │ │ │ └── dashboard/
│ │ │ ├── services/
│ │ │ └── guards/
│ ├── angular.json
│ └── package.json
└── README.md


---

## ⚙️ Installation & Running

### 📦 Backend (NestJS)

#### Prerequisites:
- Node.js v18+
- PostgreSQL 14+

#### Steps:

1. Navigate to backend:
   cd backend

2. Install dependencies:
   npm install

Create .env file and set the following:

dotenv

DB_HOST=localhost
DB_PORT=5432
DB_NAME=medikart
DB_USER=your_pg_username
DB_PASS=your_pg_password
JWT_SECRET=your_secret
Start the server:


npm run start:dev
Backend will run at http://localhost:3000.

🖥️ Frontend (Angular)
Prerequisites:
Node.js 18+

Angular CLI 17+

Steps:
Navigate to frontend:


cd frontend
Install dependencies:


npm install
Run the development server:


ng serve
Frontend will run at http://localhost:4200.


