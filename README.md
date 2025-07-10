# login2explore_TishaJain
Macro Project of login2explore

Student Enrollment Form
Description
This is a basic student enrollment form that allows users to add new student records, retrieve existing data using a roll number, and update records if needed. The form interacts directly with the JsonPowerDB (JPDB) database using JavaScript and jQuery, without any backend server.

Features
Enter roll number to check if the student already exists.

If found, details are auto-filled and editable.

If not found, user can input new student data.

Supports Save, Update, and Reset operations.

Fully functional client-side integration with JPDB.

Technologies Used
HTML, CSS (basic)

JavaScript

jQuery

JsonPowerDB (JPDB)

Why JsonPowerDB?
Easy integration with frontend (no backend required)

Works entirely with JSON data

Fast and lightweight

Ideal for prototypes and quick internal tools

How It Works
User enters a Roll Number.

On blur (losing focus), it checks in the database:

If the record exists, fields are auto-filled and Update is enabled.

If not, user can fill the form manually and Save it.

Reset button clears everything and enables Roll No input again.

Project Setup
No special setup required.
Just open the HTML file in your browser.

Make sure:

You’re connected to the internet (to load external JS and access JPDB).

You have a valid JPDB token and have set up the database and relation names accordingly.

Release History
v1.0 – July 10, 2025
Initial release with:

Save student data

Update existing student record

Form reset and field control

License
This is an open project for learning and demonstration purposes.
You are free to use and modify it.
