# 📚 StudyNotion

**StudyNotion** is a comprehensive EdTech platform built with the **MERN stack** (MongoDB, Express.js, React.js, Node.js). The platform enables users to explore and purchase courses, while instructors can seamlessly create and manage educational content. Designed for scalability and a modern learning experience, StudyNotion offers robust features for both students and educators.

<img width='100%' src='https://github.com/praduman8435/StudyNotion/blob/main/screenshots/home1.png' />

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

### 3. Environment Variables Setup

To run the **StudyNotion** project locally, you need to configure environment variables for both the **backend** and **frontend**.

#### 📦 Backend Environment Variables

1. Go to the `backend/` directory.
2. Create a file named `.env`
3. Add the following environment variables:

```env
PORT=5000

DATABASE_URL=mongodb://localhost:27017/your-db-name

CLOUD_NAME=your_cloudinary_cloud_name
API_KEY=your_cloudinary_api_key
API_SECRET=your_cloudinary_api_secret

JWT_SECRET=your_jwt_secret_key

RAZORPAY_KEY=your_razorpay_key
RAZORPAY_SECRET=your_razorpay_secret

FOLDER_NAME=your_folder_name_for_uploads

MAIL_HOST=your_smtp_host
MAIL_USER=your_email@example.com
MAIL_PASS=your_email_password_or_app_specific_password
```
#### 📦 Frontend Environment Variables

1. Go to the `frontend/` directory.
2. Create a file named `.env`
3. Add the following environment variables:

```env
VITE_APP_BASE_URL=http://localhost:5000/api/v1

VITE_APP_RAZORPAY_KEY=your_razorpay_key
```

### 4. Run the Frontend

Install dependencies and start the frontend development server:

```
cd frontend
npm install
npm run dev
```

### 5. Run the Backend

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

### **⭐ Support with a star!**

<img width='100%' src='https://github.com/praduman8435/StudyNotion/blob/main/screenshots/gif2.gif' />
