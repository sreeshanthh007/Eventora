# 🎉 Eventora

Eventora is a full-stack **Event Management & Service Booking Platform** that enables users to plan events, book services, and manage vendors efficiently.  
The project is built using **MERN + TypeScript** and follows **Clean Architecture** principles to ensure scalability, maintainability, and testability.

---

## ✨ Features

### 👤 Users
- Register and authenticate securely
- Browse and book event services
- Manage event bookings
- Real-time updates and notifications

### 🧑‍💼 Vendors
- Register and manage services
- Manage Event & Services
- View and respond to Booked Services

### 🛠 Admin
- Manage users and vendors
- Approve and control services
- Monitor platform activity

### ⚡ Real-Time
- Real-time communication support

---

## 🏗 Tech Stack

### Frontend (Client)
- React.js
- TypeScript
- Vite
- Tailwind CSS
- Redux / Context API

### Backend (API)
- Node.js
- Express.js
- TypeScript
- MongoDB
- JWT Authentication
- Socket.IO

### Architecture & Tools
- Clean Architecture
- Docker & Docker Compose
- ESLint
- Git & GitHub

---

## 📁 Monorepo Structure

```text
eventora/
│
├── client/                         # Frontend (React + TypeScript)
│   ├── src/
│   │   ├── api/                    # API calls
│   │   ├── assets/                 # Images & static assets
│   │   ├── components/             # Reusable UI components
│   │   ├── contexts/               # React Contexts
│   │   ├── hooks/                  # Custom hooks
│   │   ├── lib/                    # Helper libraries
│   │   ├── protected/              # Protected routes/components
│   │   ├── routes/                 # Application routing
│   │   ├── services/               # Business logic & API services
│   │   ├── store/                  # State management
│   │   ├── types/                  # TypeScript types
│   │   ├── utils/                  # Utility functions
│   │   ├── App.tsx
│   │   └── main.tsx
│   │
│   ├── public/
│   ├── .env
│   ├── .env.example
│   ├── package.json
│   └── vite.config.ts
│
├── api/                            # Backend (Node.js + Express)
│   ├── src/
│   │   ├── entities/               # Enterprise business rules
│   │   ├── useCases/               # Application business rules
│   │   ├── interfaceAdapters/      # Controllers & presenters
│   │   ├── frameworks/             # DB, server, external services
│   │   ├── shared/                 # Shared utilities & constants
│   │   └── app.ts                  # App entry point
│   │
│   ├── logs/
│   ├── Dockerfile
│   ├── docker-compose.yml
│   ├── .env
│   ├── .env.example
│   ├── package.json
│   └── tsconfig.json
│
├── .gitignore
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/sreeshanthh007/Eventora.git
cd Eventora
```

---

### 2️⃣ Setup Backend (API)
```bash
cd api
npm install
```

Create a `.env` file inside `api/`:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

Run backend:
```bash
npm run dev
```

---

### 3️⃣ Setup Frontend (Client)
```bash
cd ../client
npm install
npm run dev
```

Frontend:
```
http://localhost:5173
```

Backend:
```
http://localhost:3000
```



## 🎯 Project Highlights

- Clean Architecture implementation
- Scalable monorepo setup
- Strong separation of concerns
- Real-time features with Socket.IO
- Production-ready structure



## 👨‍💻 Author

**Sreesanth K S**  
- GitHub: https://github.com/sreeshanthh007  
- LinkedIn: https://www.linkedin.com/in/sreesanth-ks-264667315/
