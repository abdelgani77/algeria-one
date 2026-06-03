# Algeria One 🇩🇿

## Government Digital Services Platform for Algeria

Algeria One is a unified e-Government platform designed to provide citizens, businesses, and government institutions with secure and efficient digital services.

The project aims to simplify administrative procedures, reduce paperwork, improve transparency, and accelerate digital transformation across Algeria.

---

## Features

### Citizen Services

* Birth Certificate Requests
* Residence Certificate Requests
* National ID Applications
* Passport Applications
* Administrative Appointment Booking
* Digital Document Verification
* Request Tracking System

### Government Services

* Ministry Service Management
* Digital Forms
* Online Requests Processing
* Citizen Records Management
* Notifications & Alerts

### Security

* Secure Authentication
* OTP Verification
* Role-Based Access Control
* Password Encryption
* Session Protection

### Dashboard

* User Profile Management
* Request History
* Uploaded Documents
* Real-Time Status Tracking

---

## Project Structure

```text
algeria-one/
├── config/
├── includes/
├── lang/
├── assets/
├── public/
├── admin/
├── api/
├── storage/
├── database.sql
├── .htaccess
├── composer.json
└── README.md
```

---

## Technologies

### Backend

* PHP 8+
* MySQL 8
* PDO

### Frontend

* HTML5
* CSS3
* JavaScript
* Bootstrap 5

### Security

* Password Hashing
* CSRF Protection
* OTP Authentication
* Secure Sessions

---

## Database

Main tables:

* users
* ministries
* services
* requests
* documents

Import the database using:

```sql
database.sql
```

---

## Installation

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/algeria-one.git
```

### 2. Move Project

Place the project inside:

```text
htdocs/
```

or

```text
www/
```

### 3. Create Database

```sql
CREATE DATABASE algeria_one;
```

Import:

```text
database.sql
```

### 4. Configure Database

Edit:

```php
config/database.php
```

```php
define('DB_HOST', 'localhost');
define('DB_NAME', 'algeria_one');
define('DB_USER', 'root');
define('DB_PASS', '');
```

### 5. Start Server

```bash
http://localhost/algeria-one/public
```

---

## User Roles

### Citizen

* Submit Requests
* Upload Documents
* Track Applications

### Employee

* Review Requests
* Process Documents
* Update Status

### Administrator

* Manage Users
* Manage Ministries
* Manage Services
* System Settings

---

## Future Roadmap

* Electronic Signature
* Mobile Application
* AI Assistant
* National Digital Identity
* Online Payments
* QR Verification
* Arabic / French / Tamazight Support
* Government API Integration

---

## Vision

To build a modern digital government platform that connects citizens with public services through a secure, fast, and user-friendly experience.

---

## License

MIT License

Copyright © 2026 Algeria One
