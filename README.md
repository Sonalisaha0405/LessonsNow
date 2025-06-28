# 📚 LessonsNow – Teacher-Student Resource Manager

**LessonsNow** is a full-stack web application that facilitates seamless interaction between instructors and students. It supports course management, quiz creation, resource sharing, and real-time communication — all in one platform.

---

## 🧑‍🏫 Getting Started Guide

This guide will help **students** and **instructors** get started with the platform effectively.

---

### 🚪 1. Authentication (Login/Register)

- Navigate to the **Login** or **Register** page.
- Sign up as either a **Student** or an **Instructor**.
  - **Instructors** can create and manage courses and quizzes.
  - **Students** can enroll in courses, download materials, and take quizzes.

---

### 👩‍🏫 2. Features for Instructors

#### ✅ Create Courses
- Go to the **Create Course** section from the dashboard or sidebar.
- Provide course title, description, and category.
- Submit to publish.

#### 📤 Upload / 📁 Delete Course Files
- Open a course page.
- Upload materials (PDFs, Docs, Images) using the **Upload Files** button.
- Delete files using the trash icon next to each uploaded item.

#### 📝 Create Quizzes
- Click **Create Quiz** on the course page.
- Provide quiz title and description.
- Add multiple-choice questions and submit.

#### 🚮 Delete Quizzes
- Go to the quiz section of the course.
- Use the **🗑️ Delete** button to remove a quiz.

#### 💬 Student Communication
- Access the built-in chat or announcement section on the course page.
- Post updates or reply to student queries in real time.

---

### 🎓 3. Features for Students

#### 📜 Browse & Enroll in Courses
- View all available courses on the home/dashboard page.
- Click on a course to see details and click **Enroll**.

#### 📥 Download Resources
- Access the course resources section.
- Download any file by clicking the download icon.

#### 🧠 Take Quizzes
- Navigate to the quiz section within an enrolled course.
- Start a quiz, select answers, and submit.
- Scores are displayed immediately after submission.

---

## 📌 Notes

- Ensure you're logged in under the correct role (**Instructor** or **Student**).
- All progress, uploads, and submissions are saved securely.
- Unauthorized access or expired sessions will redirect to the login page.

---

## 🔧 Technologies Used

### 🔙 Backend
- **Python** with **Flask**
- **Flask-SQLAlchemy** (ORM)
- **MySQL**
- **Flask-SocketIO** (for real-time communication)
- **Firebase Admin SDK** (authentication or notifications)
- **Eventlet** (SocketIO support)
- **Gunicorn** (for production deployment)

---

## 📁 Project Structure

