# E-Learning Platform

A PHP and MySQL based e-learning system for students, tutors, and admins.  
It allows users to register, manage courses, watch lessons, take quizzes, and track progress.  
Built for local development using XAMPP.

## 🧩 Features
- User registration and login  
- Separate panels for students, tutors, and admins  
- Course and playlist management  
- Video lessons and progress tracking  
- Quiz and score system  
- Likes, comments, and bookmarks

## ⚙️ Technologies Used
- PHP  
- MySQL  
- HTML, CSS, JavaScript  
- XAMPP for local server setup

## 🚀 How to Run Locally
1. Install **XAMPP** and start **Apache** and **MySQL**.  
2. Copy this project folder into `htdocs`.  
3. Open **phpMyAdmin**, click **Import**, and upload the file `course_db.sql`.  
4. Copy `config.sample.php` to `config.php` and add your database credentials.  
5. Visit `http://localhost/<your-folder-name>` in your browser.

## 🗄️ Database
- File: `course_db.sql`  
- Import it in phpMyAdmin to create tables and sample data.

## 🔒 Security Note
- Keep `config.php` private. It contains your actual credentials.  
- `.gitignore` ensures `config.php` is not uploaded to GitHub.

## 📢 Deployment
GitHub Pages cannot run PHP. Use a PHP hosting service like:
- Render  
- 000webhost  
- InfinityFree  
- Any cPanel hosting provider

## 📄 License
This project is for educational purposes only.

## 📸 Project Screenshots

![Home Page](images/homepage.png)
*Home page of the E-Learning Platform*

![Teacher Section](images/teacher-section.png)
*Teacher dashboard for course management*

![Quiz Interface](images/quiz-interface.png)
*Students taking quizzes on the platform*

