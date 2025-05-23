# PHP-project-task
Password Manager

Overview

A PHP-based web application for secure password management. Users can register, log in, generate random passwords, save them with website names, update their account password, and log out. Built with OOP, MySQL, and AES encryption.

Features





Register with username and hashed password (BCRYPT).



Log in securely.



Generate passwords with customizable parameters.



Save passwords with timestamps.



Update account password.



Log out to end session.



Secure: hashed passwords, PDO prepared statements, XSS protection.

Requirements





XAMPP (Apache, PHP 7.4+, MySQL).



PHP extensions: pdo_mysql, openssl.



Modern web browser.

Installation





Install XAMPP from apachefriends.org.



Start Apache and MySQL in XAMPP Control Panel.



Create folder password_manager in C:\xampp\htdocs.



Place index.php in C:\xampp\htdocs\password_manager.



Fix XAMPP dashboard redirect:





Rename C:\xampp\htdocs\index.php (if it redirects to /dashboard/).



Access project at http://localhost/password_manager/.



Set up MySQL:





In phpMyAdmin, create database password_manager.



Create users and passwords tables (use provided SQL schema).



Verify PHP: Ensure pdo_mysql and openssl are enabled in php.ini.

Usage





Register: Enter username and password, click "Register".



Login: Use credentials to access the interface.



Generate Password: Set length and character types, click "Generate".



Save Password: Enter website name and save the password.



Change Password: Enter new password and update.



Logout: Click "Logout" to end session.

UML Diagram





Provided in PlantUML format. Generate using plantuml.com.

Troubleshooting





Registration Issues:





Check error messages (e.g., "Username already exists").



Verify database/tables exist in phpMyAdmin.



Check logs (C:\xampp\apache\logs\error.log).



Ensure openssl is enabled in php.ini.



XAMPP Dashboard Redirect:





Rename C:\xampp\htdocs\index.php.



Use http://localhost/password_manager/.



Database Errors:





Confirm MySQL is running.



Update database password in index.php if needed.

Submission





Screenshots: Database tables, interface (register, login, password table, logout).



Report: Confirm all features work, note error handling.



Code: Submit index.php, SQL schema, UML diagram.
