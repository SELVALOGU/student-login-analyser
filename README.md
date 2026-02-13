# Secure Student Login Behaviour Analyzer

A full-stack web application tracking and analyzing student login patterns to detect suspicious behavior.

## Features
- **Secure Authentication**: Hashed passwords (bcrypt), Session management.
- **Behaviour Tracking**: IP, Device, Login Time monitoring.
- **Risk Analysis**: Detects multiple failed attempts, new locations/devices.
- **Dashboards**:
  - **Student**: View login history and risk alerts.
  - **Admin**: Monitor all users and block suspicious accounts.

## Tech Stack
- Frontend: HTML5, CSS3, Bootstrap 5, Chart.js
- Backend: PHP (Native)
- Database: MySQL

## Setup Instructions
1. **Database Setup**:
   - Create a database named `student_behaviour_db` in MySQL.
   - Import `database.sql` to create the required tables.
   - (Optional) Configure `config.php` if your database credentials differ from default (root/empty).

2. **Run the Application**:
   - Host the files on a PHP server (e.g., XAMPP/WAMP or built-in PHP server).
   - Navigate to `index.php`.

3. **Default Admin Credentials**:
   - Username: `admin`
   - Password: `admin123`

## Folder Structure
- `/admin`: Admin dashboard & management scripts.
- `/student`: Student dashboard.
- `/auth`: Login, Register, Logout scripts.
- `/includes`: Helper functions, header/footer.
- `/assets`: CSS, JS, Images.
