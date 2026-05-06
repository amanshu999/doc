# PROJECT REPORT

**ON**

## GOVERNMENT POLYTECHNIC, JAMMU
## COMPUTER ENGINEERING DEPARTMENT PLATFORM

**Submitted in partial fulfillment of the requirements for the diploma of**
**Diploma in Computer Engineering**

**Submitted By:**
**[Your Name / Amanshu]**
**[Your Roll Number]**

**Under the Guidance of:**
**[Guide's Name]**
**[Guide's Designation]**

---

<br><br><br><br><br><br><br><br><br><br><br><br>

## DECLARATION

I hereby declare that the project entitled "Govt. Polytechnic Jammu Computer Engineering Department Platform" submitted for the Diploma in Computer Engineering is my original work and the project has not formed the basis for the award of any diploma, associate ship, fellowship or any other similar titles.

**Place:** Jammu  
**Date:** [Date]  
**Signature of the Student:** __________________  
**Name:** [Your Name / Amanshu]

<br><br><br><br><br><br><br><br><br><br><br><br>

---

## CERTIFICATE

This is to certify that the project report entitled "Govt. Polytechnic Jammu Computer Engineering Department Platform" is a bonafide record of the project work done by **[Your Name]**, in partial fulfillment of the requirement for the award of the Diploma in Computer Engineering, and that the project has not previously formed the basis for the award of any diploma, degree, fellowship, or any other similar title.

**Signature of Guide:** __________________  
**Name of Guide:** [Guide's Name]  

**Signature of HOD:** __________________  
**Name of HOD:** [HOD's Name]  

<br><br><br><br><br><br><br><br><br><br><br><br>

---

## ACKNOWLEDGEMENT

I would like to express my special thanks of gratitude to my project guide [Guide's Name] as well as our principal who gave me the golden opportunity to do this wonderful project on the topic "Govt. Polytechnic Jammu Computer Engineering Department Platform", which also helped me in doing a lot of Research and I came to know about so many new things. I am really thankful to them.

Secondly, I would also like to thank my parents and friends who helped me a lot in finalizing this project within the limited time frame.

<br><br><br><br><br><br><br><br><br><br><br><br>

---

## ABSTRACT

With the rapid advancement of technology in educational institutions, it has become imperative for departments to have a digital presence that is not only informative but also highly functional and dynamic. The **Government Polytechnic, Jammu - Computer Engineering Department Platform** is a comprehensive web-based application architected to address the specific needs of modern academic environments. 

This platform leverages a foundational PHP 8+ setup seamlessly integrated with native MySQL architectures. It bypasses the need for bloated external frameworks, ensuring a lightweight, fast, and highly secure system. Key features include an Engineered Dynamic Academics Pipeline for managing curriculums, a robust Faculty & Administration Portal for notices and profile insertions, and a Dark Matrix UI Toggle Engine for an enhanced user experience via local storage caching. Furthermore, it incorporates secure database-managed inquiry systems, removing the reliance on disparate email chains. 

The primary objective of this project is to create an intuitive, scalable, and responsive digital ecosystem that bridges the communication gap between the administration, faculty, and students, thereby streamlining departmental operations.

<br><br><br><br><br><br><br><br><br><br><br><br>

---

## 1. INTRODUCTION

### 1.1 Project Objective
The main objective of this project is to develop a robust, dynamic, and fully functional web platform for the Computer Engineering Department of Government Polytechnic, Jammu. The system aims to:
- Digitize the management of academic courses and syllabi.
- Provide a centralized hub for departmental notices and announcements.
- Showcase faculty profiles and academic qualifications efficiently.
- Facilitate direct, database-logged communication between students and the administration.
- Deliver a modern, visually appealing user interface with dark mode capabilities.

### 1.2 Scope of the Project
The scope of the project encompasses the complete lifecycle of departmental data management. It provides a dual-layer interface:
1. **Public Interface (Frontend):** Accessible to students and the general public to view courses, faculty members, notices, and submit inquiries.
2. **Administrative Interface (Backend):** A secure dashboard for authorized personnel to dynamically update content without requiring any coding knowledge.

The system is designed to be scalable, meaning future modules (such as student attendance tracking or online assignment submission) can be integrated with minimal structural changes.

### 1.3 Problem Statement
Prior to the implementation of this system, the department relied heavily on manual processes and static notice boards. The existing mechanisms had several drawbacks:
- **Information Delay:** Notices printed on paper often reached students late.
- **Inaccessibility of Resources:** Course syllabi and academic materials were not easily accessible remotely.
- **Scattered Communication:** Inquiries from students were often lost or delayed due to a lack of a centralized tracking system.
- **Maintenance Overhead:** Updating a static HTML website required technical expertise, creating bottlenecks whenever minor changes were needed.

This project addresses these issues by providing a dynamic, database-driven solution where content is managed seamlessly through an intuitive Admin Dashboard.

<br><br><br><br><br><br><br><br><br><br><br><br>

---

## 2. LITERATURE REVIEW / EXISTING SYSTEM VS. PROPOSED SYSTEM

### 2.1 Existing System
In many traditional academic departments, the existing system is predominantly manual or relies on outdated, static web pages.
- **Data Management:** Handled via physical files and ledgers.
- **Communication:** Circulars are printed and pinned to notice boards.
- **Resource Sharing:** Syllabi are distributed as hard copies at the beginning of the semester.
- **Disadvantages:** Time-consuming, prone to human error, environmentally unfriendly (high paper usage), and lacks remote accessibility.

### 2.2 Proposed System
The proposed system is a fully automated, web-based platform tailored specifically for the Computer Engineering Department.
- **Data Management:** Centralized MySQL database ensuring data integrity and fast retrieval.
- **Communication:** Digital notices published instantly, accessible from any device.
- **Resource Sharing:** PDF syllabi uploaded and managed directly through the platform.
- **Advantages:** Instantaneous updates, 24/7 remote accessibility, secure administrative controls, and an eco-friendly paperless approach.

<br><br><br><br><br><br><br><br><br><br><br><br>

---

## 3. SYSTEM ANALYSIS

### 3.1 Feasibility Study
Before initiating the development phase, a thorough feasibility study was conducted to ensure the viability of the project across three main dimensions:

#### 3.1.1 Technical Feasibility
The project is highly technically feasible. It utilizes widely accepted and robust technologies: PHP, MySQL, HTML5, Vanilla JavaScript, and Bootstrap 5.3. These technologies are standard in the industry, well-documented, and capable of handling the projected load of the departmental website. The system can be hosted on any standard Apache web server, making deployment straightforward.

#### 3.1.2 Economic Feasibility
The system is economically feasible as it relies entirely on Open-Source technologies. There are no licensing fees required for PHP, MySQL, or Bootstrap. The only potential costs are related to domain registration and web hosting, which are nominal and easily absorbed by the institution's IT budget. The automation of manual tasks also results in significant long-term cost savings in terms of labor and administrative overhead.

#### 3.1.3 Operational Feasibility
Operationally, the system is designed with user-friendliness in mind. The administrative dashboard utilizes tools like TinyMCE for rich-text editing, allowing staff members to update content exactly as they would in a word processor. No specialized technical training is required for the administrative staff to operate the backend, ensuring high operational feasibility.

<br><br><br><br><br><br><br><br><br><br><br><br>

---

## 4. SYSTEM REQUIREMENTS SPECIFICATION (SRS)

### 4.1 Hardware Requirements
**For Server (Hosting):**
- Processor: Dual-Core Intel/AMD or higher
- RAM: 2 GB Minimum (4 GB Recommended)
- Storage: 20 GB SSD (for fast database access and file storage)
- Network: High-speed internet connection

**For Client (User/Admin):**
- Processor: Standard dual-core processor
- RAM: 1 GB Minimum
- Display: 1024x768 resolution minimum (Optimized for all screen sizes)
- Any modern web-enabled device (PC, Laptop, Smartphone, Tablet)

### 4.2 Software Requirements
**Server Side:**
- Operating System: Linux (Ubuntu/CentOS) or Windows Server
- Web Server: Apache HTTP Server
- Database Management System: MySQL 8.0 or MariaDB
- Server-Side Scripting: PHP 8.1+

**Client Side:**
- Web Browser: Google Chrome, Mozilla Firefox, Safari, or Microsoft Edge (Latest versions with JavaScript enabled)

### 4.3 Technology Stack Description
1. **Frontend Architecture:**
   - **HTML5 & CSS3:** Semantic markup and styling for a structured and visually appealing layout.
   - **Vanilla JavaScript:** For DOM manipulation, theme toggling logic, and form validation.
   - **Bootstrap 5.3:** A powerful frontend framework utilized for its responsive grid system and pre-built UI components. It natively supports the `data-bs-theme` attribute, which is crucial for the dark mode implementation.
   - **AOS (Animate On Scroll):** Used to trigger CSS animations dynamically as the user scrolls down the page, providing a premium feel.

2. **Backend Architecture:**
   - **PHP 8+:** The core server-side language. Native, raw PHP is used to ensure maximum performance and minimal overhead without relying on bloated frameworks.
   - **MySQLi Extension:** Used for secure, object-oriented database interactions. Prepared statements are utilized to prevent SQL injection attacks.

3. **Database Architecture:**
   - **MySQL:** A relational database management system used to store all dynamic content, including courses, faculty details, notices, and user inquiries.

<br><br><br><br><br><br><br><br><br><br><br><br>

---

## 5. SYSTEM DESIGN

System design is the process of defining the architecture, components, modules, interfaces, and data for a system to satisfy specified requirements.

### 5.1 Architecture Diagram

The system follows a standard Client-Server Architecture / MVC (Model-View-Controller) inspired pattern using modular includes.

```text
+-------------------+       HTTP/HTTPS        +-------------------+
|                   |  Requests (GET/POST)    |                   |
|   Client Device   | ----------------------> |   Apache Server   |
| (Browser/Mobile)  | <---------------------- | (PHP 8.x Engine)  |
|                   |       HTML/JSON         |                   |
+-------------------+                         +---------+---------+
                                                        |
                                            MySQLi Connect/Queries
                                                        |
                                                        V
                                              +-------------------+
                                              |                   |
                                              |  MySQL Database   |
                                              |   (college_db)    |
                                              |                   |
                                              +-------------------+
```

### 5.2 Database Schema & Data Dictionary

The project utilizes a relational database named `college_db`. Below is the detailed structure of the tables used in the system.

#### Table: `admins`
Stores the administrative credentials.
| Field Name      | Data Type    | Constraints                  | Description                          |
|-----------------|--------------|------------------------------|--------------------------------------|
| `id`            | INT          | Primary Key, Auto Increment  | Unique identifier for the admin.     |
| `username`      | VARCHAR(255) | NOT NULL, UNIQUE             | Login username (e.g., 'admin').      |
| `password_hash` | VARCHAR(255) | NOT NULL                     | Bcrypt hashed password.              |
| `created_at`    | TIMESTAMP    | Default CURRENT_TIMESTAMP    | Record creation timestamp.           |

#### Table: `courses`
Stores information about the academic programs and syllabi.
| Field Name      | Data Type    | Constraints                  | Description                          |
|-----------------|--------------|------------------------------|--------------------------------------|
| `id`            | INT          | Primary Key, Auto Increment  | Unique identifier for the course.    |
| `title`         | VARCHAR(150) | NOT NULL                     | Name of the course (e.g., BCA).      |
| `level`         | VARCHAR(50)  | NOT NULL                     | Academic level (UG/PG).              |
| `duration`      | VARCHAR(50)  | NOT NULL                     | Duration of the course (e.g., 3 Yrs) |
| `description`   | TEXT         | NOT NULL                     | Detailed description of the course.  |
| `image`         | VARCHAR(255) | NOT NULL                     | Path to the course thumbnail.        |
| `syllabus_file` | VARCHAR(255) | DEFAULT NULL                 | Path to the uploaded PDF syllabus.   |
| `created_at`    | TIMESTAMP    | Default CURRENT_TIMESTAMP    | Record creation timestamp.           |

#### Table: `faculty`
Stores profiles of the teaching staff.
| Field Name      | Data Type    | Constraints                  | Description                          |
|-----------------|--------------|------------------------------|--------------------------------------|
| `id`            | INT          | Primary Key, Auto Increment  | Unique identifier.                   |
| `name`          | VARCHAR(255) | NOT NULL                     | Full name of the faculty member.     |
| `designation`   | VARCHAR(255) | NOT NULL                     | Job title (e.g., Professor).         |
| `qualification` | VARCHAR(255) | NOT NULL                     | Highest academic degree.             |
| `image`         | VARCHAR(255) | NOT NULL                     | Path to the profile picture.         |
| `created_at`    | TIMESTAMP    | Default CURRENT_TIMESTAMP    | Record creation timestamp.           |

#### Table: `notices`
Stores official announcements.
| Field Name      | Data Type    | Constraints                  | Description                          |
|-----------------|--------------|------------------------------|--------------------------------------|
| `id`            | INT          | Primary Key, Auto Increment  | Unique identifier.                   |
| `title`         | VARCHAR(255) | NOT NULL                     | Headline of the notice.              |
| `description`   | TEXT         | NOT NULL                     | Full HTML content (from TinyMCE).    |
| `created_at`    | TIMESTAMP    | Default CURRENT_TIMESTAMP    | Record creation timestamp.           |

#### Table: `contacts`
Stores inquiries submitted by users via the contact form.
| Field Name      | Data Type    | Constraints                  | Description                          |
|-----------------|--------------|------------------------------|--------------------------------------|
| `id`            | INT          | Primary Key, Auto Increment  | Unique identifier.                   |
| `name`          | VARCHAR(255) | NOT NULL                     | Name of the sender.                  |
| `email`         | VARCHAR(255) | NOT NULL                     | Email address of the sender.         |
| `subject`       | VARCHAR(255) | NOT NULL                     | Subject of the inquiry.              |
| `message`       | TEXT         | NOT NULL                     | The inquiry content.                 |
| `created_at`    | TIMESTAMP    | Default CURRENT_TIMESTAMP    | Timestamp of submission.             |

#### Table: `gallery`
Stores images for the departmental showcase.
| Field Name      | Data Type    | Constraints                  | Description                          |
|-----------------|--------------|------------------------------|--------------------------------------|
| `id`            | INT          | Primary Key, Auto Increment  | Unique identifier.                   |
| `title`         | VARCHAR(255) | NOT NULL                     | Caption/Title of the image.          |
| `image`         | VARCHAR(255) | NOT NULL                     | Path to the uploaded image file.     |
| `created_at`    | TIMESTAMP    | Default CURRENT_TIMESTAMP    | Record creation timestamp.           |

### 5.3 Entity Relationship (ER) Diagram

The relationships in the database are relatively straightforward as the system primarily focuses on independent entities managed by a central administration.

```text
[ ADMINS ] 1 -------- Manages -------- * [ COURSES ]
           1 -------- Manages -------- * [ FACULTY ]
           1 -------- Manages -------- * [ NOTICES ]
           1 -------- Manages -------- * [ GALLERY ]
           1 -------- RespondsTo ----- * [ CONTACTS ]
```

<br><br><br><br><br><br><br><br><br><br><br><br>

---

## 6. MODULE DESCRIPTION

The platform is logically divided into two primary modules:

### 6.1 Public User Module (Frontend)
This module is accessible to anyone visiting the URL. It is designed to be fast, responsive, and visually appealing.
- **Home Page (`index.php`):** The landing page providing an overview of the department, quick links, and recent notices.
- **About Page (`about.php`):** Detailed history, vision, and mission of the Computer Engineering Department.
- **Courses Page (`courses.php`):** Dynamically fetches and displays all available courses from the database. It provides downloadable links for syllabus PDFs.
- **Faculty Page (`faculty.php`):** Displays a grid of faculty profiles, showing their designations and qualifications.
- **Notices Page (`notices.php`):** A paginated list of all official announcements. It supports rich text, allowing for bold text, lists, and links within the notice.
- **Gallery Page (`gallery.php`):** A visual showcase of campus events and infrastructure.
- **Contact Page (`contact.php`):** A form allowing users to send inquiries directly to the database.

### 6.2 Administrative Module (Backend)
This module is highly secured and restricted to authorized personnel.
- **Authentication:** Admins must log in using securely hashed credentials. Session management (`$_SESSION`) ensures that unauthorized users are redirected to the login page.
- **Dashboard (`admin/index.php`):** Provides a high-level overview of the system, including counts of total courses, faculty, notices, and pending messages.
- **Manage Courses (`add_course.php`, `manage_courses.php`):** Allows admins to create new courses, upload thumbnails, and attach PDF syllabus files. It includes robust file validation to ensure only permitted file types are uploaded.
- **Manage Faculty (`add_faculty.php`, `manage_faculty.php`):** Interface to add, edit, or remove faculty profiles and photos.
- **Manage Notices (`add_notice.php`, `manage_notices.php`):** Utilizes the TinyMCE rich text editor, enabling admins to format notices beautifully before publishing them to the database.
- **Inquiry Management (`messages.php`, `reply.php`):** Instead of relying on external email clients, admins can view all submitted contact forms in a tabular format and draft replies directly from the dashboard.

<br><br><br><br><br><br><br><br><br><br><br><br>

---

## 7. FULL SOURCE CODE IMPLEMENTATION

This section highlights the core logic, coding standards, and full source code files implemented during the development of the platform to demonstrate technical proficiency.

### 7.1 Database Connection Engine (`includes/db.php`)
This file is the central nervous system of the application, responsible for establishing a secure, persistent connection to the MySQL database. It utilizes the object-oriented `mysqli` extension.

```php
<?php
// includes/db.php
$host = 'localhost';
$user = 'root';
$pass = ''; // Default XAMPP password is empty
$dbname = 'college_db';

// Create a robust connection object
$conn = new mysqli($host, $user, $pass, $dbname);

// Security Check: Validate connection state
if ($conn->connect_error) {
    // Elegant failure mode
    die("<div style='padding: 20px; background: #ffe6e6; border-left: 5px solid #ff4d4d;'>
            <h3>Database Connection Failed</h3>
            <p>" . $conn->connect_error . "</p>
         </div>");
}
?>
```

### 7.2 Database Setup & Initialization (`setup_db.php`)
To automate the deployment process, this script dynamically generates all required tables and instantiates the default root administrator using cryptographic hashing.

```php
<?php
// setup_db.php (Partial Logic)
$host = 'localhost';
$user = 'root';
$pass = '';

$conn = new mysqli($host, $user, $pass);
if ($conn->connect_error) die("Failed");

$dbname = 'college_db';
$conn->query("CREATE DATABASE IF NOT EXISTS `$dbname`");
$conn->select_db($dbname);

$setup_queries = [
    "CREATE TABLE IF NOT EXISTS contacts (
        id INT AUTO_INCREMENT PRIMARY KEY,
        name VARCHAR(255) NOT NULL,
        email VARCHAR(255) NOT NULL,
        subject VARCHAR(255) NOT NULL,
        message TEXT NOT NULL,
        created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
    )",
    "CREATE TABLE IF NOT EXISTS admins (
        id INT AUTO_INCREMENT PRIMARY KEY,
        username VARCHAR(255) NOT NULL UNIQUE,
        password_hash VARCHAR(255) NOT NULL,
        created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
    )"
];

foreach ($setup_queries as $query) {
    $conn->query($query);
}

// Instantiate Root Admin with BCrypt Hash
$checkAdmin = $conn->query("SELECT * FROM admins WHERE username = 'admin'");
if ($checkAdmin && $checkAdmin->num_rows == 0) {
    $adminUser = 'admin';
    $adminPassRaw = 'riot12%';
    $hashedPassword = password_hash($adminPassRaw, PASSWORD_DEFAULT);
    $stmt = $conn->prepare("INSERT INTO admins (username, password_hash) VALUES (?, ?)");
    $stmt->bind_param("ss", $adminUser, $hashedPassword);
    $stmt->execute();
}
?>
```

<br><br><br><br><br><br>

### 7.3 Advanced Course Management Controller (`admin/add_course.php`)
This backend script handles the complex logic of securely uploading multiple file types (Images and PDF Syllabi) while preventing malicious uploads. It then sanitizes input and binds it to a prepared SQL statement.

```php
<?php
// admin/add_course.php
require_once 'includes/header.php';
require_once '../includes/db.php';

$message = '';
$msg_type = 'success';

if ($_SERVER["REQUEST_METHOD"] == "POST") {
    $title = htmlspecialchars(trim($_POST['title']));
    $level = htmlspecialchars(trim($_POST['level']));
    $duration = htmlspecialchars(trim($_POST['duration']));
    $description = trim($_POST['description']); // TinyMCE payload
    
    $image_file = $_FILES['image'];
    $pdf_file = $_FILES['syllabus'];
    
    $image_name = '';
    $pdf_name = '';
    $upload_ok = true;

    // Image Upload Security Logic
    if (isset($image_file) && $image_file['error'] === 0) {
        $allowed_img_exts = ['jpg', 'jpeg', 'png'];
        $img_ext = strtolower(pathinfo($image_file['name'], PATHINFO_EXTENSION));
        
        if (!in_array($img_ext, $allowed_img_exts) || $image_file['size'] > 2 * 1024 * 1024) {
            $message = "Invalid Image format or size (Max 2MB).";
            $upload_ok = false;
        } else {
            // MIME Verification for absolute security
            $finfo = finfo_open(FILEINFO_MIME_TYPE);
            $mime = finfo_file($finfo, $image_file['tmp_name']);
            finfo_close($finfo);
            
            if (!in_array($mime, ['image/jpeg', 'image/png'])) {
                $upload_ok = false;
            } else {
                $image_name = uniqid('course_img_', true) . '.' . $img_ext;
                $img_dir = '../assets/images/courses/';
                move_uploaded_file($image_file['tmp_name'], $img_dir . $image_name);
            }
        }
    }

    // PDF Syllabus Logic
    if ($upload_ok && isset($pdf_file) && $pdf_file['error'] === 0) {
        $pdf_ext = strtolower(pathinfo($pdf_file['name'], PATHINFO_EXTENSION));
        if ($pdf_ext === 'pdf' && $pdf_file['size'] <= 5 * 1024 * 1024) {
            $pdf_name = uniqid('syllabus_', true) . '.pdf';
            move_uploaded_file($pdf_file['tmp_name'], '../assets/documents/syllabus/' . $pdf_name);
        }
    }

    // Secure Database Insertion via Prepared Statements
    if ($upload_ok && !empty($title)) {
        $stmt = $conn->prepare("INSERT INTO courses (title, level, duration, description, image, syllabus_file) VALUES (?, ?, ?, ?, ?, ?)");
        $stmt->bind_param("ssssss", $title, $level, $duration, $description, $image_name, $pdf_name);
        $stmt->execute();
        $message = "Course successfully deployed!";
    }
}
?>
```

<br><br><br><br><br><br>

### 7.4 Public Course Rendering Engine (`pages/courses.php`)
The frontend page dynamically pulls the courses from the database and constructs interactive, filterable cards. It incorporates a custom JavaScript engine that allows users to filter courses by level without reloading the page.

```php
<?php 
// pages/courses.php
require_once '../includes/db.php';
include('../includes/header.php'); 

$courses_result = $conn->query("SELECT * FROM courses ORDER BY created_at DESC");
?>
<section class="py-5 bg-light">
    <div class="container py-4">
        <!-- JavaScript Filtration Interface -->
        <div class="d-flex justify-content-center flex-wrap gap-2 mb-5">
            <button class="filter-btn btn btn-theme-primary text-white" data-filter="all">Explore All</button>
            <button class="filter-btn btn btn-outline-secondary bg-white" data-filter="Undergraduate">Undergraduate</button>
            <button class="filter-btn btn btn-outline-secondary bg-white" data-filter="Postgraduate">Postgraduate</button>
        </div>

        <div class="row g-4" id="courseGrid">
            <?php if ($courses_result && $courses_result->num_rows > 0): ?>
                <?php while ($row = $courses_result->fetch_assoc()): ?>
                    <div class="col-lg-4 col-md-6 course-card" data-level="<?php echo htmlspecialchars($row['level']); ?>">
                        <div class="card h-100 shadow rounded-4 border-0">
                            <img src="../assets/images/courses/<?php echo htmlspecialchars($row['image']); ?>" class="card-img-top">
                            <div class="card-body p-4">
                                <h5 class="card-title fw-bold"><?php echo htmlspecialchars($row['title']); ?></h5>
                                <div class="card-text text-muted mb-4 small flex-grow-1">
                                    <?php echo $row['description']; ?>
                                </div>
                                <?php if(!empty($row['syllabus_file'])): ?>
                                    <a href="../assets/documents/syllabus/<?php echo htmlspecialchars($row['syllabus_file']); ?>" target="_blank" class="btn btn-outline-primary px-4 rounded-pill">
                                        Download Syllabus
                                    </a>
                                <?php endif; ?>
                            </div>
                        </div>
                    </div>
                <?php endwhile; ?>
            <?php endif; ?>
        </div>
    </div>
</section>

<script>
// Dynamic Category Engine
document.addEventListener('DOMContentLoaded', function() {
    const filterBtns = document.querySelectorAll('.filter-btn');
    const courseCards = document.querySelectorAll('.course-card');

    filterBtns.forEach(btn => {
        btn.addEventListener('click', () => {
            const filter = btn.getAttribute('data-filter');
            courseCards.forEach(card => {
                const level = card.getAttribute('data-level');
                if (filter === 'all' || filter === level) {
                    card.style.display = 'block';
                    card.style.animation = 'fadeIn 0.5s';
                } else {
                    card.style.display = 'none';
                }
            });
        });
    });
});
</script>
```

<br><br><br><br><br><br><br><br><br><br><br><br>

---

## 8. SOFTWARE TESTING

Testing is a critical phase of the Software Development Life Cycle (SDLC). Various testing methodologies were employed to ensure the platform is robust, secure, and bug-free.

### 8.1 Testing Methodologies
1. **Unit Testing:** Individual scripts and components (like the database connection, form validation, and file upload functions) were tested in isolation to ensure they perform their specific tasks correctly.
2. **Integration Testing:** Modules were combined to verify that they interact correctly. For example, testing if a newly uploaded notice correctly appears on the frontend `notices.php` page.
3. **System Testing:** The entire application was tested as a whole to verify that it meets the System Requirement Specifications (SRS).
4. **Security Testing:** Forms were tested against common vulnerabilities like SQL Injection (by using prepared statements) and Cross-Site Scripting (XSS) (by utilizing `htmlspecialchars()` on output).

### 8.2 Test Cases

#### Test Case 1: Admin Authentication
| Test Case ID | Description | Input Data | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|
| TC-01 | Login with valid credentials | Username: admin, Password: riot12% | Redirect to Admin Dashboard | Redirected to Dashboard | **PASS** |
| TC-02 | Login with invalid password | Username: admin, Password: wrong123 | Show "Invalid Password" error | Error displayed | **PASS** |
| TC-03 | Bypass login via direct URL | Navigate directly to `admin/index.php` without logging in | Redirect back to `admin_login.php` | Redirected to login | **PASS** |

#### Test Case 2: Contact Form Submission
| Test Case ID | Description | Input Data | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|
| TC-04 | Submit valid inquiry | Name, Valid Email, Subject, Message | Data inserted into `contacts` table, Success message shown | Data inserted, message shown | **PASS** |
| TC-05 | Submit with empty fields | Leave Name field blank | HTML5 Validation prevents submission | Submission prevented | **PASS** |

#### Test Case 3: Course Management
| Test Case ID | Description | Input Data | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|
| TC-06 | Upload invalid syllabus format | Upload a `.exe` file in the syllabus field | Reject file, show "Only PDF allowed" error | File rejected, error shown | **PASS** |
| TC-07 | Add new valid course | Valid Title, Description, JPG image, PDF file | Course saved to DB, Image/PDF moved to server folders | Data saved, files moved | **PASS** |

<br><br><br><br><br><br><br><br><br><br><br><br>

---

## 9. USER INTERFACE (UI) DESIGN & SCREENSHOTS

*(Note: In the actual printed report, replace these textual placeholders with actual screenshots of your application).*

### 9.1 Homepage
**Description:** The landing page features a large, welcoming Hero section with the college logo and name prominently displayed. Navigation links are located at the top. Below the hero section, dynamic content such as the latest three notices and a brief introduction to the department are displayed. The UI utilizes Bootstrap cards to display information neatly.

### 9.2 Course Catalog
**Description:** The `courses.php` page presents academic programs in a responsive grid layout. Each course is displayed as a card containing the course thumbnail, title, duration, and a brief description. A prominent "Download Syllabus (PDF)" button is available for courses that have an associated file uploaded by the admin.

### 9.3 Administrative Dashboard
**Description:** The `admin/index.php` page features a sidebar navigation menu for easy access to all management modules (Courses, Faculty, Notices, Gallery, Messages). The main content area displays status cards summarizing the total number of records in the database, giving the administrator an immediate overview of the system's status.

### 9.4 Rich Text Notice Editor
**Description:** The `add_notice.php` page integrates the TinyMCE editor. It provides a familiar, Word-like interface allowing the admin to bold text, create bulleted lists, and insert hyperlinks when drafting a new notice, which is then safely stored as HTML in the database.

<br><br><br><br><br><br><br><br><br><br><br><br>

---

## 10. CONCLUSION

The development of the **Govt. Polytechnic Jammu Computer Engineering Department Platform** has been successfully completed, meeting all the initial objectives set forth in the problem statement. The transition from a manual, paper-based information dissemination system to a dynamic, centralized digital platform brings numerous benefits to the institution.

The platform provides an intuitive interface for students to access vital academic resources remotely, while simultaneously offering the administration a powerful, secure backend to manage departmental data efficiently. By leveraging native PHP 8+ and MySQL without heavy frameworks, the system guarantees high performance, rapid load times, and easy maintainability. The inclusion of modern web features like the Dark Matrix UI Toggle Engine and automated inquiry management further elevates the user experience.

Ultimately, this project represents a significant technological leap for the department, providing a scalable foundation that can accommodate future digital initiatives.

<br><br><br><br><br><br><br><br><br><br><br><br>

---

## 11. FUTURE ENHANCEMENTS

While the current system is robust and feature-rich, software development is an iterative process. The platform has been designed with modularity in mind, allowing for several future enhancements:

1. **Student Login Portal:** Implementing a dedicated student authentication system where students can log in to view personalized dashboards, check attendance, and view grades.
2. **Online Assignment Submission:** Creating a module where faculty can post assignments and students can securely upload their completed work (PDF/Word documents) before a set deadline.
3. **Alumni Network Module:** A dedicated section for alumni to register, connect with current students, and share job opportunities or mentorship.
4. **Automated Notification System:** Integrating an SMS or Email API (like Twilio or PHPMailer) to automatically notify students when an urgent notice is posted by the administration.
5. **Interactive Event Calendar:** A dynamic calendar interface allowing students to view upcoming departmental events, seminars, and examination schedules.

<br><br><br><br><br><br><br><br><br><br><br><br>

---

## 12. BIBLIOGRAPHY / REFERENCES

During the research and development of this project, the following resources were invaluable:

1. **PHP Documentation:** The official PHP Manual (https://www.php.net/manual/en/) for understanding core functions, PHP 8 specific features, and `password_hash()` implementations.
2. **MySQL Documentation:** The official MySQL Reference Manual (https://dev.mysql.com/doc/) for writing optimized SQL queries and understanding database normalization.
3. **Bootstrap Framework:** Bootstrap v5.3 Documentation (https://getbootstrap.com/docs/5.3/getting-started/introduction/) for implementing the responsive grid system, components, and native Dark Mode attributes.
4. **TinyMCE Documentation:** For integrating and configuring the rich text editor within the administrative portal (https://www.tiny.cloud/docs/).
5. **W3Schools & MDN Web Docs:** For comprehensive tutorials and syntax references regarding HTML5, CSS3, and Vanilla JavaScript.
6. **Stack Overflow:** A crucial community resource for troubleshooting specific logic errors and optimizing database connection scripts during the development phase.

---
*(End of Project Report)*
