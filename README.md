# SchoolManagementSystem


This is a comprehensive School Management System designed to manage the various aspects of a school’s operations. Built using HTML, CSS for the frontend, and PHP for the backend, this system facilitates the management of students, teachers, classes, attendance, and more.

## Features

### 1. **Student Management**
   - Add, update, and delete student records.
   - Assign students to specific classes and sections.
   - Manage student attendance and grades.

### 2. **Teacher Management**
   - Add, update, and remove teacher profiles.
   - Assign teachers to classes and subjects.
   - Track teacher attendance and performance.

### 3. **Class Management**
   - Create and manage class schedules.
   - Assign students and teachers to specific classes.
   - Organize classes into different sections.

### 4. **Attendance Tracking**
   - Record daily attendance for students and teachers.
   - Generate attendance reports for analysis.
   - Notify parents of student absences via email.

### 5. **Examination Management**
   - Schedule exams and assign them to classes.
   - Input and manage student exam results.
   - Generate and print report cards.

### 6. **User Management**
   - Role-based access control (admin, teacher, student, parent).
   - Secure login system with password encryption.
   - User profiles with customizable settings.

### 7. **Notifications**
   - Send notifications to students, teachers, and parents.
   - Automatic email alerts for important events.

### 8. **Dashboard**
   - Overview of the entire system with quick access to important features.
   - Statistics on student performance, attendance, and more.

## Installation

### Prerequisites
- **PHP**: Version 7.4 or higher
- **MySQL**: Database to store the system's data
- **Apache/Nginx**: Web server to host the application

### Steps
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/KevTheTech/SchoolManagementSystem.git

   ```
   
2. **Navigate to the Project Directory:**
   ```bash
   cd SchoolManagementSystem
   ```

3. **Database Setup:**
   - Create a new MySQL database.
   - Import the provided `database.sql` file into your database.

4. **Configuration:**
   - Open the `config.php` file and update the database connection details:
     ```php
     <?php
     $host = 'localhost';
     $db = 'your_database_name';
     $user = 'your_database_user';
     $pass = 'your_database_password';
     ?>
     ```
     
5. **Start the Server:**
   - If using XAMPP, move the project folder to the `htdocs` directory.
   - Start Apache and MySQL from the XAMPP control panel.
   - Access the application by visiting `http://localhost/SchoolManagementSystem` in your browser.

## Usage

### Admin Login
- Username: `admin`
- Password: `admin123`

Once logged in as an admin, you can manage all aspects of the system including students, teachers, classes, and exams.

### Teacher and Student Login
- Teachers and students can log in using their assigned credentials to access their respective dashboards.

## Project Structure

```plaintext
SchoolManagementSystem/
│
├── css/
│   └── styles.css         # CSS files for styling the frontend
│
├── js/
│   └── scripts.js         # JavaScript files for client-side interactions
│
├── includes/
│   ├── header.php         # Common header file
│   ├── footer.php         # Common footer file
│   └── config.php         # Database configuration
│
├── pages/
│   ├── admin/
│   │   ├── dashboard.php  # Admin dashboard
│   │   ├── students.php   # Manage students
│   │   ├── teachers.php   # Manage teachers
│   │   └── classes.php    # Manage classes
│   │
│   ├── teacher/
│   │   ├── dashboard.php  # Teacher dashboard
│   │   ├── attendance.php # Mark attendance
│   │   └── grades.php     # Input grades
│   │
│   ├── student/
│   │   ├── dashboard.php  # Student dashboard
│   │   └── results.php    # View results
│   │
│   └── login.php          # Login page
│
├── index.php              # Main landing page
├── README.md              # Project documentation
└── database.sql           # SQL file to set up the database
```

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your proposed changes.


## Contact

If you have any questions or need further assistance, please contact us at [Kevadvtcorp@gmail.com](mailto:Kevadvtcorp@gmail.com).
