# 📚 StudyNotion – Full-Stack EdTech Platform

**StudyNotion** is a comprehensive EdTech platform built with the **MERN stack** (MongoDB, Express.js, React.js, Node.js). The platform enables users to explore and purchase courses, while instructors can seamlessly create and manage educational content. Designed for scalability and a modern learning experience, StudyNotion offers robust features for both students and educators.

---

## 🚀 Features

- **User Authentication & Authorization:** Secure JWT-based authentication
- **Instructor Dashboard:** Tools for course creation and content management
- **Student Dashboard:** Track course progress and access enrolled content
- **Content Management:** Upload and organize videos and modules
- **Email Notifications:** Automated emails for signups and course events
- **Responsive UI:** Modern interface built with React and Tailwind CSS

---

## 🧰 Tech Stack

| Layer    | Technology             |
| -------- | ---------------------- |
| Frontend | React.js, Tailwind CSS |
| Backend  | Node.js, Express.js    |
| Database | MongoDB                |
| Auth     | JWT                    |
| Email    | Nodemailer             |

---

## ⚙️ Getting Started (run StudyNotion locally)

### 1. Clone the Repository

Clone the repository to your local machine and navigate into the project directory:

```
git clone https://github.com/praduman8435/StudyNotion.git
```

```
cd StudyNotion
```

### 2. Start MongoDB with Docker

Make sure Docker is installed and running. Then start a MongoDB container:

```
docker run -d -p 27017:27017 --name studynotion-mongo mongo
```

### 3. Run the Frontend

Install dependencies and start the frontend development server:

```
cd frontend
npm install
npm run dev
```

### 4. Run the Backend

Open a new terminal window, then install dependencies and start the backend server:

```
cd backend
npm install
npm run dev
```

---

## 🌐 Access the App

- **Frontend:** [http://localhost:5173](http://localhost:5173)
- **Backend API:** [http://localhost:5000](http://localhost:5000)

---

### **⭐ If you liked this project, give it a star!**
