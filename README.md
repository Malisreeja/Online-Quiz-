# Online-Quiz-platform
A dynamic and user-friendly Online Quiz Platform built using Java (JSP + Servlets) and XAMPP (MySQL + Apache). This project allows students to register, take quizzes within a time limit, and get auto-evaluated results instantly.



## 🎯 Objective

The platform is designed to conduct online quizzes securely with features like authentication, timed questions, and automatic score evaluation. Ideal for schools, colleges, or training centers.



## 🚀 Features

- 🔐 User registration and login system
- 🧾 Admin panel to add/edit/delete quiz questions
- 🧠 Quiz module with timer and auto-submission
- 📊 Automatic evaluation and result generation
- 💾 MySQL database to store user data, questions, and results
- 📱 Responsive front-end using HTML, CSS, Bootstrap



## 🛠️ Technologies Used

- **Frontend:** HTML5, CSS3, Bootstrap
- **Backend:** Java (JSP, Servlets)
- **Database:** MySQL (via XAMPP)
- **Server:** Apache (via XAMPP)
- **IDE:** Eclipse/NetBeans



## 🗂️ Project Structure

online-quiz-platform/
│
├── src/
│ ├── com.quiz.controller/ # Servlets (LoginServlet, QuizServlet, etc.)
│ ├── com.quiz.dao/ # Data access logic
│ ├── com.quiz.model/ # Java Beans (User, Question, Result)
├── WebContent/
│ ├── index.jsp # Home Page
│ ├── login.jsp # User Login
│ ├── register.jsp # User Registration
│ ├── quiz.jsp # Quiz Interface
│ ├── result.jsp # Display results
│ └── css/ # Styling
│ └── js/ # JavaScript (timer, form validation)
├── DB/
│ └── quiz.sql # Database schema and sample data
├── README.md # Documentation


## 🔌 How to Run

1. **Install XAMPP** and start Apache & MySQL servers.
2. **Import `quiz.sql`** file into **phpMyAdmin** to set up the database.
3. **Open Eclipse/NetBeans** and import this project.
4. Set up the **Apache Tomcat server** and run the project.
5. Access it via:
http://localhost:8080/online-quiz-platform/





- **Admin:**  
Username: `admin`  
Password: `admin123`

- **Student:**  
Register a new user through the signup page.



## 👩‍💻 Author

Mali Sreeja Reddy
🔗 [GitHub](https://github.com/Malisreeja) | ✉️ sreejareddymali@gmail.com
