# 🚀 Jobify

Jobify is a full-stack job portal web application that allows users to explore job opportunities and manage job-related activities through a modern and responsive interface.

The project is built using **React** for the frontend and **Node.js + Express.js** for the backend.

## ✨ Features

- 🔐 User Authentication
- 👤 User Profile Management
- 💼 Browse Job Opportunities
- 🔎 Search and Filter Jobs
- 📝 Job Application Management
- 📊 User Dashboard
- 🔒 Protected Routes
- 📱 Responsive User Interface
- ⚡ REST API Integration
- 🗄️ Database Integration

## 🛠️ Tech Stack

### Frontend

- React.js
- Vite
- JavaScript
- CSS
- Axios
- React Router

### Backend

- Node.js
- Express.js
- REST APIs
- Authentication & Authorization
- Database integration

## 📂 Project Structure

```text
Jobify/
│
├── backend/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── utils/
│   ├── routes.js
│   ├── index.js
│   └── package.json
│
├── frontend/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── vite.config.js
│
├── .gitignore
└── README.md
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone git@github.com:MohdFaizanf1/Jobify.git
cd Jobify
```

### 2. Install Backend Dependencies

```bash
cd backend
npm install
```

### 3. Install Frontend Dependencies

```bash
cd ../frontend
npm install
```

## 🔐 Environment Variables

Create a `.env` file inside the backend and frontend directories as required by the application.

Example:

```env
# Add your environment variables here
DATABASE_URL=your_database_url
JWT_SECRET=your_jwt_secret
```

> Never commit `.env` files, API keys, passwords, or other secrets to GitHub.

## ▶️ Running the Project

### Start Backend

```bash
cd backend
npm run dev
```

### Start Frontend

Open another terminal:

```bash
cd frontend
npm run dev
```

Then open the local URL displayed by Vite in your browser.

## 🔄 Application Flow

```text
User
  ↓
React Frontend
  ↓
REST API
  ↓
Node.js + Express.js Backend
  ↓
Database
```

The frontend communicates with the backend through REST APIs. The backend handles application logic, authentication, validation, and database operations.

## 🔒 Security

- Environment variables are excluded using `.gitignore`
- Sensitive credentials are not stored directly in the source code
- Protected endpoints use authentication and authorization
- Secrets should always be stored in environment variables

## 🚀 Future Improvements

- Advanced job recommendations
- Improved search and filtering
- Admin dashboard
- Application status tracking
- Email notifications
- Improved analytics dashboard

## 👨‍💻 Author

**Mohd Faizan**

B.Tech Computer Science & Engineering  
Bennett University

GitHub: `MohdFaizanf1`

## 📄 License

This project is intended for educational and portfolio purposes.
