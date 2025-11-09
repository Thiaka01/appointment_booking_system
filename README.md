# appointment_booking_system
A fully functional Appointment Booking System built using XAMPP, VS CODE and a stack consisting of HTML, CSS, JavaScript, PHP and MySQL
This project demonstrates real-world full-stack development skills including authentication,CRUD operations, dynamic UI components, and database-driven interactions.

**Key Features**
1 User Authentication

a.User registration system

b.Secure login using hashed passwords

c.Session-based authentication

2.Appointment Booking

a. Users can book available time slots

b.Prevent double-booking using database validation(Ensures multiple users can book the same day but not the same time)

c.Real-time date & time selection(Ensures that booking is between valid working hours[7 am to 9 pm] )

d.Dynamic calendar UI using JavaScript

e.Availability slots displayed visually

3. Admin Dashboard

a.Admin can view all appointments

b.Manage/edit/delete bookings

c.Filter appointments by date

d.Responsive dashboard layout using CSS Grid & Flexbox

4. Notifications 

a.Email/SMS confirmation for booked appointments

b.Reminder system to notify users

c.Custom message templates

5.CRUD Functionality

The system supports complete CRUD operations:

Create: New appointments

Read: View bookings & user details

Update: Modify appointment time/date

Delete: Remove appointments

All operations interact directly with a MySQL database.

PROJECT STRUCTURE:
appointment_system/
│
├── index.php
├── register.php
├── login.php
├── book.php
├── admin.php
├── logout.php
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
├── config/
│   └── db.php
│
└── database/
    └── appointments_db.sql


Technologies Used
1.Frontend

HTML5

CSS3 (Grid & Flexbox layout)

JavaScript (calendar, validation, dynamic updates)

2. Backend

PHP (procedural + MySQLi/PDO)

MySQL database

XAMPP for local hosting

 Tools

1.VS Code (source code editing)

2.phpMyAdmin (database management)

 Extra Features 

Dynamic calendar with clickable dates

Disabled past dates

Auto-refresh schedule view

Mobile-responsive UI

Real-time error messages & validation feedback

 How to Run the Project

1.Install XAMPP

2.Clone this repository into:

C:\xampp\htdocs\appointment_system


3.Start Apache and MySQL

4.Import the database file from /database/appointments_db.sql

5.Visit the app in your browser:

http://localhost/appointment_system/


This project demonstrates:

1.full-stack understanding

2.secure login system

3.practical UI/UX design

4.logical backend development

5.real MySQL integration

6.calendar + scheduling logic

7.responsive layout

It is suitable for:
