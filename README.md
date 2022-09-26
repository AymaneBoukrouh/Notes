# Notes

### About

A very simple Web Application for simple note management written in PHP

### Features

- User Login System, Email Verification, Password Reset
- Note Management: Add, Edit, Delete, View

### Requirements

- MySQL
- PHPMailer

### Initialization

- Initialize MySQL database by running `assets/db/init_db.sql`
- Set environment variables in Apache

### Configuration Files

- MySQL authentication `modules/db/auth.php`
- SMTP authentication `modules/phpmailer/auth.php`
