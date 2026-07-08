# ❓ Quora Clone

A full-stack knowledge sharing platform inspired by **Quora**, where users can ask questions, share answers, and connect with people who provide valuable insights on a wide range of topics. The application encourages collaborative learning by enabling users to engage in meaningful discussions and discover knowledge shared by the community.

---

## 📖 About the Project

**Quora Clone** is a full-stack web application that recreates the core experience of Quora. Users can browse questions, post their own queries, answer existing questions, and follow other users to stay updated with their activities.

The application is built using the **MERN Stack**, with **React.js** powering the frontend, **Redux** handling application state, **Node.js** and **Express.js** serving REST APIs, and **MongoDB** providing persistent data storage. Its modular architecture and responsive interface ensure a seamless user experience across devices.

---

## ✨ Features

- 👤 User Authentication
- ❓ Ask and Browse Questions
- ✍️ Create and View Answers
- 📋 View All Posts
- 🔍 Filter Questions by Categories
- 👥 Follow Other Users
- 📰 Community Feed
- 📱 Responsive User Interface
- ⚡ State Management using Redux

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| **Frontend** | React.js |
| **State Management** | Redux |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB |
| **Languages** | JavaScript (ES6), HTML5, CSS3 |

---

## ⚙️ Setup Instructions

### Prerequisites

Make sure you have the following installed:

- Node.js (v14 or above)
- npm
- MongoDB (Local or MongoDB Atlas)

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/quora-clone.git
```

### 2. Navigate to the Project Directory

```bash
cd quora-clone
```

### 3. Install Dependencies

Install frontend dependencies:

```bash
npm install
```

Install backend dependencies (if the backend is in a separate folder):

```bash
cd server
npm install
```

### 4. Configure Environment Variables

Create a `.env` file inside the server directory and add the required environment variables:

```env
MONGO_URI=your_mongodb_connection_string
PORT=5000
JWT_SECRET=your_secret_key
```

### 5. Start the Backend Server

```bash
npm run server
```

### 6. Start the Frontend

Open a new terminal and run:

```bash
npm start
```

The application will be available at:

```
http://localhost:3000
```

> **Note:** Ensure both the frontend and backend servers are running simultaneously.

---

## 📸 Application Screenshot

### 🏠 Landing Page

![Landing Page](./assets/landing-page.png)