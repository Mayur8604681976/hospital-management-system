# Hospital Management System

A web-based Hospital Management System developed using Python, Flask, MySQL, and HTML. The project is designed to provide a centralized interface for organizing hospital-related information and simplifying routine administrative workflows.

## Overview

The Hospital Management System is a database-driven web application created as a practical software development project. It combines a Python backend with a MySQL database and a web interface.

The application is intended to support the organization of hospital records and administrative activities through a structured dashboard.

## Features and Modules

The interface is organized into the following hospital management sections:

- **Patients:** Patient information and record management.
- **Doctors & Staff:** Organization of doctor and staff information.
- **Appointments:** Hospital appointment management.
- **Billing & Payments:** Billing-related information.
- **Pharmacy:** Pharmacy-related records.
- **Wards & Rooms:** Ward and room organization.

Note: The availability of individual operations depends on the functionality implemented in the current version of the project.

## Technology Stack

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| Flask | Web application framework |
| MySQL | Relational database |
| PyMySQL | Python-to-MySQL connectivity |
| HTML | Web page structure |
| CSS | User interface styling |
| JavaScript | Client-side interactivity, where implemented |

## Project Structure

```text
hospital-management-system/
├── app.py
├── hospital_management.html
├── database.sql
├── requirements.txt
├── .gitignore
├── README.md
└── screenshots/
    └── dashboard.png
```

This is a suggested structure. Keep the actual filenames and folders consistent with your project.

## Prerequisites

Before running the application, install:

- Python 3.10 or a compatible version
- MySQL Server
- MySQL Workbench (optional, for database management)
- A web browser
- Git (optional, for version control)

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/hospital-management-system.git
cd hospital-management-system
```

Replace `YOUR-USERNAME` with your GitHub username.

Alternatively, download the repository ZIP file and extract it.

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```powershell
.\venv\Scripts\Activate.ps1
```

If PowerShell blocks activation, you can run the Python commands below using the environment's interpreter directly.

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Configure MySQL

Start your MySQL server and create the database if it does not already exist:

```sql
CREATE DATABASE hospital_db;
```

If a database schema file is included in the repository, review it and run its SQL statements in MySQL Workbench.

### 5. Configure the database connection

Check the database configuration in `app.py`. Set the host, port, database name, username, and password to match your local MySQL installation.

Do not publish your real database password or other secrets to GitHub. Use environment variables or a local configuration file excluded by `.gitignore`.

### 6. Run the application

From the project directory, run:

```bash
python app.py
```

Open the local URL printed in your terminal. Flask applications commonly use `http://127.0.0.1:5000/`, unless the application is configured to use another address or port.

## Database

The application uses MySQL for relational data storage. The exact tables and relationships should be documented according to the SQL schema implemented in the repository.

## Learning Outcomes

This project provides practical experience with:

- Python backend development
- Flask routing and web application structure
- Relational database design and SQL
- Connecting a Python application to MySQL
- Building a web-based administrative interface
- Organizing and documenting a software project

## Future Enhancements

Potential improvements include:

- Secure login and role-based access control
- Complete CRUD operations for patients and doctors
- Appointment scheduling and status tracking
- Billing and payment reports
- Pharmacy inventory tracking
- Ward and room availability management
- Form validation and error handling
- Deployment to a suitable hosting platform

These are proposed enhancements, not claims about features already implemented.

## Author

**Mayur Pandey**

B.Tech in Computer Science and Engineering

GitHub: https://github.com/YOUR-USERNAME

## License

This project is available for educational and portfolio purposes. Add a license file if you intend to grant others explicit permission to reuse, modify, or distribute the code.
