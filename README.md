🧑‍🏫📚 Getting Started with the Learning Platform
This guide will help new users — both students and instructors — understand how to use the platform effectively.

🚪 1. Authentication (Login/Register)
🔐 Go to the Login or Register page from the landing screen.

You can sign up as a student or instructor (based on the registration form selection).

Instructor accounts have privileges to create and manage courses.

Students can enroll in courses and participate in quizzes.

👩‍🏫 2. For Instructors
Once logged in as an instructor:

✅ Create Courses
Navigate to “Create Course” from the dashboard or side menu.

Fill out details like title, description, and category.

Submit to publish your course.

📤 Upload or 📁 Delete Course Files
Open your course.

Use the “Upload Files” button to upload study materials (PDFs, docs, images).

Uploaded files appear in a list with delete options to remove any.

📝 Create Quizzes
Open your course page.

Click on “+ New Quiz” or “Create Quiz” button.

Enter quiz title, description, and add questions with multiple-choice options.

Submit to save the quiz.

🚮 Delete Quizzes
Inside the course → quiz section.

Use the 🗑️ Delete button to remove a quiz.

💬 Communicate with Students
Each course may have a discussion/chat feature (check the sidebar or bottom section).

Instructors can post announcements or reply to student questions.

🎓 3. For Students
Once logged in as a student:

📜 View Courses & Enroll
Browse the list of available courses.

Click on a course card to see details.

Click “Enroll” to register for the course.

📥 Download Resources
Go to the enrolled course.

All uploaded resources (like PDFs or notes) are shown.

Click download next to any file to save it locally.

🧠 Take Quizzes
Navigate to the quiz section of an enrolled course.

Click “Take Quiz” to start.

Select answers and Submit when done.

See your score immediately after submission.

📌 Final Notes
🕵️‍♀️ Make sure you're logged in to the correct role (instructor or student).

💾 All your progress, uploads, and submissions are saved securely.

🚫 Unauthorized access or expired sessions redirect you to the login screen.



📚 LessonsNow – Teacher-Student Resource Manager
LessonsNow is a full-stack web application designed to manage online courses, quizzes, resources, and real-time communication between students and instructors.

🔧 Technologies Used
Backend
Python with Flask

Flask-SQLAlchemy for ORM
MySQL

Flask-SocketIO for real-time features

Firebase Admin SDK (likely for authentication or notifications)

Eventlet (for SocketIO support)

Gunicorn (for deployment)

📁 Project Structure
bash
Copy
Edit
online-course-backend/
├── app.py                    # Main Flask app
├── auth/                    # Authentication routes
├── courses/                 # Course management
├── quiz/                    # Quiz creation and management
├── uploads/                 # File upload functionality
├── models/                  # Database models and setup
├── .env                     # Environment variables
├── requirements.txt         # Python dependencies
🚀 Getting Started
1. Clone the Repository
bash
Copy
Edit
git clone https://your-repo-url.git
cd project\ teacher-student\ resourese\ manager/online-course-backend
2. Set Up a Virtual Environment
bash
Copy
Edit
python3 -m venv venv
source venv/bin/activate  # on Windows: venv\Scripts\activate
3. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
4. Set Up Environment Variables
Create a .env file at the root of the backend with the following (example):

env
Copy
Edit
DATABASE_URL=postgresql://user:password@localhost/dbname
SECRET_KEY=your_secret_key
FIREBASE_CREDENTIALS=path_to_firebase_adminsdk.json
5. Run the Application
bash
Copy
Edit
python app.py
The backend will be served on http://localhost:5000.

📚 Features
Instructor authentication and role-based access

Course and resource management

Quiz creation and submission

Real-time messaging with SocketIO

File uploads for educational content