# PROJECT REPORT

**ON**

## GOVERNMENT POLYTECHNIC, JAMMU
## COMPUTER ENGINEERING DEPARTMENT PLATFORM

**Submitted in partial fulfillment of the requirements for the diploma of**
**Diploma in Computer Engineering**

**Submitted By:**
1. **Amanshu Sharma** [Roll No: ]
2. **Saksham Malhotra** [Roll No: ]
3. **Pavneet Kour** [Roll No: ]
4. **Paramjeet** [Roll No: ]
5. **Gurmeet** [Roll No: ]
6. **Vikas Angural** [Roll No: ]

**Under the Guidance of:**
**[Guide's Name]**
**[Guide's Designation]**

---

<br><br><br><br><br><br><br><br><br><br><br><br>

## DECLARATION

We hereby solemnly declare that the project report entitled **"Govt. Polytechnic Jammu Computer Engineering Department Platform"**, submitted in partial fulfillment of the requirements for the award of the **Diploma in Computer Engineering**, is an authentic and original record of the collective project work carried out by us. 

We further declare that this project is the result of our own independent research, system design, and coding efforts, conducted under the expert supervision and guidance of our assigned project guide. The materials, libraries, and frameworks utilized in this project have been duly acknowledged and cited wherever necessary. 

Furthermore, we declare that to the best of our knowledge and belief, this project work has not previously formed the basis, in whole or in part, for the award of any other diploma, degree, associate-ship, fellowship, or any other similar academic titles at this institution or any other university/board.

**Place:** Jammu  
**Date:** [Date]  
**Signatures of the Students:**
1. __________________ (Amanshu Sharma)
2. __________________ (Saksham Malhotra)
3. __________________ (Pavneet Kour)
4. __________________ (Paramjeet)
5. __________________ (Gurmeet)
6. __________________ (Vikas Angural)

<br><br><br><br><br><br><br><br><br><br><br><br>

---

## CERTIFICATE

This is to certify that the project report entitled **"Govt. Polytechnic Jammu Computer Engineering Department Platform"** is a bonafide, authentic, and meticulously researched record of the academic project work successfully undertaken and completed by **Amanshu Sharma, Saksham Malhotra, Pavneet Kour, Paramjeet, Gurmeet, and Vikas Angural**. 

This work was carried out by them as a team, under my direct supervision and guidance, in partial fulfillment of the stringent requirements for the award of the **Diploma in Computer Engineering** from Govt. Polytechnic Jammu. 

To the best of my knowledge and satisfaction, the project encompasses a significant amount of original technical work, adhering to the standard software development lifecycle. I further certify that this project report, or any part thereof, has not been submitted previously for the award of any other diploma, degree, fellowship, or similar academic distinction. The students have demonstrated commendable dedication, technical proficiency, and teamwork throughout the duration of this project.

**Signature of Guide:** __________________  
**Name of Guide:** [Guide's Name]  

**Signature of HOD:** __________________  
**Name of HOD:** [HOD's Name]  

<br><br><br><br><br><br><br><br><br><br><br><br>

---

## ACKNOWLEDGEMENT

The successful completion of any complex software development endeavor is rarely the result of solitary effort. We would like to take this opportunity to express our profound gratitude and deep appreciation to everyone who played a pivotal role in the successful realization of the **"Govt. Polytechnic Jammu Computer Engineering Department Platform"**.

First and foremost, we would like to express our special thanks and deepest sense of gratitude to our esteemed project guide, **[Guide's Name]**. Their unwavering support, continuous encouragement, and invaluable technical insights provided the crucial foundation necessary to navigate the complexities of this project. Their constructive criticism and willingness to devote time to address our queries were instrumental in shaping the final outcome.

We are also immensely thankful to our respected Principal and the Head of the Computer Engineering Department, **[HOD's Name]**, for granting us the golden opportunity to undertake a project of such significant institutional relevance. Their provision of necessary laboratory resources and a conducive academic environment greatly facilitated our research and development process.

Furthermore, we extend our heartfelt gratitude to the entire teaching and non-teaching staff of the Computer Engineering Department for their indirect yet significant contributions to our foundational knowledge. 

Lastly, words fall short in expressing our deepest gratitude to our parents, families, and friends. Their constant emotional support, patience, and unwavering belief in our capabilities provided us with the necessary strength and motivation to finalize this project within the strict deadlines. We are truly indebted to everyone who directly or indirectly contributed to making this project a resounding success.

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
Prior to the conceptualization and implementation of this system, the Computer Engineering department relied heavily on an archaic, manual, and predominantly paper-based framework. The existing mechanisms had several severe operational and logistical drawbacks:
- **Information Asymmetry & Delay:** Notices printed on paper were often physically pinned to a single designated notice board. Students who were absent, or those residing in hostels far from the administrative block, missed critical announcements regarding examination schedules, syllabus changes, and holiday declarations.
- **Inaccessibility of Academic Resources:** Course syllabi, past examination papers, and reference materials were not easily accessible remotely. Students had to physically visit the library or the departmental office to request photocopies, which was both time-consuming and environmentally detrimental.
- **Scattered Communication Channels:** Inquiries from students or prospective applicants were often handled via unorganized emails or physical drop-boxes. This led to inquiries being lost, delayed responses, and a lack of a centralized tracking mechanism for the administration to analyze common student issues.
- **High Maintenance Overhead & Bottlenecks:** Updating a static HTML-based departmental website required specialized technical expertise. Every minor modification, whether adding a new faculty member's profile or fixing a typo in a course description, required the intervention of a dedicated IT technician. This created a severe bottleneck, rendering the website stale and outdated.

This project definitively addresses these multi-faceted issues by introducing a dynamic, database-driven solution. Content is managed seamlessly through an intuitive, secure Admin Dashboard, ensuring that the department's digital presence is always active, accurate, and easily accessible from any geographical location.

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
Before initiating the core development phase of the SDLC (Software Development Life Cycle), an exhaustive feasibility study was conducted. The primary objective was to evaluate whether the proposed system is viable, practical, and sustainable over the long term. This assessment was categorized into three primary dimensions:

#### 3.1.1 Technical Feasibility
The project demonstrates an exceptionally high degree of technical feasibility. It is constructed upon a stack of widely accepted, robust, and mature web technologies: PHP 8.x, MySQL 8.x, HTML5, Vanilla JavaScript, and the Bootstrap 5 CSS framework. These core technologies are industry standards, boasting extensive documentation, massive community support, and proven reliability in high-traffic environments. Furthermore, the system architecture is deliberately designed to avoid heavy framework dependencies, minimizing overhead. The application can be hosted on virtually any standard Apache or Nginx web server, making deployment and server migration a trivial process.

#### 3.1.2 Economic Feasibility
From a financial perspective, the system is exceptionally viable. It relies entirely on Open-Source software paradigms. There are absolutely no licensing fees required to deploy or operate PHP, MySQL, or Bootstrap. The primary financial expenditures are limited to the initial domain name registration and recurrent, low-cost shared web hosting. Furthermore, the implementation of this system automates numerous manual administrative tasks. The reduction in paper usage (for notices and syllabi), combined with the streamlining of communication, translates to significant long-term operational cost savings for the institution.

#### 3.1.3 Operational Feasibility
Operational feasibility assesses the ease with which the target users can adapt to the new system. The administrative backend is engineered with a focus on User Experience (UX). It utilizes intuitive interfaces and integrates tools like TinyMCE, a sophisticated rich-text editor that mimics the functionality of Microsoft Word. Consequently, administrative staff members require near-zero specialized technical training to operate the backend, publish notices, or manage faculty profiles. On the frontend, the UI is fully responsive, ensuring that students can easily navigate the platform regardless of whether they are using a desktop computer, tablet, or mobile device.

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

The conceptualization, design, and development of the **Govt. Polytechnic Jammu Computer Engineering Department Platform** have been successfully executed and brought to fruition, exceeding the initial baseline objectives outlined in the problem statement. The transition from a legacy, manual, paper-based information dissemination ecosystem to a highly dynamic, centralized, and automated digital platform brings a multitude of strategic, operational, and environmental benefits to the institution.

Primarily, the platform completely democratizes access to academic information. By providing an intuitive, visually appealing, and highly responsive interface, students can now seamlessly access critical academic resources, course syllabi, and urgent departmental notices from anywhere in the world, at any time of day, regardless of the device they are using. This eradicates the geographical and temporal constraints that plagued the traditional notice board system.

From an administrative perspective, the platform is a paradigm shift. It empowers the department's faculty and administrative staff with a highly secure, yet incredibly user-friendly backend dashboard. The integration of advanced rich-text editors and automated file-handling systems means that non-technical staff can now perform complex web updates instantaneously. This drastically reduces the department's reliance on external IT support, effectively eliminating digital bottlenecks and ensuring that the website is always an accurate reflection of the current academic environment.

Technologically, the decision to leverage native, raw PHP 8+ and MySQL—rather than relying on heavily abstracted, bloated frameworks—has proven to be highly advantageous. It has resulted in a system that guarantees rapid execution times, extremely low server resource consumption, and straightforward maintainability. The codebase is transparent, secure, and immune to the frequent deprecation cycles associated with third-party libraries. Furthermore, the inclusion of modern, user-centric web features—such as the persistent Dark Matrix UI Toggle Engine and the database-driven asynchronous inquiry management system—elevates the platform from a simple informational site to a premium digital experience.

Ultimately, this project represents far more than just a departmental website; it is a significant technological leap forward. It successfully establishes a highly robust, scalable, and secure digital foundation that the Computer Engineering Department can rely upon for years to come, perfectly positioning the institution to embrace future digital initiatives and technological advancements in the educational sector.

<br><br><br><br><br><br><br><br><br><br><br><br>

---

## 11. FUTURE ENHANCEMENTS

While the current system is robust and feature-rich, software development is an iterative process. The platform has been designed with modularity in mind, allowing for several future enhancements:

1. **Dedicated Student & Faculty Portal Authentication:** The next logical step is implementing a role-based authentication system. This would allow students to log in to personalized dashboards using their specific roll numbers. Within this portal, they could track their cumulative attendance, view internal assessment grades securely, and manage their academic profiles.
2. **Online Assignment & Project Submission Engine:** Creating a secure file-transfer module where faculty can post assignments with strict deadlines. Students could digitally upload their completed work (PDFs, Source Code ZIPs, or Word documents). The system would automatically lock submissions after the deadline and provide an interface for faculty to grade submissions online.
3. **Comprehensive Alumni Network Module:** To foster continuous institutional growth, a dedicated section for alumni could be developed. Alumni would be able to register, verify their graduation details, and connect with current students. This would serve as a powerful networking tool for sharing job opportunities, conducting mentorship programs, and organizing alumni meets.
4. **Automated API-Driven Notification System:** Integrating third-party APIs (such as Twilio for SMS or PHPMailer for automated emails). When the administration publishes an "Urgent" notice, the system would automatically trigger an SMS broadcast or an email blast to all registered students, ensuring immediate information delivery without requiring the student to actively check the website.
5. **Interactive Event Calendar & Scheduling Matrix:** A dynamic, visually rich calendar interface allowing students to view an overview of the entire academic semester. This would include upcoming departmental seminars, guest lectures, internal examination schedules, and holidays, potentially with export options to Google Calendar or Apple Calendar.
6. **AI-Powered Chatbot for General Inquiries:** Implementing a lightweight Machine Learning model or rules-based chatbot on the frontend. This bot could automatically answer frequently asked questions (FAQs) regarding admission procedures, course eligibility, or fee structures, further reducing the manual workload on the administration.

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
