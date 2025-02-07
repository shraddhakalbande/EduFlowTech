EduFlowTech - Student Attendance Management System

📌 Project Overview
EduFlowTech is a Student Attendance Management System designed to streamline attendance tracking and subject management. Built using Spring Boot, Hibernate, and MySQL, this modular system ensures efficient record-keeping and seamless user interaction.

🚀 Features
✔ Student Management: Register, update, and manage student details.
✔ Subject Management: Assign, update, and track subjects.
✔ User Authentication: Secure access with role-based permissions.
✔ Attendance Tracking: Log and retrieve attendance records.
✔ RESTful APIs: Endpoints for efficient data access and integration.

🛠️ Tech Stack
🔹 Backend: Java, Spring Boot
🔹 Database: MySQL
🔹 ORM: Hibernate
🔹 Testing: Postman
🔹 Architecture: Layered (Controller, Service, Repository)

📂 Modules
🔸 Student Controller: Manages student-related operations.
🔸 Subject Controller: Handles subject assignments and retrieval.
🔸 User Controller: Manages user authentication and roles.
🔸 Attendance Record Controller: Handles attendance tracking.

🔧 Installation & Setup
➡ Clone the repository:
  git clone https://github.com/yourusername/EduFlowTech.git
➡ Navigate to the project directory:
  cd EduFlowTech
➡ Configure application.properties for MySQL connection.
➡ Build and run the application:
  mvn spring-boot:run
  
📖 API Endpoints
Endpoint	Method	Description
/students	GET	Get all students
/subjects	GET	Retrieve all subjects
/attendance	POST	Record student attendance
/users/login	POST	User authentication

---
