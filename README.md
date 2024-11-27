# Role_Based_Access
Backend development project related to access control of a login and registration page based on their role like user, admin and moderator 
Overview

This project implements a Role-Based Access Control (RBAC) system to manage access control for users. The system allows administrators to define roles, assign users to roles, and control access to resources based on user roles.

Features

- Role management: Create, update, and delete roles
- User management: Assign users to roles and manage user permissions
- Resource management: Control access to resources based on user roles
- Access control: Enforce access control policies based on user roles and permissions

Requirements

- Python 3.8+
- Flask 2.0+
- Flask-RBAC 0.2+

Installation

1. Clone the repository: `git clone https://github.com/Meghali54/Role_Based_Access.git
2. Install dependencies: pip install -r requirements.txt
3. Run the application: flask run

Configuration

- Create a file with the following settings:
    - SECRET_KEY: A secret key for the application
    - DATABASE_URI: The URI for the database

Usage

1. Access the application at http://localhost:5000
2. Login as an administrator to manage roles, users, and resources
3. Assign users to roles and manage user permissions
4. Control access to resources based on user roles

Contributing

Contributions are welcome! Please submit a pull request with your changes.
This project is licensed under MIT guidance. 
