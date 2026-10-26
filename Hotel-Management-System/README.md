# 🏨 Hotel Management System

A web-based **Hotel Management System** designed to support hotel administration and cashier operations through a centralized digital management platform.

This project was developed as a software development project to implement a management system that helps organize hotel-related operational activities, particularly for **administrators and cashiers**.

## 📌 Project Overview

The **Hotel Management System** provides a digital platform for managing hotel operations through role-based access.

The system focuses on two main operational roles:

- 👨‍💼 **Admin** — manages hotel-related data and monitors operational activities.
- 💳 **Cashier** — handles cashier and transaction-related activities.

The project uses a separated frontend architecture, with the frontend implemented using **React** and the application backend built around **Laravel**.

## ✨ Key Features

### 👨‍💼 Admin Management

- Admin authentication
- Admin dashboard
- Management of hotel operational data
- Data management through CRUD functionality
- Monitoring of system activities

### 💳 Cashier Management

- Cashier authentication
- Cashier dashboard
- Transaction management
- Transaction-related data processing
- Support for daily cashier operations

### 🔐 Authentication & Access Control

- User authentication
- Role-based access
- Different interfaces and functionality based on user roles
- Protected application pages

### 🖥️ Web Interface

The application provides a modern web interface with a separated frontend architecture for a more organized development structure.

## 🛠️ Technology Stack

### Backend

- **Laravel**
- **PHP**
- **Composer**
- **Vite**

### Frontend

- **React 19**
- **React Router**
- **Tailwind CSS**
- **React Icons**
- **Axios**

### Development Tools

- Git & GitHub
- npm
- Composer
- Visual Studio Code

## 🏗️ Project Architecture

The project separates the application into backend and frontend components:

```text
Hotel-Management-System/
│
├── frontend/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── ...
│
├── public/
├── vendor/
├── package.json
├── composer.lock
├── vite.config.js
└── ...
```

### Frontend

The `frontend/` directory contains the React-based user interface, including:

- Page components
- Navigation
- Authentication interfaces
- Admin interface
- Cashier interface
- Reusable UI components

### Backend

The main application handles:

- Business logic
- Authentication
- Data processing
- Application routing
- Backend services
- Database interaction

## 🚀 Getting Started

### Prerequisites

Make sure the following software is installed:

- PHP
- Composer
- Node.js & npm
- Database server
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/fdlrahen/Hotel-Management-System.git
cd Hotel-Management-System
```

### 2. Install Backend Dependencies

```bash
composer install
```

### 3. Configure Environment

Create the environment configuration file:

```bash
cp .env.example .env
```

Then generate the application key:

```bash
php artisan key:generate
```

> On Windows, you can also create `.env` by copying `.env.example` manually.

Configure the database connection in `.env` according to your local database setup.

### 4. Install Frontend Dependencies

Navigate to the frontend directory:

```bash
cd frontend
npm install
```

### 5. Run the Frontend

```bash
npm start
```

### 6. Run the Backend

From the main project directory:

```bash
php artisan serve
```

The application can then be accessed through the local development server.

## 📊 Development Focus

This project demonstrates practical experience in:

- Full-stack web application development
- Frontend and backend integration
- Role-based application design
- CRUD-based information management
- Authentication and authorization
- REST/API communication
- Database-driven application development
- Responsive user interface development

## 🎯 Project Goals

The main goals of this project are to:

1. Digitize hotel administration and cashier workflows.
2. Separate system functionality according to user roles.
3. Provide a centralized platform for managing hotel operations.
4. Practice full-stack application development.
5. Apply modern frontend and backend technologies in a real-world management-system scenario.

## 📷 Screenshots

Screenshots of the application can be added here to demonstrate the user interface.

### Admin Dashboard

_Add screenshot here._

### Cashier Dashboard

_Add screenshot here._

### Login Page

_Add screenshot here._

## 🔮 Future Improvements

Potential improvements for future development include:

- Advanced hotel reservation management
- Room availability tracking
- Automated financial reporting
- More detailed analytics dashboards
- Improved notification system
- API documentation
- Automated testing
- Cloud deployment

## 👩‍💻 Author

**Ardiva Nugraheni Fadlilah**

Computer Science / Information Technology Graduate

GitHub: [@fdlrahen](https://github.com/fdlrahen)

---

⭐ This project is part of my software development portfolio and demonstrates my experience in building web-based management systems.
