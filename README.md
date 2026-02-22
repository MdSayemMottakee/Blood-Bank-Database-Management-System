# Blood Bank Database Management System (BBDMS)

[![PHP Version](https://img.shields.io/badge/php-%3E%3D7.4-blue.svg)](https://www.php.net/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A robust and user-friendly web application designed to bridge the gap between blood donors and those in need. This system manages donor records, hospital requests, and patient requirements efficiently.

## 🚀 Features

### For Donors
*   **Easy Registration:** Simple sign-up process for new donors.
*   **Account Management:** Update profile information and donation history.
*   **Search Facility:** Find other donors or blood banks in the vicinity.

### For Hospitals & Staff
*   **Request Management:** Place and track blood requests.
*   **Inventory Tracking:** Monitor available blood units.
*   **Staff Accounts:** Dedicated portal for hospital personnel.

### For Administrators
*   **Global Dashboard:** Overview of all system activities.
*   **User Management:** Approve, modify, or remove users/hospitals.
*   **Reporting:** Generate reports on donations and requests.

## 🛠️ Tech Stack

*   **Backend:** PHP (PDO for secure database interactions)
*   **Database:** MySQL
*   **Frontend:** HTML5, CSS3, JavaScript
*   **UI Framework:** Bootstrap 4
*   **Icons:** Font Awesome

## 📦 Installation Guide

1.  **Environment Setup:**
    *   Install a local server like **XAMPP** or **WAMP**.
    *   Ensure Apache and MySQL services are running.

2.  **Database Configuration:**
    *   Open `phpMyAdmin` (usually `http://localhost/phpmyadmin`).
    *   Create a new database named `bbdms`.
    *   Import the `bbdms.sql` file provided in the root directory.

3.  **Project Deployment:**
    *   Clone or download this repository.
    *   Move the project folder to your local server's root directory (e.g., `htdocs` for XAMPP or `www` for WAMP).

4.  **Configuration:**
    *   Edit `includes/config.php` to update your database credentials if different from default.

5.  **Access:**
    *   User Portal: `http://localhost/Blood-Bank-Database-Management-System/index.php`
    *   Admin Portal: `http://localhost/Blood-Bank-Database-Management-System/admin/index.php`

## 📸 Screenshots

*(Add screenshots here after implementation)*

## 📄 License

This project is licensed under the MIT License - see the `LICENSE` file for details.
