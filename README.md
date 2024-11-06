 Online Examination System

An Online Examination System built using PHP and MySQL designed to streamline the process of conducting exams online. This project enables administrators to manage exams, users, and results, while providing a smooth experience for students to take exams within set parameters.

 Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

 Features

- User Roles
  - Admin Can create and manage exams, questions, and user roles.
  - Student Can register, log in, and take exams assigned to them.

- Exam Management]
  - Multiple-choice and short-answer question types.
  - Timer-based exams with automatic submission upon completion.
  - Secure login and session management for each user.

- Result Processing
  - Automated grading for objective questions.
  - Results are accessible to both students and admins.
  - Manual grading option for subjective questions.

 Installation

1. Clone the Repository
   ```bash
   git clone <repository_url>
2. Database Setup
   - Import the SQL file (usually named something like 'database.sql' or 'exam_system.sql') into MySQL to set up the required tables and data.
   - Update the database configuration in your project’s configuration file (typically 'config.php') with your MySQL database credentials.

3. Server Setup
   - Place the project folder ("Online_exam") in the root directory of your local server, such as 'htdocs' in XAMPP.
   - Start your Apache and MySQL services.
   - Access the project by visiting `http://localhost/Online_exam` in your web browser.

 Technologies Used

- Frontend: HTML, CSS, JavaScript (Bootstrap for responsive design)
- Backend: PHP
- Database: MySQL
- Libraries: jQuery (for client-side interactivity)

 Project Structure
- config.php: Contains database configuration details.
- index.php: Main landing page or login page.
- admin: Folder containing files for admin functionalities.
- student: Folder containing files for student functionalities.
- exams: Manages exams, questions, and results.
- assets: Contains CSS, JavaScript, and image files.

 Future Enhancements

- Email Notifications: Send reminders and exam details to students via email.
- Enhanced Analytics: Detailed reports and insights for administrators.
- Mobile Responsiveness: Optimize the interface for mobile users.

 License
This project is open-source and available under the [MIT License](LICENSE).
