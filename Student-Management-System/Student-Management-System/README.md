# Student_Database-Management

This is the repository for the dbms project of File Organization and Database Management Laboratory MA39204 for the Spring semester 2022-23, at IIT Kharagpur.
A student database management system built using Flask and MySQL as backend.

## 1. Installation  

VS Code and XAMPP need to be installed.

And also Python need to be installed

```bash
pip install python
```

Then install the required packages using the following command
```bash
python.exe -m pip install --upgrade pip
pip install flask
pip install Flask-SQLAlchemy
pip install Flask-Mail
pip install Flask-Login
```
If you want to use the mysql database, then install the following packages
```bash
python.exe -m pip install mysqlclient
python.exe -m pip install mysql-connector-python
```

And also install 'HTML Snippets' and 'Python' extensions in VS Code

## 2. Database connection

Open the folder "Student Management System" in the VS Code.

Open the XAMPP Control Panel and start the Apache and MySQL and click on the admin button of mysql.

Create a database and name it 'studentdbms' and import the 'students.sql' file from the 'student management' folder.


## 3. How to run the code:

Go to the 'main.py' file in the 'student manager' folder and run it in VS Code. 

Then go to the browser and enter the url displayed on the terminal ("http://127.0.0.1:5000").

## 4. Login 

Create an account using the sign up button and login in to the site.

Then you can do the operations on the student database as explained in the report.
