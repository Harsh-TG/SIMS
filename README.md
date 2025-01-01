# **Student Internship Management System (SIMS)**
## Description
STIMS helps manage student data and track internship and training records for students applying for internships in college. It enables administrators to manage student information, track training and internship applications, and monitor progress.

# **Tools and Technologies:**
Frontend: JavaScript, CSS
Backend: PHP
Database: MySQL
Libraries: PHPMailer (for email functionality)
# **Features:**
Manage student profiles.
Track internship applications.
View internship status updates.



# **Setup Instructions**
## Prerequisites
A web server that supports PHP (e.g., XAMPP, MAMP, or LAMP).
MySQL database.
## Frontend Setup
1.Clone the repository:
git clone (https://github.com/Harsh-TG/STAIMS.git)

2.Open the project folder and ensure all frontend files are ready.

## Backend Setup
Set up MySQL and create the database with the provided schema.
Configure config.php for your MySQL database credentials.
Ensure the PHP files are correctly handling CRUD operations.
## Running the Application
If using XAMPP, start Apache and MySQL.
Navigate to http://localhost/STIMS in your browser.
# **Testing**
Test the CRUD operations (Create, Read, Update, Delete) for student and internship records.
Ensure forms are submitting and retrieving data correctly.
Use PHP’s error logging to track and resolve any issues.
## API Endpoints (Optional)
GET /students: Fetch all students.
POST /students: Add a new student.
GET /students/{id}: Fetch a specific student.
PUT /students/{id}: Update student details.
DELETE /students/{id}: Delete a student.
# **LICENSE**
This project is licensed under the MIT License - see the LICENSE file for details.
