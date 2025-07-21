
# 📁 Project Manager - MERN Stack Task & Project Management App

A modern, scalable, and full-stack cloud-based Project & Task Management Application built with the **MERN Stack (MongoDB, Express, React, Node.js)**, enhanced with **TypeScript**, **Tailwind CSS v4**, **Shadcn UI**, and **React Router v7**. This system allows users to manage workspaces, projects, tasks, and team collaboration seamlessly in a fully responsive interface.

---

## 🚀 Features

- 🔐 **Authentication System**: Sign up, sign in, email verification, and secure password reset flows.
- 🏢 **Workspaces**: Create, manage, and navigate between multiple workspaces.
- 📁 **Projects**: Create and assign projects within each workspace.
- ✅ **Tasks**: Create, update, and track tasks inside a project.
- 📊 **Dashboard**: Overview of workspaces, projects, and tasks.
- 🌐 **Responsive UI**: Fully responsive and mobile-friendly interface.
- 🎨 **Modern UI**: Built with Tailwind CSS v4 + Shadcn UI components.
- ✉️ **Email Integration**: Email verification and reset password via mail.
- ⚙️ **Robust Backend**: Node.js, Express, and MongoDB for secure and scalable APIs.

---

## 🛠️ Tech Stack

**Frontend:**
- React.js + TypeScript
- React Router v7
- Tailwind CSS v4
- Shadcn UI
- Axios

**Backend:**
- Node.js
- Express.js
- MongoDB + Mongoose
- JWT Authentication
- Nodemailer (for emails)

---

## 🧑‍💻 Getting Started

### 📦 Prerequisites

- Node.js (v18+)
- MongoDB (local or cloud via Atlas)
- npm / yarn
- A working email account for testing email flows (use Mailtrap or similar for dev)

---

## 🔧 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/jainnaitik12/Project-Manager.git
cd Project-Manager
```

### 2. Install Frontend & Backend Dependencies

```bash
cd client
npm install
cd ../server
npm install
```

### 3. Create `.env` Files

#### For `server/.env`:

```env
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
CLIENT_URL=http://localhost:5173
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password
```

---

### 4. Run the Application

#### Backend:

```bash
cd server
npm run dev
```

#### Frontend:

```bash
cd client
npm run dev
```

Visit: `http://localhost:5173`

---



---

## 📌 Future Improvements

- 🔁 Real-time collaboration with WebSockets
- 📆 Task scheduling/calendar view
- 📱 Mobile PWA version
- 🧠 AI task suggestions (e.g., using GPT APIs)

---





