# 🧭 FindMyJob - MERN Stack Job Portal

FindMyJob is a modern full-stack job portal application built using the **MERN stack** (MongoDB, Express.js, React.js, and Node.js). It allows job seekers to search and apply for jobs, while employers can post and manage listings.

---

## 🚀 Features

### 👨‍💼 Job Seekers
- Register/Login with authentication
- Browse job listings by category, location, and keywords
- Apply to jobs with resume upload
- Track applied jobs
- User profile with resume and details

### 🏢 Employers
- Register/Login with authentication
- Post new job openings
- Edit/delete job postings
- View applicants and application details

### ⚙️ Admin Panel
- View/manage all users and job listings
- Delete inappropriate or inactive job posts

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Redux Toolkit (if used)
- Axios
- Tailwind CSS / Bootstrap

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT for Authentication
- Multer for file uploads (resumes)

---

## 🔐 Authentication
- Secure login/signup using JWT
- Protected routes for both job seekers and employers

---

## 📦 Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/Kartikey2402/JobPortal.git
cd findmyjob
````

### 2. Setup Backend

```bash
cd backend
npm install
```

Create a `.env` file in `/backend` with all required environment variables.

```

Then run:

```bash
npm run dev
```

### 3. Setup Frontend

```bash
cd ../frontend
npm install
npm run dev
```

## 📸 Screenshots

| Job Listings                          | Job Details                               |
| ------------------------------------- | ----------------------------------------- |
| ![Job list](screenshots/job-list.png) | ![Job detail](screenshots/job-detail.png) |

---

## ✅ Future Improvements

* Email notifications
* Admin dashboard analytics
* Resume parser integration
* Pagination and search filters

---

## 🤝 Contribution

Contributions are welcome!
Please fork the repo and submit a pull request for review.


