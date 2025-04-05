# Employee Management System

This is a Employee management system built using **Django 4**, **HTML 5**, **CSS 3**, and **Bootstrap 5**.

# 1. Login to admin
![login](https://github.com/KiranKumarMalik/Employee-Management-System-Using-Django/blob/b19348c2e6624325009124f741b94f2a4ff7c294/ss/Screenshot%202025-04-04%20224912.png)

<h3>Admin Credentials</h3>
Username: admin <br>
Password: admin123

# 2. Admin Dashboard (Number of employees, departments and positions)
![dashboard](https://github.com/KiranKumarMalik/Employee-Management-System-Using-Django/blob/de8141aad0dcc7c3b49ccdf125940c2969e9c264/ss/Screenshot%202025-04-04%20221345.png)

# 3. To add department
![dep](https://github.com/KiranKumarMalik/Employee-Management-System-Using-Django/blob/bad7a6c3dc46068ad128a041f820ee07a761a264/ss/Screenshot%202025-04-04%20221412.png)

![add](https://github.com/KiranKumarMalik/Employee-Management-System-Using-Django/blob/bad7a6c3dc46068ad128a041f820ee07a761a264/ss/Screenshot%202025-04-04%20221516.png)

![add](https://github.com/KiranKumarMalik/Employee-Management-System-Using-Django/blob/bad7a6c3dc46068ad128a041f820ee07a761a264/ss/Screenshot%202025-04-04%20221547.png)
<h3>New department added successfully</h3>

# 4. To add position
![pos](https://github.com/KiranKumarMalik/Employee-Management-System-Using-Django/blob/e62f8fd696da204c12a2f00a311fa70f4cd6f2d3/ss/Screenshot%202025-04-04%20221617.png)

![add](https://github.com/KiranKumarMalik/Employee-Management-System-Using-Django/blob/e62f8fd696da204c12a2f00a311fa70f4cd6f2d3/ss/Screenshot%202025-04-04%20221728.png)

![added](https://github.com/KiranKumarMalik/Employee-Management-System-Using-Django/blob/e62f8fd696da204c12a2f00a311fa70f4cd6f2d3/ss/Screenshot%202025-04-04%20221745.png)
<h3>New position added successfully</h3>

# 5. To add Employee
![emp](https://github.com/KiranKumarMalik/Employee-Management-System-Using-Django/blob/e62f8fd696da204c12a2f00a311fa70f4cd6f2d3/ss/Screenshot%202025-04-04%20221824.png)

![add](https://github.com/KiranKumarMalik/Employee-Management-System-Using-Django/blob/e62f8fd696da204c12a2f00a311fa70f4cd6f2d3/ss/Screenshot%202025-04-04%20222130.png)

![added](https://github.com/KiranKumarMalik/Employee-Management-System-Using-Django/blob/e62f8fd696da204c12a2f00a311fa70f4cd6f2d3/ss/Screenshot%202025-04-04%20222153.png)
<h3>New Employee added successfully</h3>

# 6. To view a particular employee details
![view](https://github.com/KiranKumarMalik/Employee-Management-System-Using-Django/blob/6f8fe7ec8266f96ce784d45234612ce250ca3275/ss/Screenshot%202025-04-04%20222215.png)

# 7. To edit a particular employee details
![edit](https://github.com/KiranKumarMalik/Employee-Management-System-Using-Django/blob/6f8fe7ec8266f96ce784d45234612ce250ca3275/ss/Screenshot%202025-04-04%20222239.png)

![editsuccess](https://github.com/KiranKumarMalik/Employee-Management-System-Using-Django/blob/6f8fe7ec8266f96ce784d45234612ce250ca3275/ss/Screenshot%202025-04-04%20222328.png)
<h3>Updated successfully</h3>

# 8. Delete a particular employee records from database
![del](https://github.com/KiranKumarMalik/Employee-Management-System-Using-Django/blob/d463bf3e79d0266c00808fbd508414a292b8b3b1/ss/Screenshot%202025-04-04%20223832.png)

![delsuccess](https://github.com/KiranKumarMalik/Employee-Management-System-Using-Django/blob/d463bf3e79d0266c00808fbd508414a292b8b3b1/ss/Screenshot%202025-04-04%20223847.png)

# 9. Filter the data
![filter](https://github.com/KiranKumarMalik/Employee-Management-System-Using-Django/blob/d463bf3e79d0266c00808fbd508414a292b8b3b1/ss/Screenshot%202025-04-04%20223909.png)


## Table of Contents 
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Run the application](#run-the-application)
- [Run the tests](#run-the-tests)
- [View the application](#view-the-application)
- [Copyright and License](#copyright-and-license)

## Prerequisites

Install the following prerequisites:

1. [Python 3.8-3.11](https://www.python.org/downloads/)
<br> This project uses **Django v4.2.4**. For Django to work, you must install a correct version of Python on your machine. More information [here](https://django.readthedocs.io/en/stable/faq/install.html).
2. [Visual Studio Code](https://code.visualstudio.com/download)

## Installation

### 1. Create a virtual environment

From the **root** directory, run:

```bash
python -m virtualenv virtualenv_name
```

### 2. Activate the virtual environment

From the **root** directory, run:

On macOS:

```bash
source venv/bin/activate
```

On Windows:

```bash
venv\scripts\activate
```

### 3. Run migrations

From the **root** directory, run:

```bash
python manage.py makemigrations
```
```bash
python manage.py migrate
```

### 4. Create an admin user to access the Django Admin interface

From the **root** directory, run:

```bash
python manage.py createsuperuser
```

When prompted, enter a username, email, and password.

## Run the application

From the **root** directory, run:

```bash
python manage.py runserver
```

## Run the tests

From the **root** directory, run:

```bash
python manage.py test --pattern="tests.py"

```

## View the application

Go to http://127.0.0.1:8000/ to view the application.

## Copyright and License

Copyright © 2025 Kiran Kumar Malik. Code released under the MIT license.
