# Team Management Guide: 5-Person Development Team

Aapka project ek "College Department Management System" hai. Isse fast aur clean tarike se banane ke liye is guide ka use karein.

## 👥 Role Matrix

### 1. Lead Developer (The Brain)
- **Kaam**: Database schema design karna aur pure project ka folder structure set karna.
- **Goal**: Ye ensure karna ki code modular ho (includes ka use) aur database connections securely handle hon.
- **Guidance**: Use `mysqli` prepared statements for everything.

### 2. Frontend Developer (The Artist)
- **Kaam**: `index.php` aur UI components (Navbar, Footer, Stats card) design karna.
- **Goal**: Look premium hona chahiye (vibrant colors, glassmorphism). AOS animations aur dark mode toggle setup karna.
- **Guidance**: Bootstrap 5 use karein par custom CSS se "wow" factor layein.

### 3. Backend Specialist (The Guard)
- **Kaam**: Admin login, session management aur content management (Faculty/Notices add/delete).
- **Goal**: Secure login system jahan bina session ke access na ho.
- **Guidance**: `password_hash()` aur `password_verify()` mandatory hai.

### 4. Feature Developer (The Specialist)
- **Kaam**: Specialized modules jaise Gallery upload, logic for dynamic courses, aur Contact form database logic.
- **Goal**: Image uploads aur file handling (Syllabus PDF) ko smooth banana.
- **Guidance**: Proper directory permissions aur file extension validation par focus karein.

### 5. QA & Documentation (The Auditor)
- **Kaam**: Pure system ko test karna (XSS attack, SQL injection) aur technical documentation banana.
- **Goal**: Taaki client dashboard dekh kar confuse na ho.
- **Guidance**: Setup scripts (`setup_db.php`) banayein taaki database ek click me ready ho jaye.

---

## 🛠️ Management Workflow (Aapke liye)

Aapko unhe guide karne ke liye ye 3 steps follow karne chahiye:

1.  **Version Control (Git)**:
    - Sabse pehle GitHub par repo banayein.
    - Har dev ko apni branch par kaam karne kahein (`feature/admin`, `feature/ui`).
    - Main branch par code aapki approval (Pull Request) ke baad hi jaye.

2.  **Daily Sync (10-min Call)**:
    - Roz puchiye: *Kal kya kiya? Aaj kya karoge? Koi blocker hai?*
    - Isse team track par rehti hai.

3.  **Code Review**:
    - Unhe bole ki code share karne se pehle `htmlspecialchars()` aur prepared statements check karein.
    - Logic repeats na ho (DRY - Don't Repeat Yourself).

## 📅 Timeline Strategy (2 Weeks)

- **Week 1 (Foundation)**: DB Design + Landing Page UI + Admin Login logic.
- **Week 2 (Core Modules)**: Faculty/Notice Management + Gallery + Testing & Final Polish.

> [!TIP]
> **Pro Tip**: Pehle Database schema final karein. Agar DB change hota hai bich me, toh pura backend code hil jata hai.
